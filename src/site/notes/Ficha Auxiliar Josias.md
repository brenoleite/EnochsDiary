---
{"dg-publish":true,"permalink":"/ficha-auxiliar-josias/","dgHomeLink":true,"dgPassFrontmatter":false}
---

# Josias

## Combate
- **CA**: 19+2 (escudo)
- **Maça Estrela OP**: (20x2)
	- **Ataque:** d20+10
	- **Dano:** 1d8+3
- **Agarrar:** 09
- **BBA**: 06

### Magias Preparadas para o dia
##### Level 00
- [ ] [[DNDSRD/35eSRD/Spells/Detect Magic|Detect Magic]] [preparada::1]
	- Detects spells and magic items within 60 ft. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Detect Poison|Detect Poison]] [preparada::1]
	- Detects poison in one creature or small object. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Light|Light]] [preparada::1]
	- Object shines like a torch. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Mending|Mending]] [preparada::1]
	- Makes minor repairs on an object. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Read Magic|Read Magic]] [preparada::1]
	- Read scrolls and spellbooks. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Resistance|Resistance]] [preparada::1]
	- Subject gains +1 on saving throws. ^onelinedescription
##### Level 01
- [ ] [[DNDSRD/35eSRD/Spells/Cure Light Wounds|Cure Light Wounds]] [preparada::1]  
	- Cures 1d8 damage +1/level (max +5). ^onelinedescription
:--:
- [ ] [[DNDSRD/35eSRD/Spells/Bless Water|Bless Water]] [preparada::1]
	- Makes holy water. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Command|Command]] [preparada::1]
	- One subject obeys selected command for 1 round. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Comprehend Languages|Comprehend Languages]] [preparada::1]
	- You understand all spoken and written languages. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Endure Elements|Endure Elements]] [preparada::1]
	- Exist comfortably in hot or cold environments. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Obscuring Mist|Obscuring Mist]] [preparada::1]
	- Fog surrounds you. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Remove Fear|Remove Fear]] [preparada::1]
	- Suppresses fear or gives +4 on saves against fear for one subject + one per four levels. ^onelinedescription
##### Level 02
- [ ] [[DNDSRD/35eSRD/Spells/Cure Moderate Wounds|Cure Moderate Wounds]] [preparada::1]  
	- Cures 2d8 damage +1/level (max +10). ^onelinedescription
:--:
- [ ] [[DNDSRD/35eSRD/Spells/Augury|Augury]] [preparada::1]
	- Learns whether an action will be good or bad. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Calm Emotions|Calm Emotions]] [preparada::1]
	- Calms creatures, negating emotion effects. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Make Whole|Make Whole]] [preparada::1]
	- Repairs an object. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Remove Paralysis|Remove Paralysis]] [preparada::1]
	- Frees one or more creatures from paralysis or slow effect. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Status|Status]] [preparada::1]
	- Monitors condition, position of allies. ^onelinedescription
##### Level 03
- [ ] [[DNDSRD/35eSRD/Spells/Cure Serious Wounds|Cure Serious Wounds]] [preparada::1]  
	- Cures 3d8 damage +1/level (max +15). ^onelinedescription
:--:
- [ ] [[DNDSRD/35eSRD/Spells/Dispel Magic|Dispel Magic]] [preparada::1]
	- Cancels magical spells and effects. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Helping Hand|Helping Hand]] [preparada::1]
	- Ghostly hand leads subject to you. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Invisibility Purge|Invisibility Purge]] [preparada::1]
	- Dispels invisibility within 5 ft./level. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Locate Object|Locate Object]] [preparada::1]
	- Senses direction toward object (specific or type). ^onelinedescription
##### Level 04
- [ ] [[DNDSRD/35eSRD/Spells/Cure Critical Wounds|Cure Critical Wounds]] [preparada::1]  
	- Cures 4d8 damage +1/level (max +20). ^onelinedescription
:--:
- [ ] [[DNDSRD/35eSRD/Spells/Discern Lies|Discern Lies]] [preparada::1]
	- Reveals deliberate falsehoods. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Neutralize Poison|Neutralize Poison]] [preparada::1]
	- Immunizes subject against poison, detoxifies venom in or on subject. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Restoration|Restoration]] [preparada::1]
	- Restores level and ability score drains. ^onelinedescription
##### Level 05
- [ ] [[DNDSRD/35eSRD/Spells/Cure Light Wounds, Mass |Cure Light Wounds, Mass ]] [preparada::1]  
	- ** Cures 1d8 damage +1/level for one creature/level, no two of which can be more than 30 ft. apart. ^onelinedescription
:--:
- [ ] [[DNDSRD/35eSRD/Spells/Break Enchantment|Break Enchantment]] [preparada::1]
	- Frees subjects from enchantments, alterations, curses, and petrification. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Scrying|Scrying]] [preparada::1]
	- Spies on subject from a distance. ^onelinedescription


