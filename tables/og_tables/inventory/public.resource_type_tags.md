# public.resource_type_tags

## Description

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| key | text |  | false |  |  |  |
| value | text[] |  | true |  |  |  |
| created_at | timestamp with time zone |  | true |  |  |  |
| updated_at | timestamp with time zone |  | true |  |  |  |
| deleted_at | timestamp with time zone |  | true |  |  |  |
| resource_type | citext |  | false |  | [public.resource_types](public.resource_types.md) |  |

## Constraints

| Name | Type | Definition |
| ---- | ---- | ---------- |
| fk_resource_types_tags | FOREIGN KEY | FOREIGN KEY (resource_type) REFERENCES resource_types(resource_type) ON UPDATE CASCADE ON DELETE CASCADE |
| resource_type_tags_pkey | PRIMARY KEY | PRIMARY KEY (key, resource_type) |

## Indexes

| Name | Definition |
| ---- | ---------- |
| resource_type_tags_pkey | CREATE UNIQUE INDEX resource_type_tags_pkey ON public.resource_type_tags USING btree (key, resource_type) |
| idx_resource_type_tags_deleted_at | CREATE INDEX idx_resource_type_tags_deleted_at ON public.resource_type_tags USING btree (deleted_at) |

## Relations

![er](public.resource_type_tags.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)