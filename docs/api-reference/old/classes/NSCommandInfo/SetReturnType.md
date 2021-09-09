---
uid: crmscript_ref_NSCommandInfo_SetReturnType
title: SetReturnType(Integer returnType)
intellisense: NSCommandInfo.SetReturnType
keywords: NSCommandInfo, GetReturnType
so.topic: reference
---

# SetReturnType(Integer returnType)

Declaration of what kind of return type the execution of this command will give.

## Parameters

* **returnType** Integer

### Enum: ReturnType

* 0 = None
* 1 = Message
* 2 = SoProtocol
* 3 = CustomGui
* 4 = Other
* 5 = URL

## Example

```crmscript
NSCommandInfo thing;
Integer returnType;
thing.SetReturnType(returnType);
```
