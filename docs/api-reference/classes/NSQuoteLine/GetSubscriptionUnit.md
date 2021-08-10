---
uid: crmscript_ref_NSQuoteLine_GetSubscriptionUnit
title: String GetSubscriptionUnit()
intellisense: NSQuoteLine.GetSubscriptionUnit
keywords: NSQuoteLine, GetSubscriptionUnit
so.topic: reference
---

# String GetSubscriptionUnit()

Either a List id to an id from a connector provided list, or, if the connection doesn’t support lists, a text with the actual subscription unit.

**Returns:** String

```crmscript
NSQuoteLine thing;
String subscriptionUnit  = thing.GetSubscriptionUnit();
```

