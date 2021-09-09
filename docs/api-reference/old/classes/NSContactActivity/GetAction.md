---
uid: crmscript_ref_NSContactActivity_GetAction
title: Integer GetAction()
intellisense: NSContactActivity.GetAction
keywords: NSContactActivity, GetAction
so.topic: reference
---

# Integer GetAction()

The activity that has occurred on this contact.

**Returns:** Integer

## Enum: actionType

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
NSContactActivity thing;
Integer action  = thing.GetAction();
```
