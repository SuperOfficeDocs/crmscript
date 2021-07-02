﻿---
uid: crmscript_ref_NSAppointmentAgent_CreateDefaultAppointmentEntityByType
title: NSAppointmentEntity CreateDefaultAppointmentEntityByType(Integer type)
intellisense: NSAppointmentAgent.CreateDefaultAppointmentEntityByType
keywords: NSAppointmentAgent, CreateDefaultAppointmentEntityByType
so.topic: reference
---

Creates a NSAppointmentEntity populated with the default values for the specific type.

**Parameters:**
 - **type** The type of task requested.
     - Enum: 0 = Unknown 
     - Enum: 1 = Appointment 
     - Enum: 2 = Document 
     - Enum: 3 = Email 
     - Enum: 4 = Fax 
     - Enum: 5 = Phone 
     - Enum: 6 = ToDo 
     - Enum: 7 = MailMergeDraft 
     - Enum: 8 = MailMergeFinal 
     - Enum: 9 = Report 
     - Enum: 10 = SaintAll 

**Returns:** NSAppointmentEntity with default values.

```crmscript
NSAppointmentAgent agent;
Integer type;
NSAppointmentEntity res = agent.CreateDefaultAppointmentEntityByType(type);
```

