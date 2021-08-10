---
uid: crmscript_ref_NSUserAgent_CreateDefaultUserFromUserType
title: NSUser CreateDefaultUserFromUserType(Integer userType)
intellisense: NSUserAgent.CreateDefaultUserFromUserType
keywords: NSUserAgent, CreateDefaultUserFromUserType
so.topic: reference
---

# NSUser CreateDefaultUserFromUserType(Integer userType)

Create default NSUser providing the user type.  Only System and Anonymous users can be created without an exsisting person.  Use CreateDefaultUserFromUserTypeAndPersonId to create internal (i.e. Employee) or external users.

**Parameters:**
 - **userType** Type of associate for the user.  This can only be System or Anonymous. Use CreateDefaultUserFromUserTypeAndPersonId to create internal (i.e. Employee) or external users.
     - Enum: 0 = Unknown 
     - Enum: 1 = InternalAssociate 
     - Enum: 2 = ResourceAssociate 
     - Enum: 3 = ExternalAssociate 
     - Enum: 4 = AnonymousAssociate 
     - Enum: 5 = SystemAssociate 

**Returns:** NSUser

```crmscript
NSUserAgent agent;
Integer userType;
NSUser res = agent.CreateDefaultUserFromUserType(userType);
```

