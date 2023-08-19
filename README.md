# tf

### terraform

```bash
terraform init
```
```bash
terraform plan --var-file="environment/sit.tfvars" -out="terraform.tfplan"
```
```bash
terraform apply "terraform.tfplan"
```
```bash
terraform destroy --var-file="environment/sit.tfvars"
```

### terraform workspace

```bash
terraform workspace list
```

```bash
terraform workspace new sit
```

```bash
terraform workspace select sit
```

### force-unlock
```
terraform force-unlock [options] LOCK_ID
```


### Checks that all Terraform configuration files adhere to a canonical format

```
terraform fmt -check
```

