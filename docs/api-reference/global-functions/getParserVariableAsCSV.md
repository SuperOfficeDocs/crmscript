---
title: getParserVariableAsCSV
description: String getParserVariableAsCSV(String paramName, Bool forceQuoting)
intellisense: Void.getParserVariableAsCSV
langref: 1
keywords: getParserVariableAsCSV(String,Bool)
so.topic: reference
---

# getParserVariableAsCSV

Return a variable from the global Parser instance as a comma separated string.

* **paramName:** The name of the variable to return.
* **forceQuoting:** If True, then each element will be quoted. If false, only elements which needs to be quoted (i.e. when they contain a comma) will be quoted.

