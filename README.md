# Provisioning an EKS Cluster

## To change the log type

Amend the following log types in the eks-cluster.tf eks module as per the requirement

```terraform
cluster_enabled_log_types = ["api", "audit", "authenticator", "controllerManager", "scheduler"]
```

## Steps to provision a EKS Cluster

```terraform
1. terraform init
2. terraform validate
3. terraform plan
4. terraform apply -auto-approve
```

## To get the output of the deployed state

```terraform
1. terraform output -json
```

## Steps to delete the EKS cluster

```terraform
1. terraform destroy
```

## For more help

```terraform
1. terraform -help
```
