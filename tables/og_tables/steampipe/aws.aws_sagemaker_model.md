# aws.aws_sagemaker_model

## Description

AWS Sagemaker Model

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| name | text |  | true |  |  | The name of the model. |
| arn | text |  | true |  |  | The Amazon Resource Name (ARN) of the model. |
| creation_time | timestamp with time zone |  | true |  |  | A timestamp that indicates when the model was created. |
| enable_network_isolation | boolean |  | true |  |  | If True, no inbound or outbound network calls can be made to or from the model container. |
| execution_role_arn | text |  | true |  |  | The Amazon Resource Name (ARN) of the IAM role that you specified for the model. |
| containers | jsonb |  | true |  |  | The containers in the inference pipeline. |
| inference_execution_config | jsonb |  | true |  |  | Specifies details of how containers in a multi-container endpoint are called. |
| primary_container | jsonb |  | true |  |  | The location of the primary inference code, associated artifacts, and custom environment map that the inference code uses when it is deployed in production. |
| vpc_config | jsonb |  | true |  |  | A VpcConfig object that specifies the VPC that this model has access to. |
| tags_src | jsonb |  | true |  |  | The list of tags for the model. |
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

![er](aws.aws_sagemaker_model.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)