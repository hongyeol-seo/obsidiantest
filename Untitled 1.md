```dataview 
table without id
	completion as 완료여부,
	title as 제목,
	"#" + join(tags, ", #") as 태그,
	file.cday as 생성일, 
	file.mday as 최종수정일,
	file.link AS Referencing,
	length(tags) as numtags
from "임시폴더"
sort completion desc
```

dataview 
TABLE without id
	completion as 완료여부,
	title as 제목,
	"#" + join(tags, ", #") as 태그,
	file.cday as 생성일, 
	file.mday as 최종수정일,
	file.link AS Referencing,
	length(tags) as numtags
from "임시폴더"
sort completion desc


```dataview
table without id
title as 제목,
created as 만든날짜,
file.link as 링크
from "임시폴더"
```