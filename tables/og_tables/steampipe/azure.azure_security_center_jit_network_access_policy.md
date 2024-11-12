# azure.azure_security_center_jit_network_access_policy

## Description

Azure Security Center JIT Network Access Policy

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| name | text |  | true |  |  | The resource name. |
| id | text |  | true |  |  | The resource id. |
| type | text |  | true |  |  | The resource type. |
| kind | text |  | true |  |  | Kind of the resource. |
| provisioning_state | text |  | true |  |  | The provisioning state of the Just-in-Time policy. |
| virtual_machines | jsonb |  | true |  |  | Configurations for Microsoft.Compute/virtualMachines resource type. |
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

![er](azure.azure_security_center_jit_network_access_policy.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)