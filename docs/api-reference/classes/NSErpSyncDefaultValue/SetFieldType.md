﻿---
uid: crmscript_ref_NSErpSyncDefaultValue_SetFieldType
title: SetFieldType(FieldMetadataType fieldType)
intellisense: NSErpSyncDefaultValue.SetFieldType
keywords: NSErpSyncDefaultValue, GetFieldType
so.topic: reference
---

Field type

**Parameter:** 
 - **fieldType** FieldMetadataType
     - Enum: 0 = Checkbox 
     - Enum: 1 = Text 
     - Enum: 2 = Password 
     - Enum: 3 = Integer 
     - Enum: 4 = Double 
     - Enum: 5 = List 
     - Enum: 6 = Date 
     - Enum: 99 = Label 

```crmscript
NSErpSyncDefaultValue thing;
FieldMetadataType fieldType;
thing.SetFieldType(fieldType);
```
