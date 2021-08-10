---
uid: crmscript_ref_NSFreeText_SetSingleWordOperator
title: SetSingleWordOperator(Integer singleWordOperator)
intellisense: NSFreeText.SetSingleWordOperator
keywords: NSFreeText, GetSingleWordOperator
so.topic: reference
---

# SetSingleWordOperator(Integer singleWordOperator)

Starts with, contains or exact match

**Parameter:** 
 - **singleWordOperator** Integer
     - Enum: 1 = Contains 
     - Enum: 2 = StartsWith 
     - Enum: 3 = ExactMatch 

```crmscript
NSFreeText thing;
Integer singleWordOperator;
thing.SetSingleWordOperator(singleWordOperator);
```

