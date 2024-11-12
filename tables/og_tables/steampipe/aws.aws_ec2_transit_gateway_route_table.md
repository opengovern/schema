# aws.aws_ec2_transit_gateway_route_table

## Description

AWS EC2 Transit Gateway Route Table

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| transit_gateway_route_table_id | text |  | true |  |  | The ID of the transit gateway route table. |
| transit_gateway_id | text |  | true |  |  | The ID of the transit gateway. |
| state | text |  | true |  |  | The state of the transit gateway route table. |
| creation_time | timestamp with time zone |  | true |  |  | The creation time of transit gateway route table. |
| default_association_route_table | boolean |  | true |  |  | Indicates whether this is the default association route table for the transit gateway. |
| default_propagation_route_table | boolean |  | true |  |  | Indicates whether this is the default propagation route table for the transit gateway. |
| tags_src | jsonb |  | true |  |  | A list of tags assigned. |
| tags | jsonb |  | true |  |  | A map of tags for the resource. |
| title | text |  | true |  |  | Title of the resource. |
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

![er](aws.aws_ec2_transit_gateway_route_table.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)