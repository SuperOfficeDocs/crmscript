---
uid: crmscript_ref_String_regexp_String_pattern
title: String.regexp(String pattern)
intellisense: String.regexp
keywords: regexp(String)
so.topic: reference
so.yml: 1
---

# String.regexp(String pattern)

Uses regexp pattern on the String object. Support for sub-expressions is also present.

The regexp is case-insensitive.

## Example

```crmscript
String s;
s="blabla 1234-4567-7890-1111 asdfasdfasdf";
String[] res = s.regexp("(\\d{4})-(\\d{4})-(\\d{4})-(\{4})");
for (Integer i=0;i<res.length(); i++)
{
  print("Result: " + res[i] + "\n");
}
```

## Interpretation of the returned array

No matches will result in an array with length 0.

* res[0] will point to the entire matched string.
* res[1 ... n-1] will point to the matches of the sub-expressions.
