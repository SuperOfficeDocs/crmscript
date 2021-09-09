---
uid: crmscript_ref_NSCommandInfo_GetReturnType
title: Integer GetReturnType()
intellisense: NSCommandInfo.GetReturnType
keywords: NSCommandInfo, GetReturnType
so.topic: reference
---

# Integer GetReturnType()

Declaration of what kind of return type the execution of this command will give.

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
NSCommandInfo thing;
Integer returnType  = thing.GetReturnType();
```
