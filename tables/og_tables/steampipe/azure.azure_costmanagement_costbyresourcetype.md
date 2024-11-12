# azure.azure_costmanagement_costbyresourcetype

## Description

Azure CostManagement CostByResourceType

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| id | text |  | true |  |  | The id of the costbyresourcetype. |
| usage_date | bigint |  | true |  |  | Usage date |
| cost | double precision |  | true |  |  | Cost |
| resource_type | text |  | true |  |  | Resource type |
| service_name | text |  | true |  |  | Service Name |
| publisher_type | text |  | true |  |  | Publisher Type |
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

![er](azure.azure_costmanagement_costbyresourcetype.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)