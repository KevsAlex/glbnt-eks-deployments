``` ssh
kubectl config set-context --current --namespace=wordpress-mysql
```

``` ssh
kubectl create secret generic mysql-pass --from-literal=password=mydb
```

- https://dev.to/aws-builders/how-to-deploy-wordpress-to-amazon-eks-using-helm-5dli
- https://www.linkedin.com/pulse/launching-wordpress-aws-using-eks-efs-mohd-junaid-mansuri/
- https://apeksh742.medium.com/aws-eks-service-for-deploying-wordpress-mysql-659841cce3b5
- https://aws.amazon.com/blogs/storage/running-wordpress-on-amazon-eks-with-amazon-efs-intelligent-tiering/
 
EFS
- https://docs.aws.amazon.com/eks/latest/userguide/efs-csi.html
