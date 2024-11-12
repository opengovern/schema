# azure.azure_compute_ssh_key

## Description

Azure Compute SSH Key

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| id | text |  | true |  |  | The unique ID identifying the resource in subscription. |
| name | text |  | true |  |  | Name of the SSH key. |
| type | text |  | true |  |  | The type of the resource in Azure. |
| public_key | text |  | true |  |  | SSH public key. |
| region | text |  | true |  |  | The Azure region/location in which the resource is located. |
| tags | jsonb |  | true |  |  | A map of tags for the resource. |
| resource_group | text |  | true |  |  | The resource group which holds this resource. |
| title | text |  | true |  |  | Title of the resource. |
| akas | jsonb |  | true |  |  | Array of globally unique identifier strings (also known as) for the resource. |
| cloud_environment | text |  | true |  |  | The Azure Cloud Environment. |
| subscription_id | text |  | true |  |  | The Azure Subscription ID in which the resource is located. |
| og_account_id | text |  | true |  |  | The Platform Account ID in which the resource is located. |
| og_resource_id | text |  | true |  |  | The unique ID of the resource in opengovernance. |
| kaytu_metadata | text |  | true |  |  | Platform Metadata of the Azure resource. |
| kaytu_description | jsonb |  | true |  |  | The full model description of the resource |
| sp_connection_name | text |  | true |  |  | Steampipe connection name. |
| sp_ctx | jsonb |  | true |  |  | Steampipe context in JSON form. |
| _ctx | jsonb |  | true |  |  | Steampipe context in JSON form. |

## Relations

![er](azure.azure_compute_ssh_key.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)