##### Aqui vai começar o dataview
```dataviewjs
let lista0 = [];
let ind0 = 0;
let numPrep0 = 0;
let lv0s = dv.pages('"Personagens/Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "Level 00");
//console.log(lv0s)
for ( let i=0 ; i<lv0s.length ; i++ ) {
    //console.log("entrou");
	numPrep0+=lv0s[i].preparada;
	for ( let j=0 ; j<lv0s[i].preparada ; j++ ) {
		lista0[ind0++]=lv0s[i];
	}
}
dv.header(5, "Level 0 ("+dv.current().num0levelspell+")");
if ( lista0.length > 0 ) {
	if ( numPrep0 > dv.current().num0levelspell)
		dv.span("**Há mais magias preparadas que o limite diário**");
	dv.taskList(lista0,false);
	//console.log(lista0)
} else dv.span("não há magias preparadas deste nível")

let lista1 = [];
let ind1 = 0;
let numPrep1 = 0;
let lv1s = dv.pages('"Personagens/Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "Level 01");
for ( let i=0 ; i<lv1s.length ; i++ ) {
    //console.log("entrou");
	numPrep1+=lv1s[i].preparada;
	for ( let j=0 ; j<lv1s[i].preparada ; j++ ) {
		lista1[ind1++]=lv1s[i];
	}
}
let dlv1s = dv.pages('"Personagens/Josias"').file.tasks
	.where(m => m.healing && m.healing == 1)
dv.header(5, "Level 1 (1 + "+dv.current().num1stlevelspell+")");
if ( lista1.length > 0 | dlv1s.length > 0) {
	dv.taskList(dlv1s,false);
	//console.log(dlv1s);
	dv.span("\n:--:\n");
	if ( numPrep1 > dv.current().num1stlevelspell)
		dv.span("**Há mais magias preparadas que o limite diário**");
	dv.taskList(lista1,false);
	//console.log(lista1)
} else dv.span("não há magias preparadas deste nível")

let lista2 = [];
let ind2 = 0;
let numPrep2 = 0;
let lv2s = dv.pages('"Personagens/Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "Level 02");
for ( let i=0 ; i<lv2s.length ; i++ ) {
    //console.log("entrou");
	numPrep2+=lv2s[i].preparada;
	for ( let j=0 ; j<lv2s[i].preparada ; j++ ) {
		lista2[ind2++]=lv2s[i];
	}
}
let dlv2s = dv.pages('"Personagens/Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "dlevel 2")
dv.header(5, "Level 2 (1 + "+dv.current().num2ndlevelspell+")");
if ( lista2.length > 0 | dlv2s.length > 0) {
	dv.taskList(dlv2s,false);
	//console.log(dlv1s);
	dv.span("\n:--:\n");
	if ( numPrep2 > dv.current().num2ndlevelspell)
		dv.span("**Há mais magias preparadas que o limite diário**");
	dv.taskList(lista2,false);
	//console.log(lista1)
} else dv.span("não há magias preparadas deste nível")

let lista3 = [];
let ind3 = 0;
let numPrep3 = 0;
let lv3s = dv.pages('"Personagens/Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "Level 03");
for ( let i=0 ; i<lv3s.length ; i++ ) {
    //console.log("entrou");
	numPrep3+=lv3s[i].preparada;
	for ( let j=0 ; j<lv3s[i].preparada ; j++ ) {
		lista3[ind3++]=lv3s[i];
	}
}
let dlv3s = dv.pages('"Personagens/Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "dlevel 3")
dv.header(5, "Level 3 (1 + "+dv.current().num3rdlevelspell+")");
if ( lista3.length > 0 | dlv3s.length > 0) {
	dv.taskList(dlv3s,false);
	//console.log(dlv1s);
	dv.span("\n:--:\n");
	if ( numPrep3 > dv.current().num3rdlevelspell)
		dv.span("**Há mais magias preparadas que o limite diário**");
	dv.taskList(lista3,false);
	//console.log(lista1)
} else dv.span("não há magias preparadas deste nível")

let lista4 = [];
let ind4 = 0;
let numPrep4 = 0;
let lv4s = dv.pages('"Personagens/Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "Level 04");
for ( let i=0 ; i<lv4s.length ; i++ ) {
    //console.log("entrou");
	numPrep4+=lv4s[i].preparada;
	for ( let j=0 ; j<lv4s[i].preparada ; j++ ) {
		lista4[ind4++]=lv4s[i];
	}
}
let dlv4s = dv.pages('"Personagens/Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "dlevel 4")
dv.header(5, "Level 4 (1 + "+dv.current().num4thlevelspell+")");
if ( lista4.length > 0 | dlv4s.length > 0) {
	dv.taskList(dlv4s,false);
	//console.log(dlv1s);
	dv.span("\n:--:\n");
	if ( numPrep4 > dv.current().num4thlevelspell)
		dv.span("**Há mais magias preparadas que o limite diário**");
	dv.taskList(lista4,false);
	//console.log(lista1)
} else dv.span("não há magias preparadas deste nível")

let lista5 = [];
let ind5 = 0;
let numPrep5 = 0;
let lv5s = dv.pages('"Personagens/Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "Level 05");
for ( let i=0 ; i<lv5s.length ; i++ ) {
    //console.log("entrou");
	numPrep5+=lv5s[i].preparada;
	for ( let j=0 ; j<lv5s[i].preparada ; j++ ) {
		lista5[ind5++]=lv5s[i];
	}
}
let dlv5s = dv.pages('"Personagens/Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "dlevel 5")
dv.header(5, "Level 5 (1 + "+dv.current().num5thlevelspell+")");
if ( lista5.length > 0 | dlv5s.length > 0) {
	dv.taskList(dlv5s,false);
	//console.log(dlv1s);
	dv.span("\n:--:\n");
	if ( numPrep5 > dv.current().num5thlevelspell)
		dv.span("**Há mais magias preparadas que o limite diário**");
	dv.taskList(lista5,false);
	//console.log(lista1)
} else dv.span("não há magias preparadas deste nível")

```

## **Testes**: 
- **Fortitude:** 9
- **Reflexos:** 3
- **Vontade:** 11
## Perícias mais usadas
|                    perícia | pts |
| --------------------------:|:---:|
|          **Concentração:** | +13 |
|   **Conhecimento Arcano:** | +14 |
| **Conhecimento História:** | +14 |
|  **Conhecimento Nobreza:** | +8  |
|                  **Cura:** | +13 |
|     **Identificar Magia:** | +18 |
|         **Sobrevivência:** | +7  |
 
 
---
