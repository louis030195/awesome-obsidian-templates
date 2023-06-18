
# {{title}} - {{date}}

## Link to recent fasting
```dataviewjs
dv.list(dv.pages().where((p) =>  !p.file.path.includes("Template") && p.file.path != dv.current().file.path && p.file.tags.includes("#fasting")).sort((p) => p.file.ctime, 'desc').limit(5).map((e) => "[["+e.file.path+"]]"))
```
## Meta

**Date:** {{date}}

The situation/context:

## Metrics

|                    | -24h | +24h | +48h | +72h+ | break +24h |
| ------------------ | ---- | ---- | ---- | ----- | ---------- |
| Energy             |      |      |      |       |            |
| Happy              |      |      |      |       |            |
| Anxious            |      |      |      |       |            |
| Ouraring readiness |      |      |      |       |            |
| Ouraring sleep     |      |      |      |       |            |
| Ouraring activity  |      |      |      |       |            |

```json
<% tp.user.ouraring_readiness() %>
```

```json
<% tp.user.ouraring_sleep() %>
```

## Insights
