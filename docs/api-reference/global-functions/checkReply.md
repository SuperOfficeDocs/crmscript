---
title: checkReply
description: Bool checkReply(String email)
intellisense: Void.checkReply
langref: 1
keywords: checkReply(String)
so.topic: reference
---

# checkReply

This function will return true if it is ok to send a receipt to the indicated email address, false otherwise.
Every time this method is called, it records that an email has been sent to the email address. If this is done too often within a specified time interval (specified in config table), you should not send an email to the email address to prevent swamping.

