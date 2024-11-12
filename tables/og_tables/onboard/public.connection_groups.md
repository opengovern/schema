# public.connection_groups

## Description

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| name | text |  | false |  |  |  |
| query | text |  | true |  |  |  |

## Constraints

| Name | Type | Definition |
| ---- | ---- | ---------- |
| connection_groups_pkey | PRIMARY KEY | PRIMARY KEY (name) |

## Indexes

| Name | Definition |
| ---- | ---------- |
| connection_groups_pkey | CREATE UNIQUE INDEX connection_groups_pkey ON public.connection_groups USING btree (name) |

## Relations

![er](public.connection_groups.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)