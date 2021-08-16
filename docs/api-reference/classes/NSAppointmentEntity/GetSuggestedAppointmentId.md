---
uid: crmscript_ref_NSAppointmentEntity_GetSuggestedAppointmentId
title: Integer GetSuggestedAppointmentId()
intellisense: NSAppointmentEntity.GetSuggestedAppointmentId
keywords: NSAppointmentEntity, GetSuggestedAppointmentId
so.topic: reference
---

# Integer GetSuggestedAppointmentId()

Suggested guide item that this appointment is an instance of (Note: NOT VALID for document-type appointments, they have their own link)

**Returns:** Integer

```crmscript
NSAppointmentEntity thing;
Integer suggestedAppointmentId  = thing.GetSuggestedAppointmentId();
```

