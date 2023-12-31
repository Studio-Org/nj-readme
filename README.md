## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_azurerm"></a> [azurerm](#provider\_azurerm) | n/a |

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_rg"></a> [rg](#module\_rg) | ../../modules/services | n/a |

## Resources

| Name | Type |
|------|------|
| [azurerm_client_config.current](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/data-sources/client_config) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_env"></a> [env](#input\_env) | n/a | `string` | n/a | yes |
| <a name="input_group_id_ro"></a> [group\_id\_ro](#input\_group\_id\_ro) | n/a | `string` | n/a | yes |
| <a name="input_location"></a> [location](#input\_location) | location where azure resource group needs to be created | `string` | n/a | yes |
| <a name="input_project_name"></a> [project\_name](#input\_project\_name) | n/a | `string` | n/a | yes |
| <a name="input_project_owner"></a> [project\_owner](#input\_project\_owner) | n/a | `string` | n/a | yes |
| <a name="input_project_short_description"></a> [project\_short\_description](#input\_project\_short\_description) | n/a | `string` | n/a | yes |
| <a name="input_resource_group_name"></a> [resource\_group\_name](#input\_resource\_group\_name) | azure resource group name | `string` | n/a | yes |
| <a name="input_start_date"></a> [start\_date](#input\_start\_date) | n/a | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_resource_group_name"></a> [resource\_group\_name](#output\_resource\_group\_name) | n/a |
