# aws.aws_networkfirewall_firewall_policy

## Description

AWS Network Firewall Policy

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| name | text |  | true |  |  | The descriptive name of the rule group. |
| arn | text |  | true |  |  | The Amazon Resource Name (ARN) of the rule group. |
| firewall_policy_id | text |  | true |  |  | The unique identifier for the firewall policy. |
| consumed_stateful_rule_capacity | bigint |  | true |  |  | The number of capacity units currently consumed by the policy's stateful rules. |
| consumed_stateless_rule_capacity | bigint |  | true |  |  | The number of capacity units currently consumed by the policy's stateless rules. |
| description | text |  | true |  |  | A description of the firewall policy. |
| firewall_policy_status | text |  | true |  |  | The current status of the firewall policy. |
| last_modified_time | timestamp with time zone |  | true |  |  | The last time that the firewall policy was changed. |
| number_of_associations | bigint |  | true |  |  | The number of firewall policies that use this rule group. |
| encryption_configuration | jsonb |  | true |  |  | A complex type that contains the Amazon Web Services KMS encryption configuration settings for your firewall policy. |
| firewall_policy | jsonb |  | true |  |  | The policy for the specified firewall policy. |
| tags_src | jsonb |  | true |  |  | A list of tags assigned to the resource. |
| title | text |  | true |  |  | Title of the resource. |
| tags | jsonb |  | true |  |  | A map of tags for the resource. |
| akas | jsonb |  | true |  |  | Array of globally unique identifier strings (also known as) for the resource. |
| partition | text |  | true |  |  | The AWS partition in which the resource is located (aws, aws-cn, or aws-us-gov). |
| region | text |  | true |  |  | The AWS Region in which the resource is located. |
| account_id | text |  | true |  |  | The AWS Account ID in which the resource is located. |
| og_account_id | text |  | true |  |  | The Platform Account ID in which the resource is located. |
| og_resource_id | text |  | true |  |  | The unique ID of the resource in opengovernance. |
| og_metadata | text |  | true |  |  | Platform Metadata of the AWS resource. |
| og_description | jsonb |  | true |  |  | The full model description of the resource |
| _ctx | jsonb |  | true |  |  | Steampipe context in JSON form, e.g. connection_name. |

## Relations

![er](aws.aws_networkfirewall_firewall_policy.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)