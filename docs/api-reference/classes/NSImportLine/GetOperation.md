---
uid: crmscript_ref_NSImportLine_GetOperation
title: Integer GetOperation()
intellisense: NSImportLine.GetOperation
keywords: NSImportLine, GetOperation
so.topic: reference
---

# Integer GetOperation()

Which operation will be used? This is a read-only property

**Returns:** Integer

     - Enum: 0 = Unknown 
     - Enum: 1 = PersonAdded 
     - Enum: 2 = PersonUpdated 
     - Enum: 4 = PersonNoChange 
     - Enum: 8 = ContactAdded 
     - Enum: 16 = ContactUpdated 
     - Enum: 32 = ContactNoChange 
     - Enum: 64 = ProductAdded 
     - Enum: 128 = ProductUpdated 
     - Enum: 256 = ProductNoChange 
     - Enum: 512 = Obs 
     - Enum: 1024 = ObsERPDuplicate 

```crmscript
NSImportLine thing;
Integer operation  = thing.GetOperation();
```

