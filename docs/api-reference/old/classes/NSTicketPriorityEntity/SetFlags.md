---
uid: crmscript_ref_NSTicketPriorityEntity_SetFlags
title: SetFlags(Integer flags)
intellisense: NSTicketPriorityEntity.SetFlags
keywords: NSTicketPriorityEntity, GetFlags
so.topic: reference
---

# SetFlags(Integer flags)

A bitmask of flags.

## Parameters

* **flags** Integer
* Enum: 0 = Unknown
* Enum: 1 = External
* Enum: 2 = Default
* Enum: 4 = AlertSchedule

```crmscript
NSTicketPriorityEntity thing;
Integer flags;
thing.SetFlags(flags);
```
