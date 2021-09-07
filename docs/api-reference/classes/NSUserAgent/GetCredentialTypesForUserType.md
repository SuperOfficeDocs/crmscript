---
uid: crmscript_ref_NSUserAgent_GetCredentialTypesForUserType
title: NSCredentialType[] GetCredentialTypesForUserType(Integer userType)
intellisense: NSUserAgent.GetCredentialTypesForUserType
keywords: NSUserAgent, GetCredentialTypesForUserType
so.topic: reference
---

# NSCredentialType[] GetCredentialTypesForUserType(Integer userType)

Get available credential types that can be used for the specified user type.

## Parameters

* **userType** The user type to retrieve credential types for

**Returns:** NSCredentialType[]

## Enum: associateType

* 0 = Unknown
* 1 = InternalAssociate
* 2 = ResourceAssociate
* 3 = ExternalAssociate
* 4 = AnonymousAssociate
* 5 = SystemAssociate

## Example

```crmscript
NSUserAgent agent;
Integer userType;
NSCredentialType[] res = agent.GetCredentialTypesForUserType(userType);
```
