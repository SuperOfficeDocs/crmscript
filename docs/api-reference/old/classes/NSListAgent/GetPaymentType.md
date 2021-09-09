---
uid: crmscript_ref_NSListAgent_GetPaymentType
title: NSPaymentType GetPaymentType(Integer paymentTypeId);
intellisense: NSListAgent.GetPaymentType
keywords: NSListAgent, GetPaymentType
so.topic: reference
---

# NSPaymentType GetPaymentType(Integer paymentTypeId);

Gets an NSPaymentType object.

## Parameters

* **paymentTypeId** The identifier of the NSPaymentType object

**Returns:** NSPaymentType

```crmscript
NSListAgent agent;
NSPaymentType thing = agent.GetPaymentType(123);
```

