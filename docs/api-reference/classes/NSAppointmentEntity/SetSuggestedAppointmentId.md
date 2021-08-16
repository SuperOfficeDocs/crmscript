---
uid: crmscript_ref_NSAppointmentEntity_SetSuggestedAppointmentId
title: SetSuggestedAppointmentId(Integer suggestedAppointmentId)
intellisense: NSAppointmentEntity.SetSuggestedAppointmentId
keywords: NSAppointmentEntity, GetSuggestedAppointmentId
so.topic: reference
---

# SetSuggestedAppointmentId(Integer suggestedAppointmentId)

Suggested guide item that this appointment is an instance of (Note: NOT VALID for document-type appointments, they have their own link)

**Parameter:** 
 - **suggestedAppointmentId** Integer

```crmscript
NSAppointmentEntity thing;
Integer suggestedAppointmentId;
thing.SetSuggestedAppointmentId(suggestedAppointmentId);
```

