---
uid: crmscript_ref_NSCheckoutInfo_GetState
title: Integer GetState()
intellisense: NSCheckoutInfo.GetState
keywords: NSCheckoutInfo, GetState
so.topic: reference
---

# Integer GetState()

Checkout state

**Returns:** Integer

## Enum: Checkout state

* 0 = NotCheckedOut
* 1 = CheckedOutOwn
* 2 = CheckedOutOther
* 3 = LockingNotSupported

## Example

```crmscript
NSCheckoutInfo thing;
Integer state  = thing.GetState();
```
