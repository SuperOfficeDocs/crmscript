---
uid: crmscript_ref_NSErpSyncAgent_ForceResyncNoBlankValues
title: NSPluginResponse ForceResyncNoBlankValues(Integer erpConnectionId, Integer[] internalKeyIds)
intellisense: NSErpSyncAgent.ForceResyncNoBlankValues
keywords: NSErpSyncAgent, ForceResyncNoBlankValues
so.topic: reference
---

# NSPluginResponse ForceResyncNoBlankValues(Integer erpConnectionId, Integer[] internalKeyIds)

Force resync from CRM or given Erp connection to all other connections and tell the sync that you don't want blank values to overwrite non-blank values. Useful on import.

**Returns:** NSPluginResponse

## Parameters

| Parameter | Type |Description |
|---|---|---|
| erpConnectionId | Integer | If positive, resync from the given ERP connection |
| internalKeyIds | Integer[] | The internal keys of the entities to resync, or empty to resync all |

## Examples

```crmscript
NSErpSyncAgent agent;
Integer erpConnectionId;
Integer[] internalKeyIds;
NSPluginResponse res = agent.ForceResyncNoBlankValues(erpConnectionId, internalKeyIds);
```
