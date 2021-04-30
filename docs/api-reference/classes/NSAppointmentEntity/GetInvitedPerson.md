﻿---
uid: crmscript_ref_NSAppointmentEntity_GetInvitedPerson
title: Person GetInvitedPerson()
intellisense: NSAppointmentEntity.GetInvitedPerson
keywords: NSAppointmentEntity, GetInvitedPerson
so.topic: reference
---

If the appointment is a booking, the invited persons may be your associates, but you are also able to invite contact persons from other companies to join your meeting. They do not receive an invitation, unless you send them one by email, but you can see in the appointment that persons other than your associates have been invited to a meeting. Each invited person will have an appointment slave record.

**Returns:** Person


```crmscript
NSAppointmentEntity thing;
Person invitedPerson  = thing.GetInvitedPerson();
```

