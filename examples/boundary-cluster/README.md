<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >=1.2.0 |
| <a name="requirement_hcp"></a> [hcp](#requirement\_hcp) | >=0.10.0 |

## Providers

No providers.

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_hcp"></a> [hcp](#module\_hcp) | ../../ | n/a |

## Resources

No resources.

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_hcp_client_id"></a> [hcp\_client\_id](#input\_hcp\_client\_id) | Client ID used to authenticate with HCP. Environment variables are preferred | `string` | `null` | no |
| <a name="input_hcp_client_secret"></a> [hcp\_client\_secret](#input\_hcp\_client\_secret) | Client secret used to authenticate with HCP. Environment variables are preferred | `string` | `null` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_cluster_url"></a> [cluster\_url](#output\_cluster\_url) | n/a |
| <a name="output_username"></a> [username](#output\_username) | n/a |
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->