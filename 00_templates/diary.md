---
tags:
---
<%*
const year = tp.date.now("YYYY");
const month = tp.date.now("MM");
const day = tp.date.now("DD");
tp.file.title = `${year}-${month}-${day}`;
const fileName = tp.file.title;
await tp.file.move(`01_diary/${year}/${month}/${fileName}`);
%>