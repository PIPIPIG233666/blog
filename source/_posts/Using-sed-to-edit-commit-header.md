---
title: Using sed to edit commit header
date: 2022-01-16 13:55:57
categories:
- ['General']
tags:
- 'General'
---

Just in case I forget about this in the near future:

```git
git filter-branch -f --msg-filter 'sed "1s/^/THING/g"' HEAD^..HEAD
```

^ This adds **THING** to your commit header within the range `HEAD^ to HEAD`

Same thing can be done to the bottom line, but it's not useful for me.
