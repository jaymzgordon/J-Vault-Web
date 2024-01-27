<%*
let jFileName = await tp.system.prompt ("Note Title")
await tp.file.rename(jFileName)
await tp.file.move("content/" + jFileName);
-%>
---
title: "<% jFileName %>"
draft: false
tags:
  - 
---
