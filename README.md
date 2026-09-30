# kcsu/proto

Shared Protobuf schemas for KCSU services.

## Schemas

| Package          | Description                                |
|------------------|--------------------------------------------|
| `kcsu.lookup.v1` | Membership list of a Lookup group.         |
| `kcsu.alerts.v1` | A critical alert raised by a KCSU service. |

## Using it

Add this repo as a submodule, pinned to a release tag (e.g.: `v1.0.0`):

```sh
git submodule add https://github.com/KCSU/proto.git proto
cd proto && git checkout v1.0.0 && cd ..
```
