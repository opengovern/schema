# aws.aws_s3_multi_region_access_point

## Description

AWS S3 Multi Region Access Point

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| name | text |  | true |  |  | The name of the Multi-Region Access Point. |
| alias | text |  | true |  |  | The alias for the Multi-Region Access Point. |
| created_at | timestamp with time zone |  | true |  |  | When the Multi-Region Access Point create request was received. |
| status | text |  | true |  |  | The current status of the Multi-Region Access Point. CREATING and DELETING are temporary states that exist while the request is propagating and being completed. |
| public_access_block | jsonb |  | true |  |  | The PublicAccessBlock configuration that you want to apply to this Amazon S3 account. |
| regions | jsonb |  | true |  |  | A collection of the Regions and buckets associated with the Multi-Region Access Point. |
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

![er](aws.aws_s3_multi_region_access_point.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)