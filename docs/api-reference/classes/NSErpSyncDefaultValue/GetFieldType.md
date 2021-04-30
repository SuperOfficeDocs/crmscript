﻿---
uid: crmscript_ref_NSErpSyncDefaultValue_GetFieldType
title: FieldMetadataType GetFieldType()
intellisense: NSErpSyncDefaultValue.GetFieldType
keywords: NSErpSyncDefaultValue, GetFieldType
so.topic: reference
---

Field type

**Returns:** FieldMetadataType

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
FieldMetadataType fieldType  = thing.GetFieldType();
```

