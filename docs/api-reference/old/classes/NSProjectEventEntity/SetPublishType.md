---
uid: crmscript_ref_NSProjectEventEntity_SetPublishType
title: SetPublishType(Integer publishType)
intellisense: NSProjectEventEntity.SetPublishType
keywords: NSProjectEventEntity, GetPublishType
so.topic: reference
---

# SetPublishType(Integer publishType)

Type of publishing action, 0 = Unknown, 1 = to external persons

## Parameters

* **publishType** Integer
* Enum: 0 = Undefined
* Enum: 1 = External

```crmscript
NSProjectEventEntity thing;
Integer publishType;
thing.SetPublishType(publishType);
```
