---
uid: crmscript_ref_NSTypicalSearches_SetDeleteLeftovers
title: SetDeleteLeftovers(Bool deleteLeftovers)
intellisense: NSTypicalSearches.SetDeleteLeftovers
keywords: NSTypicalSearches, GetDeleteLeftovers
so.topic: reference
---

# SetDeleteLeftovers(Bool deleteLeftovers)

If true, then any TypicalSearch records in the database that are NOT referenced in this call, should be deleted

**Parameter:** 
 - **deleteLeftovers** Bool

```crmscript
NSTypicalSearches thing;
Bool deleteLeftovers;
thing.SetDeleteLeftovers(deleteLeftovers);
```

