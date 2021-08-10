---
uid: crmscript_ref_NSFreeText_GetSingleWordOperator
title: Integer GetSingleWordOperator()
intellisense: NSFreeText.GetSingleWordOperator
keywords: NSFreeText, GetSingleWordOperator
so.topic: reference
---

# Integer GetSingleWordOperator()

Starts with, contains or exact match

**Returns:** Integer

     - Enum: 1 = Contains 
     - Enum: 2 = StartsWith 
     - Enum: 3 = ExactMatch 

```crmscript
NSFreeText thing;
Integer singleWordOperator  = thing.GetSingleWordOperator();
```

