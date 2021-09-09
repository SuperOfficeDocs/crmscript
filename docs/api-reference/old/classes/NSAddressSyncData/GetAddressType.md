---
uid: crmscript_ref_NSAddressSyncData_GetAddressType
title: Integer GetAddressType()
intellisense: NSAddressSyncData.GetAddressType
keywords: NSAddressSyncData, GetAddressType
so.topic: reference
---

# Integer GetAddressType()

**Returns:** Integer

## Enum: address type

* 0 = Unknown
* 1 = ContactPostalAddress
* 2 = ContactStreetAddress
* 16387 = PersonPrivateAddress
* 8196 = QuoteBillingAddress
* 8197 = QuoteShippingAddress

## Example

```crmscript
NSAddressSyncData thing;
Integer addressType  = thing.GetAddressType();
```
