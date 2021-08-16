---
uid: crmscript_ref_NSMailMergeTask_GetSingleEntryOnEachCompany
title: Bool GetSingleEntryOnEachCompany()
intellisense: NSMailMergeTask.GetSingleEntryOnEachCompany
keywords: NSMailMergeTask, GetSingleEntryOnEachCompany
so.topic: reference
---

# Bool GetSingleEntryOnEachCompany()

Should we only create one task on each company? If false, separate tasks will be created for all persons from the same company.

**Returns:** Bool

```crmscript
NSMailMergeTask thing;
Bool singleEntryOnEachCompany  = thing.GetSingleEntryOnEachCompany();
```

