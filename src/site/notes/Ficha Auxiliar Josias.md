---
{"dg-publish":true,"permalink":"/ficha-auxiliar-josias/","dgHomeLink":true,"dgPassFrontmatter":false}
---


## cidades
- [[Mundo/Ilitia|Ilitia]]
- [[Mundo/Cidade de Nemis|Cidade de Nemis]]

## Quests
- **[[Exército de Heironeous|Exército de Heironeous]]**

## Combate
- **CA**: 19+2 (escudo)
- **Espada Larga**: (19/20x2)
	- **Ataque:** d20+18
	- **Dano:** 2d6+6
- **Espada Longa**: (17/20x2)
	- **Ataque:** d20+17
	- **Dano**: 1d8+4
- **Agarrar:** 16
- **BBA**: 12

### Combatendo montado
- *+1 no bonus de ataque* contra criaturas médias e menores (Pg. 134 PT - Pg. 157 ENG)
- *Investida* com Lança causa 2x o dano normal (Pg. 135 PT - Pg. 157 ENG)
- O personagem é capaz de realizar um ataque total enquanto sua montaria se desloca.^[No livro em inglês é especifica: Full attack with a Ranged Weapon] Da mesma forma, ele conseguiria realizar ações de movimento normalmente - sendo capaz, por exemplo, de carregar e disparar uma besta leve enquanto sua montaria avança. (Pg. 135 PT - Pg. 157 ENG)
- **Magias** montado(Pg. 135 PT - Pg. 157 ENG)
	- deslocamento normal - concentração CD 10+nível da magia
	- correndo - concentração CD 15+nível da magia
- **Quedas**. (Pg. 135 PT - Pg. 157 ENG)
	- Se o animal cair enquanto montado 
		- cavalgar CD 15 ou 1d6 de dano
	- Se o cavaleiro ficar inconsciente
		- Sela militar - 25% chance de cair - 1d6 de dano
		- sela normal - 50% chande de cair - 1d6 de dano

### Magias Preparadas para o dia

