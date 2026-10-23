# ▶ Backend

_Plan `backend` · [doc](../docs/backend.md) · data as of 2026-10-23 04:12 UTC · [all subsets](README.md)_

**50% done** · ✓ 1 done · ▶ 1 active · ○ 0 ready · ✕ 2 blocked

```mermaid
%%{init: {"themeVariables": {"pie1": "#0ca30c", "pie2": "#2a78d6", "pie3": "#d03b3b", "pieOpacity": "1", "pieSectionTextColor": "#000", "pieStrokeColor": "#fff", "pieStrokeWidth": "2px", "pieOuterStrokeWidth": "0px"}}}%%
pie showData title Items by status
  "✓ done" : 1
  "▶ active" : 1
  "✕ blocked" : 2
```

| Item | Status | Ticked | Depends on |
|---|---|--:|---|
| [#1](https://github.com/bvraghav/pm-dummy/issues/1) Database schema | ✓ done | 2/2 |  |
| [#2](https://github.com/bvraghav/pm-dummy/issues/2) API endpoints | ▶ active | 2/2 | ✓ #1 |
| [#3](https://github.com/bvraghav/pm-dummy/issues/3) Auth tokens | ✕ blocked |  | ▶ #2, ✓ other#1 |
| [#8](https://github.com/bvraghav/pm-dummy/issues/8) Broken reference | ✕ blocked |  | ? `no-such-id` |

## Changes

From 2026-10-23 03:44 to 2026-10-23 04:12 UTC:

- no changes

## Needs attention

### ✕ Blocked

- [#3](https://github.com/bvraghav/pm-dummy/issues/3) Auth tokens, waiting on ▶ [#2](https://github.com/bvraghav/pm-dummy/issues/2) API endpoints
- [#8](https://github.com/bvraghav/pm-dummy/issues/8) Broken reference, waiting on ? `no-such-id` (unresolved)

### Metadata problems

- [#8](https://github.com/bvraghav/pm-dummy/issues/8) Broken reference: unresolved dependency `no-such-id`


## Next up

Nothing ready to start.

## Dependency graph

_Legend: ✓ done · ▶ active (assigned or partly ticked) · ○ ready (nothing it waits on is open) · ✕ blocked · arrows point from a dependency to what waits on it; dotted lines join a plan to its items._

```mermaid
flowchart LR
  n0["✓ #1 Database schema"]:::done
  n1["▶ #2 API endpoints"]:::active
  n2["✕ #3 Auth tokens"]:::blocked
  n3["✕ #8 Broken reference"]:::blocked
  n4["✓ other#1 Database schema"]:::done
  n0 --> n1
  n1 --> n2
  n4 --> n2
  n3_u0["? no-such-id"]:::unknown --> n3
  classDef done fill:#0ca30c,color:#000,stroke:#0ca30c
  classDef active fill:#2a78d6,color:#fff,stroke:#2a78d6
  classDef ready fill:#eda100,color:#000,stroke:#eda100
  classDef blocked fill:#d03b3b,color:#fff,stroke:#d03b3b
  classDef unknown fill:#898781,color:#000,stroke:#898781
  classDef dropped fill:#898781,color:#000,stroke:#898781
```

## Trend

_The trend starts once there are two days of history._
