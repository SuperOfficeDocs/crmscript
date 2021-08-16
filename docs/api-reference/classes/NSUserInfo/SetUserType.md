---
uid: crmscript_ref_NSUserInfo_SetUserType
title: SetUserType(Integer userType)
intellisense: NSUserInfo.SetUserType
keywords: NSUserInfo, GetUserType
so.topic: reference
---

# SetUserType(Integer userType)

**Parameter:** 
 - **userType** Integer
     - Enum: 0 = Unknown 
     - Enum: 1 = InternalAssociate 
     - Enum: 2 = ResourceAssociate 
     - Enum: 3 = ExternalAssociate 
     - Enum: 4 = AnonymousAssociate 
     - Enum: 5 = SystemAssociate 

```crmscript
NSUserInfo thing;
Integer userType;
thing.SetUserType(userType);
```

