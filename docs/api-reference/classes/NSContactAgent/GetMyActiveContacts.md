---
uid: crmscript_ref_NSContactAgent_GetMyActiveContacts
title: NSContactActivity[] GetMyActiveContacts(DateTime activityStartTime, Integer[] contactCategories, Integer actionType)
intellisense: NSContactAgent.GetMyActiveContacts
keywords: NSContactAgent, GetMyActiveContacts
so.topic: reference
---

# NSContactActivity[] GetMyActiveContacts(DateTime activityStartTime, Integer[] contactCategories, Integer actionType)

Returns the contacts where there has been activity since activityStartTime. If activityStartTime is larger than the current date, all contacts with activity since the last log-out are returned. The result set can be filtered by category and action type.

## Parameters

* **activityStartTime** The start time of the activities. If the start time is set to a future date; activities since the user last logged out are returned.
* **contactCategories** Integer array of categories to filter on. If the array is empty contacts from all categories will be selected.
* **actionType** The type of action that has occurred. E.g. updates, deletes, new appointments, etc.

**Returns:** NSContactActivity[]

### Enum: actionType

* 0 = Unknown
* 1 = Created
* 2 = Updated
* 4 = NewActivity
* 8 = ActivityCompleted
* 16 = PersonAdded
* 32 = PersonUpdated
* 64 = DocumentAdded
* 127 = All

## Example

```crmscript
NSContactAgent agent;
DateTime activityStartTime;
Integer[] contactCategories;
Integer actionType;
NSContactActivity[] res = agent.GetMyActiveContacts(activityStartTime, contactCategories, actionType);
```
