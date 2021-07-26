﻿---
uid: crmscript_ref_NSFindAgent_GetSpecifiedCriteriaInformationWithDefaults
title: CriteriaInformation GetSpecifiedCriteriaInformationWithDefaults(String storageType, String providerName, String storageKey, String[] desiredColumnNames, String[] staticColumns)
intellisense: NSFindAgent.GetSpecifiedCriteriaInformationWithDefaults
keywords: NSFindAgent, GetSpecifiedCriteriaInformationWithDefaults
so.topic: reference
---

Get criteria information from a set of saved criteria, for a specific set of columns. The result contains the restrictions in two forms: fully populated NSArchiveRestrictionInfo objects, used to display details and for saving changes; and as a list suitable for an Archive control. ALL columns specified in the call will be present in the results; those that do not have corresponding criteria set will have empty values and the default (first) operator, with the IsActive flag set to false.

**Parameters:**
 - **storageType** Restriction storage type specification, either 'Criteria' or 'Reporter' (or possible extensions)
 - **providerName** Name of archive provider that is the intended consumer of the restrictions
 - **storageKey** Storage key to be interpreted by the restriction storage provider, when it fetches criteria for the search
 - **desiredColumnNames** Optional array of restrictions that are to be EXCLUDED from the CriteriaArchiveRows part of the result. In the Find dialogs, that corresponds to the 'static' fields, to avoid duplicating them in the 'Match also' criteria list. This array can be null, indicating that all restrictions should be included in the criteria list.
 - **staticColumns** Optional array of restrictions that are to be EXCLUDED from the CriteriaArchiveRows part of the result. In the Find dialogs, that corresponds to the 'static' fields, to avoid duplicating them in the 'Match also' criteria list. This array can be null, indicating that all restrictions should be included in the criteria list.

**Returns:** The result contains the restrictions in two forms: fully populated NSArchiveRestrictionInfo objects, used to display details and for saving changes; and as a list suitable for an Archive control. ALL columns specified in the call will be present in the results; those that do not have corresponding criteria set will have empty values and the default (first) operator, with the IsActive flag set to false.

```crmscript
NSFindAgent agent;
String storageType;
String providerName;
String storageKey;
String[] desiredColumnNames;
String[] staticColumns;
CriteriaInformation res = agent.GetSpecifiedCriteriaInformationWithDefaults(storageType, providerName, storageKey, desiredColumnNames, staticColumns);
```

