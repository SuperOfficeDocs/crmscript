---
uid: crmscript_ref_NSMailMergeTask_SetSingleEntryOnEachCompany
title: SetSingleEntryOnEachCompany(Bool singleEntryOnEachCompany)
intellisense: NSMailMergeTask.SetSingleEntryOnEachCompany
keywords: NSMailMergeTask, GetSingleEntryOnEachCompany
so.topic: reference
---

# SetSingleEntryOnEachCompany(Bool singleEntryOnEachCompany)

Should we only create one task on each company? If false, separate tasks will be created for all persons from the same company.

**Parameter:** 
 - **singleEntryOnEachCompany** Bool

```crmscript
NSMailMergeTask thing;
Bool singleEntryOnEachCompany;
thing.SetSingleEntryOnEachCompany(singleEntryOnEachCompany);
```

