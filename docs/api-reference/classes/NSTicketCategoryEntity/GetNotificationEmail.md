---
uid: crmscript_ref_NSTicketCategoryEntity_GetNotificationEmail
title: String GetNotificationEmail()
intellisense: NSTicketCategoryEntity.GetNotificationEmail
keywords: NSTicketCategoryEntity, GetNotificationEmail
so.topic: reference
---

# String GetNotificationEmail()

Comma separated list of addresses to notify when requests are redelegated to (unassigned) in this category.

**Returns:** String

```crmscript
NSTicketCategoryEntity thing;
String notificationEmail  = thing.GetNotificationEmail();
```

