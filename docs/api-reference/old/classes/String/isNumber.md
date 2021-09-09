---
uid: crmscript_ref_String_isNumber
title: String.isNumber()
intellisense: String.isNumber
keywords: isNumber()
so.topic: reference
so.yml: 1
---

# String.isNumber()

Returns true if it is possible to convert a string to an integer. If the string begins with a number it is possible to convert until an illegal character occurs.

## Example

```crmscript
//Returns true
printLine(String("123").isNumber().toString());
//Returns true, conversion to Integer will return 123
printLine(String("123nok").isNumber().toString());
//Returns false
printLine(String("nok123").isNumber().toString());
//Returns true, conversion to Integer will return 12
printLine(String("12nok3").isNumber().toString());
```

* **Returns:** True if the string can be converted to an integer, false otherwise.
