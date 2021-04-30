﻿---
uid: crmscript_ref_NSPersonEntity_SetCorrespondingAssociate
title: SetCorrespondingAssociate(Associate correspondingAssociate)
intellisense: NSPersonEntity.SetCorrespondingAssociate
keywords: NSPersonEntity, GetCorrespondingAssociate
so.topic: reference
---

The associate corresponding to this person. Will be empty if the person is not a user (internal associate user, external user).

**Parameter:** 
 - **correspondingAssociate** Associate

```crmscript
NSPersonEntity thing;
Associate correspondingAssociate;
thing.SetCorrespondingAssociate(correspondingAssociate);
```
