---
uid: crmscript_ref_NSProduct_SetRights
title: SetRights(String rights)
intellisense: NSProduct.SetRights
keywords: NSProduct, GetRights
so.topic: reference
---

# SetRights(String rights)

Field1=right&Field2=right, etc. of any fields that have non-standard field access rights. Rights can be one of: N (=None or Hidden), R (=Read-only), W (=Writeable), M (=Mandatory). The fields will mostly be from the Quoteline table, but some added fields that are conceptually part of the quoteline, like Image will also be possibly to set rights on. Will be used by SuperOffice to control the user interface when showing the record.

**Parameter:** 
 - **rights** String

```crmscript
NSProduct thing;
String rights;
thing.SetRights(rights);
```

