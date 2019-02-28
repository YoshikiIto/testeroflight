---
title: "How to access webpage via basic authentication with selenium"
date: 2019-02-28T23:19:21+09:00
draft: false
---

If you want to access a webpage via basic authentication with selenium web driver, write user id and password in the argument of a 'get' method.

```
driver.get("http://username:password@hogehoge.com");
```