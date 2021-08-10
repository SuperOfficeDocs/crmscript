---
uid: crmscript_ref_NSSuggestedAppointmentEntity_GetDeleted
title: Bool GetDeleted()
intellisense: NSSuggestedAppointmentEntity.GetDeleted
keywords: NSSuggestedAppointmentEntity, GetDeleted
so.topic: reference
---

# Bool GetDeleted()

0 -> record is active 1 -> record is 'deleted' and should not be shown in lists

**Returns:** Bool

```crmscript
NSSuggestedAppointmentEntity thing;
Bool deleted  = thing.GetDeleted();
```

