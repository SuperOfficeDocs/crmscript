---
uid: crmscript_ref_NSUserDefinedFieldInfo_GetProgId
title: String GetProgId()
intellisense: NSUserDefinedFieldInfo.GetProgId
keywords: NSUserDefinedFieldInfo, GetProgId
so.topic: reference
---

# String GetProgId()

Programmatic ID, for use by software that needs to find a particular field. Carried over like udefIdentity across generations. Use a Company.Product.Field format to avoid naming conflicts; the Company name SuperOffice is reserved.

**Returns:** String

```crmscript
NSUserDefinedFieldInfo thing;
String progId  = thing.GetProgId();
```

