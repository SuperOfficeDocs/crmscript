---
uid: crmscript_ref_NSSuggestedAppointment_GetDeleted
title: Integer GetDeleted()
intellisense: NSSuggestedAppointment.GetDeleted
keywords: NSSuggestedAppointment, GetDeleted
so.topic: reference
---

# Integer GetDeleted()

0 -> record is active 1 -> record is 'deleted' and should not be shown in lists

**Returns:** Integer

```crmscript
NSSuggestedAppointment thing;
Integer deleted  = thing.GetDeleted();
```

