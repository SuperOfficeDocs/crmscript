---
uid: crmscript_ref_EabEntry_getValue_String_p_0
title: EabEntry.getValue(String field)
intellisense: EabEntry.getValue
sortOrder: 277
keywords: getValue(String)
so.topic: reference
---

# String getValue(String field)

Get the value of the given field in the EabEntry instance.

## Available fields

* name
* email
* sms
* folderId
* dbi_agent_id
* dbi_key
* dbi_last_syncronized
* dbi_last_modified
* dbi_delete

## Parameters

| Parameter | Type | Description |
|---|---|---|
| Field | String | The name of the field. |

## Example

    EabEntry eab;
   
    Bool b = eab.load(15);
    print(b.toString());
   
    eab.setValue("name", "test");
    print(eab.getValue("name"));
