# azure.azure_cosmosdb_restorable_database_account

## Description

Azure Cosmos DB Restorable Database Account

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| name | text |  | true |  |  | The friendly name that identifies the restorable database account. |
| id | text |  | true |  |  | Contains ID to identify a restorable database account uniquely. |
| account_name | text |  | true |  |  | The name of the global database account. |
| api_type | text |  | true |  |  | The API type of the restorable database account. |
| creation_time | timestamp with time zone |  | true |  |  | The creation time of the restorable database account. |
| deletion_time | timestamp with time zone |  | true |  |  | The time at which the restorable database account has been deleted. |
| type | text |  | true |  |  | Type of the resource. |
| restorable_locations | jsonb |  | true |  |  | List of regions where the database account can be restored from. |
| title | text |  | true |  |  | Title of the resource. |
| akas | jsonb |  | true |  |  | Array of globally unique identifier strings (also known as) for the resource. |
| region | text |  | true |  |  | The Azure region/location in which the resource is located. |
| resource_group | text |  | true |  |  | The resource group which holds this resource. |
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

![er](azure.azure_cosmosdb_restorable_database_account.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)