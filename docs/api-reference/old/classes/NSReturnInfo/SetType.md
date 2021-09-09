---
uid: crmscript_ref_NSReturnInfo_SetType
title: SetType(Integer type)
intellisense: NSReturnInfo.SetType
keywords: NSReturnInfo, GetType
so.topic: reference
---

# SetType(Integer type)

How is the return value to be understood by the caller

## Parameters

* **type** Integer

### Enum: ReturnType

* 0 = None
* 1 = Message
* 2 = SoProtocol
* 3 = CustomGui
* 4 = Other
* 5 = URL

## Example

```crmscript
NSReturnInfo thing;
Integer type;
thing.SetType(type);
```
