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


