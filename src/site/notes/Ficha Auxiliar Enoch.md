```dataviewjs
let lv1s = dv.pages('"Ficha Auxiliar Enoch"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "level 1")
	//	.limit(dv.current().num1stlevelspell)
if ( lv1s.length > 0 ) {
	dv.header(5, "Level 1")
	if ( lv1s.length > dv.current().num1stlevelspell)
		dv.span("**Há mais magias preparadas que o limite diário**")
	dv.taskList(lv1s,false)
}

let lv2s = dv.pages('"Ficha Auxiliar Enoch"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "level 2")
		//.limit(dv.current().num2ndlevelspell)
if (lv2s.length > 0 ) {
	dv.header(5, "Level 2")
	if ( lv2s.length > dv.current().num2ndlevelspell)
		dv.span("**Há mais magias preparadas que o limite diário**")
	dv.taskList(lv2s,false)
}

let lv3s = dv.pages('"Ficha Auxiliar Enoch"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 && 
	m.header.subpath == "level 3")
		//.limit(dv.current().num3rdlevelspell)
if (lv3s.length > 0) {
	dv.header(5, "Level 3")
	if ( lv3s.length > dv.current().num3rdlevelspell)
		dv.span("**Há mais magias preparadas que o limite diário**")
	dv.taskList(lv3s,false)
}
```