# Terraform Module Template
Template for Terraform modules

## Variables
### Input
| Variables    | Description                        | Default |
|:-------------|:-----------------------------------|:--------|
| company      | Company name                       |         |
| environment  | Environment name                   |         |
| name         | Name                               |         |
| service      | Service name                       |         |
| tags         | Tags for the certificate resources |         |

### Output
| Variables         | Description               |
|:------------------|:--------------------------|
|  |  |

## How to
Specify the module source and the provider information.

### Sample
```
provider "aws" {
    region = ""
    shared_credentials_file = ""
}

module "module-name" {
    source = "github.com/Haplo-tech/Terraform.Module.Template"
    company = ""
    environment = ""
    name = ""
    service = ""
    tags = {}
}
```
