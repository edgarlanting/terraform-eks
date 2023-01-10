# terraform-eks
A repository to make it really easy to setup an EKS cluster via Terraform

Upon cloning this repo, you might want to provide a custom cluster name in `main.tf` for the `cluster_name` variable. 
If you want to create the cluster in a specific availability zone, you will need to change the region in `variables.tf`

Then, run `terraform init`, followed by `terraform apply` to set up an EKS cluster.
