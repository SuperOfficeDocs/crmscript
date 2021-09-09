---
uid: crmscript_ref_NSAddressSyncData_SetAddressType
title: SetAddressType(Integer addressType)
intellisense: NSAddressSyncData.SetAddressType
keywords: NSAddressSyncData, GetAddressType
so.topic: reference
---

# SetAddressType(Integer addressType)

## Parameters

* **addressType** Integer

### Enum: address type

* 0 = Unknown
* 1 = ContactPostalAddress
* 2 = ContactStreetAddress
* 16387 = PersonPrivateAddress
* 8196 = QuoteBillingAddress
* 8197 = QuoteShippingAddress

## Example

```crmscript
NSAddressSyncData thing;
Integer addressType;
thing.SetAddressType(addressType);
```
