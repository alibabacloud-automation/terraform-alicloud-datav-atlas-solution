# Complete Example

This example demonstrates the complete usage of the DataV for Atlas module.

## Overview

This example creates a complete DataV for Atlas solution including:

- VPC (Virtual Private Cloud) with configurable CIDR block
- VSwitch (Virtual Switch) in specified availability zone
- PostgreSQL RDS instance with PostGIS extension support
- Database account with proper privileges
- Database for spatial data storage
- Public connection for external access

## Prerequisites

- Terraform >= 1.0
- Alibaba Cloud account with appropriate permissions
- Alibaba Cloud CLI configured (optional)

## Usage

1. Clone this repository
2. Navigate to this example directory
3. Copy `terraform.tfvars.example` to `terraform.tfvars` and customize the values
4. Run the following commands:

```bash
terraform init
terraform plan
terraform apply
```