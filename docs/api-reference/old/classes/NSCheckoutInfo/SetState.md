---
uid: crmscript_ref_NSCheckoutInfo_SetState
title: SetState(Integer state)
intellisense: NSCheckoutInfo.SetState
keywords: NSCheckoutInfo, GetState
so.topic: reference
---

# SetState(Integer state)

Checkout state

## Parameters

* **state** Integer

### Enum: Checkout state

* 0 = NotCheckedOut
* 1 = CheckedOutOwn
* 2 = CheckedOutOther
* 3 = LockingNotSupported

## Example

```crmscript
NSCheckoutInfo thing;
Integer state;
thing.SetState(state);
```
