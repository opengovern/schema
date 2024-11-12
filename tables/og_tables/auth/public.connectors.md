# public.connectors

## Description

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| id | bigint | nextval('connectors_id_seq'::regclass) | false |  |  |  |
| created_at | timestamp with time zone |  | true |  |  |  |
| updated_at | timestamp with time zone |  | true |  |  |  |
| deleted_at | timestamp with time zone |  | true |  |  |  |
| user_count | bigint | 0 | true |  |  |  |
| connector_id | text |  | true |  |  |  |
| connector_type | text |  | true |  |  |  |
| connector_sub_type | text |  | true |  |  |  |
| last_update | timestamp with time zone |  | true |  |  |  |

## Constraints

| Name | Type | Definition |
| ---- | ---- | ---------- |
| connectors_pkey | PRIMARY KEY | PRIMARY KEY (id) |

## Indexes

| Name | Definition |
| ---- | ---------- |
| connectors_pkey | CREATE UNIQUE INDEX connectors_pkey ON public.connectors USING btree (id) |
| idx_connectors_deleted_at | CREATE INDEX idx_connectors_deleted_at ON public.connectors USING btree (deleted_at) |

## Relations

![er](public.connectors.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)