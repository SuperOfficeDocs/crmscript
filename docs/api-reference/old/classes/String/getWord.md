---
uid: crmscript_ref_String_getWord_Integer_num
title: String.getWord(Integer num)
intellisense: String.getWord
keywords: getWord(Integer)
so.topic: reference
so.yml: 1
---

# String.getWord(Integer num)

Return a numbered word from a string

This function returns the word number num from the string. Word 0 is the first word in the string, even if it's after some leading whitespace.

For example, `String("  this is a test")`.getWord(1) yields "is".

## Parameters

* **The:** number of the word to return, starting at 0
* **Returns:** The word