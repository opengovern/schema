# azure.azure_app_service_plan

## Description

Azure App Service Plan

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| name | text |  | true |  |  | The friendly name that identifies the app service plan |
| id | text |  | true |  |  | Contains ID to identify an app service plan uniquely |
| kind | text |  | true |  |  | Contains the kind of the resource |
| type | text |  | true |  |  | The resource type of the app service plan |
| hyper_v | boolean |  | true |  |  | Specify whether resource is Hyper-V container app service plan |
| is_spot | boolean |  | true |  |  | Specify whether this App Service Plan owns spot instances, or not |
| is_xenon | boolean |  | true |  |  | Specify whether resource is Hyper-V container app service plan |
| maximum_elastic_worker_count | bigint |  | true |  |  | Maximum number of total workers allowed for this ElasticScaleEnabled App Service Plan |
| maximum_number_of_workers | bigint |  | true |  |  | Maximum number of instances that can be assigned to this App Service plan |
| per_site_scaling | boolean |  | true |  |  | Specify whether apps assigned to this App Service plan can be scaled independently |
| provisioning_state | text |  | true |  |  | Provisioning state of the App Service Environment |
| reserved | boolean |  | true |  |  | Specify whether the resource is Linux app service plan, or not |
| sku_capacity | bigint |  | true |  |  | Current number of instances assigned to the resource. |
| sku_family | text |  | true |  |  | Family code of the resource SKU |
| sku_name | text |  | true |  |  | Name of the resource SKU |
| sku_size | text |  | true |  |  | Size specifier of the resource SKU |
| sku_tier | text |  | true |  |  | Service tier of the resource SKU |
| status | text |  | true |  |  | App Service plan status |
| apps | jsonb |  | true |  |  | Site a web app, a mobile app backend, or an API app. |
| title | text |  | true |  |  | Title of the resource. |
| tags | jsonb |  | true |  |  | A map of tags for the resource. |
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

![er](azure.azure_app_service_plan.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)