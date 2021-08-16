---
uid: crmscript_ref_NSSuggestedAppointment_GetSaleTypeStageLinkId
title: Integer GetSaleTypeStageLinkId()
intellisense: NSSuggestedAppointment.GetSaleTypeStageLinkId
keywords: NSSuggestedAppointment, GetSaleTypeStageLinkId
so.topic: reference
---

# Integer GetSaleTypeStageLinkId()

Link to saleTypeStageLink, the anchor for sale guide items. Either this OR projectAnchorId should be set, not both at the same time.

**Returns:** Integer

```crmscript
NSSuggestedAppointment thing;
Integer saleTypeStageLinkId  = thing.GetSaleTypeStageLinkId();
```

