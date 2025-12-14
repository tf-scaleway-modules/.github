# Terraform Scaleway Modules

Official, community-maintained **Terraform and OpenTofu modules for Scaleway**.

This organization provides reusable, opinionated infrastructure modules to help teams build, deploy, and operate workloads on **Scaleway** using infrastructure as code best practices.

##  What you’ll find here

-  Production-ready **Terraform modules**
-  Fully compatible with **OpenTofu**
-  Modular, composable, and opinionated design
-  Examples with sane defaults
-  Clear documentation for every module

##  Usage

Example usage with Terraform or OpenTofu:

```hcl
module "vpc" {
  source  = "tf-scaleway-modules/vpc/scaleway"
  version = ">= 1.0.0"

  project_id = var.project_id
  region     = "fr-par"
}
```

## Documentation

Each module repository contains:

- A detailed README.md
- Inputs and outputs documentation
- One or more usage examples

Please refer to individual repositories for module-specific details.

## Contributing

Contributions are welcome and encouraged.

You can contribute by:

- Reporting bugs or requesting features via GitHub Issues
- Submitting pull requests with clear descriptions
- Improving documentation or examples

Please follow existing conventions and keep changes focused.

## License

Unless stated otherwise, all modules are licensed under the Apache License 2.0.