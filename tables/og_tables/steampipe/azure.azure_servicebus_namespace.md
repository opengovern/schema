# azure.azure_servicebus_namespace

## Description

Azure ServiceBus Namespace

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| name | text |  | true |  |  | The name of the resource. |
| id | text |  | true |  |  | The unique id identifying the resource in subscription. |
| type | text |  | true |  |  | The type of the resource. |
| provisioning_state | text |  | true |  |  | The provisioning state of the namespace. |
| zone_redundant | boolean |  | true |  |  | Enabling this property creates a Premium Service Bus Namespace in regions supported availability zones. |
| created_at | timestamp with time zone |  | true |  |  | The time the namespace was created. |
| disable_local_auth | boolean |  | true |  |  | This property disables SAS authentication for the Service Bus namespace. |
| metric_id | text |  | true |  |  | The identifier for Azure insights metrics. |
| servicebus_endpoint | text |  | true |  |  | Specifies the endpoint used to perform Service Bus operations. |
| sku_capacity | bigint |  | true |  |  | The specified messaging units for the tier. For Premium tier, capacity are 1,2 and 4. |
| sku_name | text |  | true |  |  | Name of this SKU. Valid valuer are: 'Basic', 'Standard', 'Premium'. |
| sku_tier | text |  | true |  |  | The billing tier of this particular SKU. Valid values are: 'Basic', 'Standard', 'Premium'. |
| status | text |  | true |  |  | Status of the namespace. |
| updated_at | timestamp with time zone |  | true |  |  | The time the namespace was updated. |
| diagnostic_settings | jsonb |  | true |  |  | A list of active diagnostic settings for the servicebus namespace. |
| encryption | jsonb |  | true |  |  | Specifies the properties of BYOK encryption configuration. Customer-managed key encryption at rest (Bring Your Own Key) is only available on Premium namespaces. |
| network_rule_set | jsonb |  | true |  |  | Describes the network rule set for specified namespace. The ServiceBus Namespace must be Premium in order to attach a ServiceBus Namespace Network Rule Set. |
| private_endpoint_connections | jsonb |  | true |  |  | The private endpoint connections of the namespace. |
| authorization_rules | jsonb |  | true |  |  | The authorization rules for a namespace. |
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

![er](azure.azure_servicebus_namespace.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)