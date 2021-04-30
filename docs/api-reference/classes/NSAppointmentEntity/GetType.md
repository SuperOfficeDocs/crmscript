﻿---
uid: crmscript_ref_NSAppointmentEntity_GetType
title: Integer GetType()
intellisense: NSAppointmentEntity.GetType
keywords: NSAppointmentEntity, GetType
so.topic: reference
---

The different types of appointment, if the appointment is supposed to be shown in the diary or checklist, or if it's a document. See the different types of appointments in the database manual.

**Returns:** Integer

     - Enum: 0 = Unknown 
     - Enum: 1 = inDiary 
     - Enum: 2 = inChecklist 
     - Enum: 3 = Note 
     - Enum: 4 = Document 
     - Enum: 5 = SavedReport 
     - Enum: 6 = BookingForDiary 
     - Enum: 7 = BookingForChecklist 
     - Enum: 8 = MergeDraft 
     - Enum: 9 = MergeFinal 

```crmscript
NSAppointmentEntity thing;
Integer type  = thing.GetType();
```

