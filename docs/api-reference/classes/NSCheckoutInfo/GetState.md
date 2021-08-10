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

     - Enum: 0 = NotCheckedOut 
     - Enum: 1 = CheckedOutOwn 
     - Enum: 2 = CheckedOutOther 
     - Enum: 3 = LockingNotSupported 

```crmscript
NSCheckoutInfo thing;
Integer state  = thing.GetState();
```

