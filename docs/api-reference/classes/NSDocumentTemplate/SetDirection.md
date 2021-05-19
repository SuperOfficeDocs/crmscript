---
uid: crmscript_class_nsdocumenttemplate_setdirection
title: SetDirection()
description: CRMScript method in the NSDocumentTemplate class that sets the direction of a document template
intellisense: NSDocumentTemplate.SetDirection
keywords: NSDocumentTemplate, GetDirection, SetDirection(DocTmplDirection direction), SetDirection(NSDocTmplDirection)
so.topic: reference
---

# SetDirection()

## Parameters

| Parameter | Type | Description |
|---|---|---|
| direction | DocTmplDirection | |

### Directions

| Enum | Direction |
|---|---|
| 0 | Unknown |
| 1 | Incoming |
| 2 | Outgoing |
| 3 | SaintAll |

See EAppntDirection

## Examples

```crmscript
NSDocumentTemplate thing;
DocTmplDirection direction;
thing.SetDirection(direction);
```
