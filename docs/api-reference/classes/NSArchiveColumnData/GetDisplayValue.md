---
uid: crmscript_ref_NSArchiveColumnData_GetDisplayValue
title: String GetDisplayValue()
intellisense: NSArchiveColumnData.GetDisplayValue
keywords: NSArchiveColumnData, GetDisplayValue
so.topic: reference
---

# String GetDisplayValue()

The visible display value for an archive cell. It is always a string, and other data types are converted to string according to the invariant culture. "[I:123]" or "[D:2014-09-13]". Further conversion to the local culture is the responsibility of the client.

**Returns:** String

```crmscript
NSArchiveColumnData thing;
String displayValue  = thing.GetDisplayValue();
```