```dataviewjs
let lv1s = dv.pages('"Ficha Auxiliar Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "level 1")
	//	.limit(dv.current().num1stlevelspell)
if ( lv1s.length > 0 ) {
	dv.header(5, "Level 1")
	if ( lv1s.length > dv.current().num1stlevelspell)
		dv.span("**Há mais magias preparadas que o limite diário**")
	dv.taskList(lv1s,false)
}

let lv2s = dv.pages('"Ficha Auxiliar Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "level 2")
		//.limit(dv.current().num2ndlevelspell)
if (lv2s.length > 0 ) {
	dv.header(5, "Level 2")
	if ( lv2s.length > dv.current().num2ndlevelspell)
		dv.span("**Há mais magias preparadas que o limite diário**")
	dv.taskList(lv2s,false)
}

let lv3s = dv.pages('"Ficha Auxiliar Josias"').file.tasks
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

## **Testes**: 
- **Fortitude:** 12
- **Reflexos:** 6
- **Vontade:** 8
## Perícias mais usadas
|                    perícia | pts |
| --------------------------:|:---:|
|              **Cavalgar:** | +17  |
| **Conhecimento Religião:** | +16  |
|                  **Cura:** |  +7  |
|            **Diplomacia:** |  +8  |
|              **Observar:** |  +2  |
|                 **Ouvir:** |  +2  |
|      **Sentir Motivação:** |  +6  |
 
 
---
## Magias
#### domínios Strength & Good
##### level 1
- [ ] [[DNDSRD/35eSRD/Spells/Protection from Evil Or Chaos|Protection from Evil]] [preparada:: 0]
- [ ] [[teste/Enlarge Person|Enlarge Person]] [preparada:: 1]

##### level 2
- [ ] [[teste/Aid|Aid]] [preparada:: 1]
- [ ] [[DNDSRD/35eSRD/Spells/Bull’s Strength|Bull’s Strength]] [preparada:: 0]

##### level 3
- [ ] [[teste/Magic Circle against Evil|Magic Circle against Evil]] [preparada:: 0]
- [ ] [[teste/Magic Vestment|Magic Vestment]] [preparada:: 1]

##### level 4
- [ ] [[teste/Holy Smite|Holy Smite]] [preparada:: 1]
- [ ] [[teste/Spell Immunity|Spell Immunity]] [preparada:: 0]

##### level 5
- [ ] [[teste/Dispel Evil|Dispel Evil]] [preparada:: 0]
- [ ] [[teste/Righteous Might|Righteous Might]] [preparada:: 0]

#### level 0
- [ ] [[teste/Create Water|Create Water]] [preparada:: 0]
- [ ] [[teste/Cure Minor Wounds|Cure Minor Wounds]] [preparada:: 0]
- [ ] [[teste/Detect Magic|Detect Magic]] [preparada:: 0]
- [ ] [[teste/Detect Poison|Detect Poison]] [preparada:: 0]
- [ ] [[teste/Guidance|Guidance]] [preparada:: 0]
- [ ] [[Inflict Minor Wouds|Inflict Minor Wouds]] [preparada:: 0]
- [ ] [[teste/Light|Light]] [preparada:: 0]
- [ ] [[teste/Mending|Mending]] [preparada:: 0]
- [ ] [[teste/Purify Food and Drink|Purify Food and Drink]] [preparada:: 0]
- [ ] [[DNDSRD/35eSRD/Spells/Read Magic (F)|Read Magic (F)]] [preparada:: 0]
- [ ] [[teste/Resistance|Resistance]] [preparada:: 0]
- [ ] [[teste/Virtue|Virtue]] [preparada:: 0]

#### level 1
- [ ] [[teste/Bane|Bane]] [preparada:: 0]
- [ ] [[teste/Bless|Bless]] [preparada:: 0]
- [ ] [[DNDSRD/35eSRD/Spells/Bless Water (M)|Bless Water (M)]] [preparada:: 0]
- [ ] [[teste/Cause Fear|Cause Fear]] [preparada:: 0]
- [ ] [[teste/Command|Command]] [preparada:: 0]
- [ ] [[teste/Comprehend Languages|Comprehend Languages]] [preparada:: 0]
- [ ] [[teste/Cure Light Wounds|Cure Light Wounds]] [preparada:: 0]
- [ ] [[teste/Curse Water|Curse Water]] [preparada:: 0]
- [ ] [[teste/Deathwatch|DeathWatch]] [preparada:: 0]
- [ ] [[teste/Detect Evil|Detect Evil]] [preparada:: 0]
- [ ] [[teste/Detect Undead|Detect Undead]] [preparada:: 0]
- [ ] [[teste/Divine Favor|Divine Favor]] [preparada:: 0]
- [ ] [[teste/Doom|Doom]] [preparada:: 0]
- [ ] [[teste/Endure Elements|Endure Elements]] [preparada:: 0]
- [ ] [[teste/Entropic Shield|Entropic Shield]] [preparada:: 0]
- [ ] [[teste/Hide from Undead|Hide From Undead]] [preparada:: 0]
- [ ] [[teste/Inflict Light Wounds|Inflict Light Wounds]] [preparada:: 0]
- [ ] [[teste/Magic Stone|Magic Stone]] [preparada:: 0]
- [ ] [[teste/Magic Weapon|Magic Weapon]] [preparada:: 0]
- [ ] [[teste/Obscuring Mist|Obscuring Mist]] [preparada:: 0]
- [ ] [[DNDSRD/35eSRD/Spells/Protection from Evil Or Chaos|Protection from Evil Or Chaos]] [preparada:: 0]
- [ ] [[teste/Remove Fear|Remove Fear]] [preparada:: 0]
- [ ] [[teste/Sanctuary|Sanctuary]] [preparada:: 0]
- [ ] [[teste/Shield of Faith|Shield of Faith]] [preparada:: 0]
- [ ] [[teste/Summon Monster I|Summon Monster I]] [preparada:: 0]

#### level 2
- [ ] [[teste/Aid|Aid]] [preparada:: 0]
- [ ] [[teste/Align Weapon|Align Weapon]] [preparada:: 0]
- [ ] [[teste/Augury|Augury]] [preparada:: 0]
- [ ] [[teste/Bear's Endurance|Bear's Endurance]] [preparada:: 0]
- [ ] [[DNDSRD/35eSRD/Spells/Bull’s Strength|Bull’s Strength]] [preparada:: 0]
- [ ] [[teste/Calm Emotions|Calm Emotions]] [preparada:: 0]
- [ ] [[teste/Consecrate|Consecrate]] [preparada:: 0]
- [ ] [[teste/Cure Moderate Wounds|Cure Moderate Wounds]] [preparada:: 0]
- [ ] [[teste/Darkness|Darkness]] [preparada:: 0]
- [ ] [[teste/Death Knell|Death Knell]] [preparada:: 0]
- [ ] [[teste/Delay Poison|Delay Poison]] [preparada:: 0]
- [ ] [[teste/Desecrate|Desecrate]] [preparada:: 0]
- [ ] [[DNDSRD/35eSRD/Spells/Eagle’s Splendor|Eagle’s Splendor]] [preparada:: 0]
- [ ] [[teste/Enthrall|Enthrall]] [preparada:: 0]
- [ ] [[teste/Find Traps|Find Traps]] [preparada:: 0]
- [ ] [[teste/Gentle Repose|Gentle Repose]] [preparada:: 0]
- [ ] [[teste/Hold Person|Hold Person]] [preparada:: 0]
- [ ] [[teste/Inflict Moderate Wounds|Inflict Moderate Wounds]] [preparada:: 0]
- [ ] [[teste/Make Whole|Make Whole]] [preparada:: 0]
- [ ] [[DNDSRD/35eSRD/Spells/Owl’s Wisdom|Owl’s Wisdom]] [preparada:: 0]
- [ ] [[teste/Remove Paralysis|Remove Paralysis]] [preparada:: 0]
- [ ] [[DNDSRD/35eSRD/Spells/Resistência a elementos|Resistência a elementos]] [preparada:: 0]
- [ ] [[teste/Restoration, Lesser|Restoration, Lesser]] [preparada:: 0]
- [ ] [[teste/Shatter|Shatter]] [preparada:: 0]
- [ ] [[DNDSRD/35eSRD/Spells/Shield Other (F)|Shield Other (F)]] [preparada:: 0]
- [ ] [[teste/Silence|Silence]] [preparada:: 0]
- [ ] [[teste/Sound Burst|Sound Burst]] [preparada:: 0]
- [ ] [[teste/Spiritual Weapon|Spiritual Weapon]] [preparada:: 0]
- [ ] [[teste/Status|Status]] [preparada:: 0]
- [ ] [[teste/Summon Monster II|Summon Monster II]] [preparada:: 0]
- [ ] [[teste/Undetectable Alignment|Undetectable Alignment]] [preparada:: 0]
- [ ] [[teste/Zone of Truth|Zone of Truth]] [preparada:: 0]

#### level 3
- [ ] [[teste/Animate Dead|Animate Dead]] [preparada:: 0]
- [ ] [[teste/Bestow Curse|Bestow Curse]] [preparada:: 0]
- [ ] [[teste/Blindness_Deafness|Blindness_Deafness]] [preparada:: 0]
- [ ] [[teste/Contagion|Contagion]] [preparada:: 0]
- [ ] [[teste/Continual Flame|Continual Flame]] [preparada:: 0]
- [ ] [[teste/Create Food and Water|Create Food and Water]] [preparada:: 0]
- [ ] [[teste/Cure Serious Wounds|Cure Serious Wounds]] [preparada:: 0]
- [ ] [[teste/Daylight|Daylight]] [preparada:: 0]
- [ ] [[teste/Deeper Darkness|Deeper Darkness]] [preparada:: 0]
- [ ] [[teste/Dispel Magic|Dispel Magic]] [preparada:: 0]
- [ ] [[teste/Glyph of Warding|Glyph of Warding]] [preparada:: 0]
- [ ] [[teste/Helping Hand|Helping Hand]] [preparada:: 0]
- [ ] [[teste/Inflict Serious Wounds|Inflict Serious Wounds]] [preparada:: 0]
- [ ] [[teste/Invisibility Purge|Invisibility Purge]] [preparada:: 0]
- [ ] [[teste/Locate Object|Locate Object]] [preparada:: 0]
- [ ] [[teste/Magic Circle against Evil|Magic Circle against Evil]] [preparada:: 0]
- [ ] [[teste/Magic Circle against Chaos|Magic Circle against Chaos]] [preparada:: 0]
- [ ] [[teste/Magic Vestment|Magic Vestment]] [preparada:: 0]
- [ ] [[teste/Meld into Stone|Meld into Stone]] [preparada:: 0]
- [ ] [[teste/Obscure Object|Obscure Object]] [preparada:: 0]
- [ ] [[teste/Prayer|Prayer]] [preparada:: 0]
- [ ] [[teste/Protection from Energy|Protection from Energy]] [preparada:: 0]
- [ ] [[DNDSRD/35eSRD/Spells/Remove Blindness or Deafness|Remove Blindness or Deafness]] [preparada:: 0]
- [ ] [[teste/Remove Curse|Remove Curse]] [preparada:: 0]
- [ ] [[teste/Remove Disease|Remove Disease]] [preparada:: 0]
- [ ] [[teste/Searing Light|Searing Light]] [preparada:: 0]
- [ ] [[teste/Speak with Dead|Speak with Dead]] [preparada:: 0]
- [ ] [[teste/Stone Shape|Stone Shape]] [preparada:: 0]
- [ ] [[teste/Summon Monster III|Summon Monster III]] [preparada:: 0]
- [ ] [[teste/Water Breathing|Water Breathing]] [preparada:: 0]
- [ ] [[teste/Water Walk|Water Walk]] [preparada:: 0]
- [ ] [[teste/Wind Wall|Wind Wall]] [preparada:: 0]

#### level 4
- [ ] [[teste/Air Walk|Air Walk]] [preparada:: 0]
- [ ] [[teste/Control Water|Control Water]] [preparada:: 0]
- [ ] [[teste/Cure Critical Wounds|Cure Critical Wounds]] [preparada:: 0]
- [ ] [[teste/Death Ward|Death Ward]] [preparada:: 0]
- [ ] [[teste/Dimensional Anchor|Dimensional Anchor]] [preparada:: 0]
- [ ] [[teste/Discern Lies|Discern Lies]] [preparada:: 0]
- [ ] [[teste/Dismissal|Dismissal]] [preparada:: 0]
- [ ] [[teste/Divination|Divination]] [preparada:: 0]
- [ ] [[teste/Divine Power|Divine Power]] [preparada:: 0]
- [ ] [[teste/Freedom of Movement|Freedom of Movement]] [preparada:: 0]
- [ ] [[teste/Giant Vermin|Giant Vermin]] [preparada:: 0]
- [ ] [[teste/Imbue with Spell Ability|Imbue with Spell Ability]] [preparada:: 0]
- [ ] [[teste/Inflict Critical Wounds|Inflict Critical Wounds]] [preparada:: 0]
- [ ] [[teste/Magic Weapon, Greater|Magic Weapon, Greater]] [preparada:: 0]
- [ ] [[teste/Neutralize Poison|Neutralize Poison]] [preparada:: 0]
- [ ] [[teste/Planar Ally, Lesser|Planar Ally, Lesser]] [preparada:: 0]
- [ ] [[teste/Poison|Poison]] [preparada:: 0]
- [ ] [[teste/Repel Vermin|Repel Vermin]] [preparada:: 0]
- [ ] [[teste/Restoration|Restoration]] [preparada:: 0]
- [ ] [[teste/Sending|Sending]] [preparada:: 0]
- [ ] [[teste/Spell Immunity|Spell Immunity]] [preparada:: 0]
- [ ] [[teste/Summon Monster IV|Summon Monster IV]] [preparada:: 0]
- [ ] [[teste/Tongues|Tongues]] [preparada:: 0]

#### level 5
- [ ] [[teste/Atonement|Atonement]] [preparada:: 0]
- [ ] [[teste/Break Enchantment|Break Enchantment]] [preparada:: 0]
- [ ] [[teste/Command, Greater|Command, Greater]] [preparada:: 0]
- [ ] [[teste/Commune|Commune]] [preparada:: 0]
- [ ] [[teste/Cure Light Wounds, Mass|Cure Light Wounds, Mass]] [preparada:: 0]
- [ ] [[teste/Dispel Chaos|Dispel Chaos]] [preparada:: 0]
- [ ] [[teste/Dispel Evil|Dispel Evil]] [preparada:: 0]
- [ ] [[teste/Disrupting Weapon|Disrupting Weapon]] [preparada:: 0]
- [ ] [[teste/Flame Strike|Flame Strike]] [preparada:: 0]
- [ ] [[teste/Hallow|Hallow]] [preparada:: 0]
- [ ] [[teste/Inflict Light Wounds, Mass|Inflict Light Wounds, Mass]] [preparada:: 0]
- [ ] [[teste/Insect Plague|Insect Plague]] [preparada:: 0]
- [ ] [[teste/Mark of Justice|Mark of Justice]] [preparada:: 0]
- [ ] [[teste/Plane Shift|Plane Shift]] [preparada:: 0]
- [ ] [[teste/Raise Dead|Raise Dead]] [preparada:: 0]
- [ ] [[teste/Righteous Might|Righteous Might]] [preparada:: 0]
- [ ] [[teste/Scrying|Scrying]] [preparada:: 0]
- [ ] [[teste/Slay Living|Slay Living]] [preparada:: 0]
- [ ] [[teste/Spell Resistance|Spell Resistance]] [preparada:: 0]
- [ ] [[teste/Summon Monster V|Summon Monster V]] [preparada:: 0]
- [ ] [[teste/Symbol of Pain|Symbol of Pain]] [preparada:: 0]
- [ ] [[teste/Symbol of Sleep|Symbol of Sleep]] [preparada:: 0]
- [ ] [[teste/True Seeing|True Seeing]] [preparada:: 0]
- [ ] [[teste/Unhallow|Unhallow]] [preparada:: 0]
- [ ] [[teste/Wall of Stone|Wall of Stone]] [preparada:: 0]
