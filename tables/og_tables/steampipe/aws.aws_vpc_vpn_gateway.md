# aws.aws_vpc_vpn_gateway

## Description

AWS VPC VPN Gateway

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| vpn_gateway_id | text |  | true |  |  | The ID of the virtual private gateway. |
| state | text |  | true |  |  | The current state of the virtual private gateway. |
| type | text |  | true |  |  | The type of VPN connection the virtual private gateway supports. |
| amazon_side_asn | bigint |  | true |  |  | The private Autonomous System Number (ASN) for the Amazon side of a BGP session. |
| availability_zone | text |  | true |  |  | The Availability Zone where the virtual private gateway was created, if applicable. This field may be empty or not returned. |
| vpc_attachments | jsonb |  | true |  |  | Any VPCs attached to the virtual private gateway. |
| tags_src | jsonb |  | true |  |  | A list of tags that are attached to VPN gateway. |
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

![er](aws.aws_vpc_vpn_gateway.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)