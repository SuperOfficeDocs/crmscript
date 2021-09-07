---
uid: crmscript_ref_NSReturnInfo_GetType
title: Integer GetType()
intellisense: NSReturnInfo.GetType
keywords: NSReturnInfo, GetType
so.topic: reference
---

# Integer GetType()

How is the return value to be understood by the caller

**Returns:** Integer

## Enum: ReturnType

* 0 = None
* 1 = Message
* 2 = SoProtocol
* 3 = CustomGui
* 4 = Other
* 5 = URL

## Example

```crmscript
NSReturnInfo thing;
Integer type  = thing.GetType();
```
