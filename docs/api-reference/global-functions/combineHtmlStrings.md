---
title: combineHtmlStrings
description: String combineHtmlStrings(Vector htmlStrings)
intellisense: Void.combineHtmlStrings
langref: 1
keywords: combineHtmlStrings(Vector)
so.topic: reference
---

# combineHtmlStrings

This function will take several strings, each containing a html document, and combine them into one html string.

The head contents in each string is combined into the head tag of the output string, except for the title tag. The title tag is taken from the first string in the vector.

The body content is likewise combined into the body tag of the output string. All strings except for the first will have their body tags converted to div tags.

The first string of the vector is considered to be the "main" html document, which the other ones are appended to.

