# aws.aws_docdb_cluster_instance

## Description

AWS DocumentDB Cluster Instance

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| db_instance_identifier | text |  | true |  |  | Contains a user-provided database identifier. This identifier is the unique key that identifies an instance. |
| db_instance_arn | text |  | true |  |  | The Amazon Resource Name (ARN) for the instance. |
| db_cluster_identifier | text |  | true |  |  | Contains the name of the cluster that the instance is a member of if the instance is a member of a cluster. |
| db_instance_status | text |  | true |  |  | Specifies the current state of this database. |
| db_instance_class | text |  | true |  |  | Contains the name of the compute and memory capacity class of the instance. |
| dbi_resource_id | text |  | true |  |  | The Amazon Web Services Region-unique, immutable identifier for the instance. |
| availability_zone | text |  | true |  |  | Specifies the name of the availability zone the instance is located in. |
| backup_retention_period | bigint |  | true |  |  | Specifies the number of days for which automatic snapshots are retained. |
| ca_certificate_identifier | text |  | true |  |  | The identifier of the CA certificate for this DB instance. |
| copy_tags_to_snapshot | boolean |  | true |  |  | Specifies whether tags are copied from the DB instance to snapshots of the DB instance, or not. |
| db_subnet_group_arn | text |  | true |  |  | The Amazon Resource Name (ARN) for the DB subnet group. |
| db_subnet_group_description | text |  | true |  |  | Provides the description of the DB subnet group. |
| db_subnet_group_name | text |  | true |  |  | The name of the DB subnet group. |
| db_subnet_group_status | text |  | true |  |  | Provides the status of the DB subnet group. |
| endpoint_address | text |  | true |  |  | Specifies the DNS address of the instance. |
| endpoint_hosted_zone_id | text |  | true |  |  | Specifies the ID that Amazon Route 53 assigns when you create a hosted zone. |
| endpoint_port | bigint |  | true |  |  | Specifies the port that the database engine is listening on. |
| engine | text |  | true |  |  | The name of the database engine to be used for this instance. |
| engine_version | text |  | true |  |  | Indicates the database engine version. |
| instance_create_time | timestamp with time zone |  | true |  |  | Provides the date and time the instance was created. |
| kms_key_id | text |  | true |  |  | If StorageEncrypted is true, the KMS key identifier for the encrypted instance. |
| latest_restorable_time | timestamp with time zone |  | true |  |  | Specifies the latest time to which a database can be restored with point-in-time restore. |
| preferred_backup_window | text |  | true |  |  | Specifies the daily time range during which automated backups are created. |
| preferred_maintenance_window | text |  | true |  |  | Specifies the weekly time range during which system maintenance can occur. |
| promotion_tier | bigint |  | true |  |  | A value that specifies the order in which an Amazon DocumentDB replica is promoted to the primary instance after a failure of the existing primary instance. |
| publicly_accessible | boolean |  | true |  |  | Specifies the accessibility options for the DB instance. |
| storage_encrypted | boolean |  | true |  |  | Specifies whether or not the instance is encrypted. |
| vpc_id | text |  | true |  |  | Provides the VpcId of the DB subnet group. |
| enabled_cloudwatch_logs_exports | jsonb |  | true |  |  | A list of log types that this instance is configured to export to CloudWatch Logs. |
| pending_modified_values | jsonb |  | true |  |  | Specifies that changes to the instance are pending. |
| status_infos | jsonb |  | true |  |  | The status of a read replica. |
| subnets | jsonb |  | true |  |  | A list of subnet elements. |
| vpc_security_groups | jsonb |  | true |  |  | A list of VPC security group elements that the instance belongs to. |
| tags_src | jsonb |  | true |  |  | A list of tags attached to the Instance. |
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

![er](aws.aws_docdb_cluster_instance.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)