---
uid: crmscript_class_nsdocumenttemplateentity_setdirection
title: SetDirection(DocTmplDirection direction)
description: CRMScript method in the NSDocumentTemplateEntity class that sets the direction of a document template
intellisense: NSDocumentTemplateEntity.SetDirection
keywords: NSDocumentTemplateEntity, GetDirection, SetDirection(DocTmplDirection direction), SetDirection(NSDocTmplDirection)
so.topic: reference
---

# SetDirection()

## Parameter

| Parameter | Type | Description |
|---|---|---|
| direction | DocTmplDirection | |

| Enum | Direction |
|---|---|
| 0 | Unknown |
| 1 | Incoming |
| 2 | Outgoing |
| 3 | SaintAll |

See EAppntDirection

## Examples

```crmscript
NSDocumentTemplateEntity thing;
DocTmplDirection direction;
thing.SetDirection(direction);
```
