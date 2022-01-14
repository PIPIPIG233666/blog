---
title: QTI Bluetooth Stack on Android 12
date: 2022-01-16 12:07:11
categories:
- ['General']
tags:
- 'General'
- 'Android'
---

[topic:twelve-qti-bt-stack · Gerrit Code Review (lineageos.org)](https://review.lineageos.org/q/topic:twelve-qti-bt-stack)

It took me a while to port it to Lineage, after hours of cherry-picking, it was finally done last night.

Funny thing about this is that CAF guys actually added proprietary features, aka bt adv audio to the open source code.

Well, I can understand that it is conditional, but some of the includes aren’t handled the same way which literally breaks the build right away.

As for bluetooth, QSSI is great: the Android 11 vendor stack works just fine, with no missing symbols or whatever.

Bluetooth is probably one of the **only** few things that one can utilize from QSSI.

I’ll get into WiFi display today while at it.
