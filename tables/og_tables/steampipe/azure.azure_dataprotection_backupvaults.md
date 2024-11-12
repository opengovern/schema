# azure.azure_dataprotection_backupvaults

## Description

Azure DataProtection BackupVaults

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| id | text |  | true |  |  | The id of the backupvaults. |
| name | text |  | true |  |  | The name of the backupvaults. |
| type | text |  | true |  |  | The resource type. |
| location | text |  | true |  |  | The location of the backup vault. |
| provisioning_state | text |  | true |  |  | The provisioning state of the backup vault resource. |
| resource_move_state | text |  | true |  |  | The resource move state for the backup vault. |
| storage_settings | jsonb |  | true |  |  | The storage settings of the backup vault. |
| monitoring_settings | jsonb |  | true |  |  | The Monitoring Settings. |
| identity | jsonb |  | true |  |  | Input Managed Identity Details. |
| system_data | jsonb |  | true |  |  | Metadata pertaining to creation and last modification of the resource. |
| title | text |  | true |  |  | Title of the resource. |
| tags | jsonb |  | true |  |  | A map of tags for the resource. |
| akas | jsonb |  | true |  |  | Array of globally unique identifier strings (also known as) for the resource. |
| region | text |  | true |  |  | The Azure region where the resource is located. |
| resource_group | text |  | true |  |  | The resource group in which the resource is located. |
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

![er](azure.azure_dataprotection_backupvaults.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)