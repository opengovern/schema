# aws.aws_service_discovery_namespace

## Description

AWS Service Discovery Namespace

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| name | text |  | true |  |  | The name of the namespace. |
| id | text |  | true |  |  | The ID of the namespace. |
| arn | text |  | true |  |  | The Amazon Resource Name (ARN) that Cloud Map assigns to the namespace when you create it. |
| create_date | timestamp with time zone |  | true |  |  | The date and time that the namespace was created. |
| description | text |  | true |  |  | A description for the namespace. |
| service_count | bigint |  | true |  |  | The number of services that were created using the namespace. |
| type | text |  | true |  |  | The type of the namespace, either public or private. |
| dns_properties | jsonb |  | true |  |  | A complex type that contains the ID for the Route 53 hosted zone that Cloud Map creates when you create a namespace. |
| http_properties | jsonb |  | true |  |  | A complex type that contains the name of an HTTP namespace. |
| tags_src | jsonb |  | true |  |  | Information about the tags associated with the namespace. |
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

![er](aws.aws_service_discovery_namespace.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)