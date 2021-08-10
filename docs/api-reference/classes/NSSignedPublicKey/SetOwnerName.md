---
uid: crmscript_ref_NSSignedPublicKey_SetOwnerName
title: SetOwnerName(String ownerName)
intellisense: NSSignedPublicKey.SetOwnerName
keywords: NSSignedPublicKey, GetOwnerName
so.topic: reference
---

# SetOwnerName(String ownerName)

The name of the module owner, not visible in GUI but used in the code. OwnerName SUPEROFFICE is reserved and may NEVER be used by partners. This must be in UPPER CASE and only contain A-Z and 0-9. NO EXTENDED CHARACTERS please.

**Parameter:** 
 - **ownerName** String

```crmscript
NSSignedPublicKey thing;
String ownerName;
thing.SetOwnerName(ownerName);
```

