---
uid: crmscript_ref_NSArchiveAgent_GetArchiveListByColumnsWithHeaderWithContext2
title: NSArchiveListResult GetArchiveListByColumnsWithHeaderWithContext2(String providerName, String columns, String sortOrder, String restriction, String entities, Integer page, Integer pageSize, String options, String context)
intellisense: NSArchiveAgent.GetArchiveListByColumnsWithHeaderWithContext2
keywords: NSArchiveAgent, GetArchiveListByColumnsWithHeaderWithContext2
so.topic: reference
---

# NSArchiveListResult GetArchiveListByColumnsWithHeaderWithContext2(String providerName, String columns, String sortOrder, String restriction, String entities, Integer page, Integer pageSize, String options, String context)

Get a page of results for an archive list, with context parameter, explicitly specifying the restrictions as strings, orderby and chosen columns; as well as a name/value string formatted set of options. The return value includes a header that has various extra information, in addition to the actual rows.

**Parameters:**
 - **providerName** The name of the archive provider to use; it will be created via the ArchiveProviderFactory from a plugin
 - **columns** Comma separated list of the names of the columns wanted.
 - **sortOrder** Sort order for the archive. "name asc, dept desc" Can be null, which indicates 'no particular order'
 - **restriction** Archive restrictions as string. "updated > '2009.1.1' and registeredBy = 2" Archives will generally throw an exception if no restrictions are set. Pass in an empty array if you really do not want restrictions, but remember that you may end up fetching the first page of millions of rows.
 - **entities** Comma separated list of entities to include. Can be null, which indicates 'include all entities'
 - **page** Page number, page 0 is the first page. Negative page numbers are interpreted as number of rows to skip.
 - **pageSize** Page size, which should be kept reasonable (say, no more than 1000 rows at a time)
 - **options** name=value&amp;... formatted set of options. "rowcount=true" will cause the rowcount to be calculated and populated.
 - **context** Context parameter, url-encoded string context parameter for ArchiveProvider constructor

**Returns:** Header with optional row count, plus array of archive list items, where each item represents one row of data (row level data + the requested columns)

```crmscript
NSArchiveAgent agent;
String providerName;
String columns;
String sortOrder;
String restriction;
String entities;
Integer page;
Integer pageSize;
String options;
String context;
NSArchiveListResult res = agent.GetArchiveListByColumnsWithHeaderWithContext2(providerName, columns, sortOrder, restriction, entities, page, pageSize, options, context);
```

