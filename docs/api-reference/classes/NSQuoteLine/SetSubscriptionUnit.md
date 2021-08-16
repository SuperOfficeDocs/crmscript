---
uid: crmscript_ref_NSQuoteLine_SetSubscriptionUnit
title: SetSubscriptionUnit(String subscriptionUnit)
intellisense: NSQuoteLine.SetSubscriptionUnit
keywords: NSQuoteLine, GetSubscriptionUnit
so.topic: reference
---

# SetSubscriptionUnit(String subscriptionUnit)

Either a List id to an id from a connector provided list, or, if the connection doesn’t support lists, a text with the actual subscription unit.

**Parameter:** 
 - **subscriptionUnit** String

```crmscript
NSQuoteLine thing;
String subscriptionUnit;
thing.SetSubscriptionUnit(subscriptionUnit);
```

