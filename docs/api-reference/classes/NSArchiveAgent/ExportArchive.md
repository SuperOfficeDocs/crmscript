---
uid: crmscript_ref_NSArchiveAgent_ExportArchive
title: NSExportArchiveResult ExportArchive(String providerName, String context, String[] desiredEntities, String[] columns, NSArchiveOrderByInfo[] sortOrder, NSArchiveRestrictionInfo[] restrictions, String exportType, String[] selectedRowIds, Integer estimatedRowCount)
intellisense: NSArchiveAgent.ExportArchive
keywords: NSArchiveAgent, ExportArchive
so.topic: reference
---

# NSExportArchiveResult ExportArchive(String providerName, String context, String[] desiredEntities, String[] columns, NSArchiveOrderByInfo[] sortOrder, NSArchiveRestrictionInfo[] restrictions, String exportType, String[] selectedRowIds, Integer estimatedRowCount)

Exports the target archive to a downloadable format.

## Parameters

| Parameter | Type |Description |
|---|---|---|
| providerName | String | The name of the archive provider to use. It will be created via the ArchiveProviderFactory from a plugin |
| context | String | Context parameter, URL-encoded string context parameter for ArchiveProvider constructor |
| desiredEntities | String [] | Comma-separated list of the names of the desired entities. |
| columns | String[] | Comma-separated list of the names of the columns wanted; supports display names |
| sortOrder | NSArchiveOrderByInfo[] | |
| restrictions | NSArchiveRestrictionInfo[] | |
| exportType | String | To what format the archive should be exported; Excel, etc. |
| selectedRowIds | String [] | |
| estimatedRowCount | Integer | The estimated amount of rows to be exported. Used to determine if the operation should be run as a batch task or immediately. |
