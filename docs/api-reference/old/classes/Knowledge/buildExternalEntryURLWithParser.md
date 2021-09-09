---
uid: crmscript_ref_Knowledge_buildExternalEntryURLWithParser_Integer_kbId_Parser_parser
title: Knowledge.buildExternalEntryURLWithParser(Integer kbId, Parser parser)
intellisense: Knowledge.buildExternalEntryURLWithParser
sortOrder: 456
keywords: buildExternalEntryURLWithParser(Integer,Parser)
so.topic: reference
---

# Knowledge.buildExternalEntryURLWithParser(Integer kbId, Parser parser)

This function builds an url to the customer center to view a knowledgebase entry.

The function fetch the baseUrl from the registry table with reg_id 61. Then it parses the url with the input parser, and returns the url.

* **Returns:** the url to the knowledgebase entry.

## Parameters

| Parameter | Type |Description |
|---|---|---|
| kbId | Integer | The ID of the knowledgebase entry to link to. |
| parser | Parser | The parser to use to parse the URL |
