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
```dataviewjs
let lista0 = [];
let ind0 = 0;
let numPrep0 = 0;
let lv0s = dv.pages('"Ficha Auxiliar Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "level 0");
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
let lv1s = dv.pages('"Ficha Auxiliar Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "level 1");
for ( let i=0 ; i<lv1s.length ; i++ ) {
    //console.log("entrou");
	numPrep1+=lv1s[i].preparada;
	for ( let j=0 ; j<lv1s[i].preparada ; j++ ) {
		lista1[ind1++]=lv1s[i];
	}
}
let dlv1s = dv.pages('"Ficha Auxiliar Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "dlevel 1")
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
let lv2s = dv.pages('"Ficha Auxiliar Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "level 2");
for ( let i=0 ; i<lv2s.length ; i++ ) {
    //console.log("entrou");
	numPrep2+=lv2s[i].preparada;
	for ( let j=0 ; j<lv2s[i].preparada ; j++ ) {
		lista2[ind2++]=lv2s[i];
	}
}
let dlv2s = dv.pages('"Ficha Auxiliar Josias"').file.tasks
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
let lv3s = dv.pages('"Ficha Auxiliar Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "level 3");
for ( let i=0 ; i<lv3s.length ; i++ ) {
    //console.log("entrou");
	numPrep3+=lv3s[i].preparada;
	for ( let j=0 ; j<lv3s[i].preparada ; j++ ) {
		lista3[ind3++]=lv3s[i];
	}
}
let dlv3s = dv.pages('"Ficha Auxiliar Josias"').file.tasks
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
let lv4s = dv.pages('"Ficha Auxiliar Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "level 4");
for ( let i=0 ; i<lv4s.length ; i++ ) {
    //console.log("entrou");
	numPrep4+=lv4s[i].preparada;
	for ( let j=0 ; j<lv4s[i].preparada ; j++ ) {
		lista4[ind4++]=lv4s[i];
	}
}
let dlv4s = dv.pages('"Ficha Auxiliar Josias"').file.tasks
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
let lv5s = dv.pages('"Ficha Auxiliar Josias"').file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "level 5");
for ( let i=0 ; i<lv5s.length ; i++ ) {
    //console.log("entrou");
	numPrep5+=lv5s[i].preparada;
	for ( let j=0 ; j<lv5s[i].preparada ; j++ ) {
		lista5[ind5++]=lv5s[i];
	}
}
let dlv5s = dv.pages('"Ficha Auxiliar Josias"').file.tasks
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
## Magias

#### domínios Strength & Good
##### dlevel 1
- [ ] [[DNDSRD/35eSRD/Spells/Protection from Evil|Protection from Evil]]  
	- +2 to AC and saves, counter mind control, hedge out elementals and outsiders.
- [ ] [[DNDSRD/35eSRD/Spells/Cure Light Wounds|Cure Light Wounds]]  
	- Cures 1d8 damage +1/level (max +5).

##### dlevel 2
- [ ] [[DNDSRD/35eSRD/Spells/Aid|Aid]] 
	- +1 on attack rolls and saves against fear, 1d8 temporary hp +1/level (max +10).
- [ ] [[DNDSRD/35eSRD/Spells/Cure Moderate Wounds|Cure Moderate Wounds]] [preparada:: 1] 
	- Cures 2d8 damage +1/level (max +10).

##### dlevel 3
- [ ] [[DNDSRD/35eSRD/Spells/Magic Circle against Evil|Magic Circle against Evil]] [preparada:: 0]
	- As protection from evil, but 10-ft. radius and 10 min./level.
- [ ] [[DNDSRD/35eSRD/Spells/Cure Serious Wounds|Cure Serious Wounds]] [preparada:: 1] 
	- Cures 3d8 damage +1/level (max +15).

##### dlevel 4
- [ ] [[DNDSRD/35eSRD/Spells/Holy Smite|Holy Smite]] [preparada:: 0]
	- 1d8 points of damage per two caster levels (maximum 5d8) to each evil creature in the area (or 1d6 points of damage per caster level, maximum 10d6, to an evil outsider) and causes it to become blinded for 1 round
- [ ] [[DNDSRD/35eSRD/Spells/Cure Critical Wounds|Cure Critical Wounds]] [preparada:: 1]
	- Cures 4d8 damage +1/level (max +20).

##### dlevel 5
- [ ] [[DNDSRD/35eSRD/Spells/Dispel Evil|Dispel Evil]] [preparada:: 0] 
	- +4 bonus against attacks by evil creatures.
- [ ] [[DNDSRD/35eSRD/Spells/Cure Light Wounds, Mass |Cure Light Wounds, Mass ]] [preparada:: 1] 
	- Cures 1d8 damage +1/level (max 25) for one creature/level, no two of which can be more than 30 ft. apart.

#### level 0
 max permitido: `= this.num0levelspell`
- [ ] [[DNDSRD/35eSRD/Spells/Create Water|Create Water]] [preparada:: 0] 
	- Up to 2 gallons of water/level
- [ ] [[DNDSRD/35eSRD/Spells/Cure Minor Wounds|Cure Minor Wounds]] [preparada:: 0]
	- Cures 1 point of damage.
- [ ] [[DNDSRD/35eSRD/Spells/Detect Magic|Detect Magic]] [preparada:: 1]
	- Detects spells and magic items within 60 ft.
- [ ] [[DNDSRD/35eSRD/Spells/Detect Poison|Detect Poison]] [preparada:: 1]
	- Detects poison in one creature or small object.
- [ ] [[DNDSRD/35eSRD/Spells/Guidance|Guidance]] [preparada:: 0]
	- +1 on one attack roll, saving throw, or skill check.
- [ ] [[DNDSRD/35eSRD/Spells/Inflict Minor Wounds|Inflict Minor Wounds]] [preparada:: 0]
	- Touch attack, 1 point of damage.
- [ ] [[DNDSRD/35eSRD/Spells/Light|Light]] [preparada:: 1]
	- Object shines like a torch.
- [ ] [[DNDSRD/35eSRD/Spells/Mending|Mending]] [preparada:: 1]
	- Makes minor repairs on an object.
- [ ] [[DNDSRD/35eSRD/Spells/Purify Food and Drink|Purify Food and Drink]] [preparada:: 0]
	- Purifies 1 cu. ft./level of food or water.
- [ ] [[DNDSRD/35eSRD/Spells/Read Magic|Read Magic]] [preparada:: 1]
	- Read scrolls and spellbooks.
- [ ] [[DNDSRD/35eSRD/Spells/Resistance|Resistance]] [preparada:: 1]
	- Subject gains +1 on saving throws.
- [ ] [[DNDSRD/35eSRD/Spells/Virtue|Virtue]] [preparada:: 0]
	- Subject gains 1 temporary hp.

#### level 1
max permitido  (`= this.num1stlevelspell`)
- [ ] [[DNDSRD/35eSRD/Spells/Bane|Bane]] [preparada:: 0]
	- Enemies take -1 on attack rolls and saves against fear.
- [ ] [[DNDSRD/35eSRD/Spells/Bless|Bless]] [preparada:: 0]
	- Allies gain +1 on attack rolls and +1 on saves against fear.
- [ ] [[DNDSRD/35eSRD/Spells/Bless Water|Bless Water]] [preparada:: 1]
	- Makes holy water.
- [ ] [[DNDSRD/35eSRD/Spells/Cause Fear|Cause Fear]] [preparada:: 0]
	- One creature of 5 HD or less flees for 1d4 rounds.
- [ ] [[DNDSRD/35eSRD/Spells/Command|Command]] [preparada:: 1]
	- One subject obeys selected command for 1 round.
- [ ] [[DNDSRD/35eSRD/Spells/Comprehend Languages|Comprehend Languages]] [preparada:: 1]
	- You understand all spoken and written languages.
- [ ] [[DNDSRD/35eSRD/Spells/Cure Light Wounds|Cure Light Wounds]] [preparada:: 0]
	- Cures 1d8 damage +1/level (max +5).
- [x] [[DNDSRD/35eSRD/Spells/Curse Water|Curse Water]] [preparada:: 0]
	- Makes unholy water.
- [x] [[DNDSRD/35eSRD/Spells/Deathwatch|Deathwatch]] [preparada:: 0]
	- Reveals how near death subjects within 30 ft. are.
- [ ] [[DNDSRD/35eSRD/Spells/Detect Evil|Detect Evil]] [preparada:: 0]
	- Reveals creatures, spells, or objects of selected alignment.
- [ ] [[DNDSRD/35eSRD/Spells/Detect Undead|Detect Undead]] [preparada:: 0]
	- Reveals undead within 60 ft.
- [ ] [[DNDSRD/35eSRD/Spells/Divine Favor|Divine Favor]] [preparada:: 0]
	- You gain +1 per three levels on attack and damage rolls.
- [ ] [[DNDSRD/35eSRD/Spells/Doom|Doom]] [preparada:: 0]
	- One subject takes -2 on attack rolls, saves, and checks.
- [ ] [[DNDSRD/35eSRD/Spells/Endure Elements|Endure Elements]] [preparada:: 1]
	- Exist comfortably in hot or cold environments.
- [ ] [[DNDSRD/35eSRD/Spells/Entropic Shield|Entropic Shield]] [preparada:: 0]
	- Ranged attacks against you have 20% miss chance.
- [ ] [[DNDSRD/35eSRD/Spells/Hide from Undead|Hide from Undead]] [preparada:: 0]
	- Undead can’t perceive one subject/level.
- [ ] [[DNDSRD/35eSRD/Spells/Inflict Light Wounds|Inflict Light Wounds]] [preparada:: 0]
	- Touch deals 1d8 damage +1/level (max +5).
- [ ] [[DNDSRD/35eSRD/Spells/Magic Stone|Magic Stone]] [preparada:: 0]
	- Three stones gain +1 on attack rolls, deal 1d6+1 damage.
- [ ] [[DNDSRD/35eSRD/Spells/Magic Weapon|Magic Weapon]] [preparada:: 0]
	- Weapon gains +1 bonus.
- [ ] [[DNDSRD/35eSRD/Spells/Obscuring Mist|Obscuring Mist]] [preparada:: 1]
	- Fog surrounds you.
- [ ] [[DNDSRD/35eSRD/Spells/Protection from Evil m|Protection from Evil m]] [preparada:: 0]
	- +2 to AC and saves, counter mind control, hedge out elementals and outsiders. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Protection from Chaos|Protection from Chaos]] [preparada:: 0]
	- +2 to AC and saves, counter mind control, hedge out elementals and outsiders. ^onelinedescription
- [ ] [[DNDSRD/35eSRD/Spells/Remove Fear|Remove Fear]] [preparada:: 1]
	- Suppresses fear or gives +4 on saves against fear for one subject + one per four levels.
- [ ] [[DNDSRD/35eSRD/Spells/Sanctuary|Sanctuary]] [preparada:: 0]
	- Opponents can’t attack you, and you can’t attack.
- [ ] [[DNDSRD/35eSRD/Spells/Shield of Faith|Shield of Faith]] [preparada:: 0]
	- Aura grants +2 or higher deflection bonus.
- [ ] [[DNDSRD/35eSRD/Spells/Summon Monster I|Summon Monster I]] [preparada:: 0]
	- Calls extraplanar creature to fight for you.

#### level 2
max permitido  (`= this.num2ndlevelspell`)
- [ ] [[DNDSRD/35eSRD/Spells/Aid|Aid]] [preparada:: 0]
	- +1 on attack rolls and saves against fear, 1d8 temporary hp +1/level (max +10).
- [ ] [[DNDSRD/35eSRD/Spells/Align Weapon|Align Weapon]] [preparada:: 0]
	- Weapon becomes good, evil, lawful, or chaotic.
- [ ] [[DNDSRD/35eSRD/Spells/Augury|Augury]] [preparada:: 1]
	- Learns whether an action will be good or bad.
- [ ] [[DNDSRD/35eSRD/Spells/Bear's Endurance|Bear's Endurance]] [preparada:: 0]
	- Subject gains +4 to Con for 1 min./level.
- [ ] [[DNDSRD/35eSRD/Spells/Bull's Strength|Bull's Strength]] [preparada:: 0]
	- Subject gains +4 to Str for 1 min./level.
- [ ] [[DNDSRD/35eSRD/Spells/Calm Emotions|Calm Emotions]] [preparada:: 1]
	- Calms creatures, negating emotion effects.
- [ ] [[DNDSRD/35eSRD/Spells/Consecrate|Consecrate]] [preparada:: 0]
	- Fills area with positive energy, making undead weaker.
- [ ] [[DNDSRD/35eSRD/Spells/Cure Moderate Wounds|Cure Moderate Wounds]] [preparada:: 0]
	- Cures 2d8 damage +1/level (max +10).
- [ ] [[DNDSRD/35eSRD/Spells/Darkness|Darkness]] [preparada:: 0]
	- 20-ft. radius of supernatural shadow.
- [x] [[DNDSRD/35eSRD/Spells/Death Knell|Death Knell]] [preparada:: 0]
	- Kills dying creature; you gain 1d8 temporary hp, +2 to Str, and +1 level.
- [ ] [[DNDSRD/35eSRD/Spells/Delay Poison|Delay Poison]] [preparada:: 0]
	- Stops poison from harming subject for 1 hour/ level.
- [x] [[DNDSRD/35eSRD/Spells/Desecrate|Desecrate]] [preparada:: 0]
	- Fills area with negative energy, making undead stronger.
- [ ] [[DNDSRD/35eSRD/Spells/Eagle's Splendor|Eagle's Splendor]] [preparada:: 0]
	- Subject gains +4 to Cha for 1 min./level.
- [ ] [[DNDSRD/35eSRD/Spells/Enthrall|Enthrall]] [preparada:: 0]
	- Captivates all within 100 ft. + 10 ft./level.
- [ ] [[DNDSRD/35eSRD/Spells/Find Traps|Find Traps]] [preparada:: 0]
	- Notice traps as a rogue does.
- [ ] [[DNDSRD/35eSRD/Spells/Gentle Repose|Gentle Repose]] [preparada:: 0]
	- Preserves one corpse.
- [ ] [[DNDSRD/35eSRD/Spells/Hold Person|Hold Person]] [preparada:: 0]
	- Paralyzes one humanoid for 1 round/level.
- [ ] [[DNDSRD/35eSRD/Spells/Inflict Moderate Wounds|Inflict Moderate Wounds]] [preparada:: 0]
	- Touch attack, 2d8 damage +1/level (max +10).
- [ ] [[DNDSRD/35eSRD/Spells/Make Whole|Make Whole]] [preparada:: 1]
	- Repairs an object.
- [ ] [[DNDSRD/35eSRD/Spells/Owl's Wisdom|Owl's Wisdom]] [preparada:: 0]
	- Subject gains +4 to Wis for 1 min./level.
- [ ] [[DNDSRD/35eSRD/Spells/Remove Paralysis|Remove Paralysis]] [preparada:: 1]
	- Frees one or more creatures from paralysis or slow effect.
- [ ] [[Resist Energy|Resist Energy]] [preparada:: 0]
	- Ignores first 10 (or more) points of damage/attack from specified energy type.
- [ ] [[DNDSRD/35eSRD/Spells/Restoration, Lesser|Restoration, Lesser]] [preparada:: 0]
	- Dispels magical ability penalty or repairs 1d4 ability damage.
- [ ] [[DNDSRD/35eSRD/Spells/Shatter|Shatter]] [preparada:: 0]
	- Sonic vibration damages objects or crystalline creatures.
- [ ] [[DNDSRD/35eSRD/Spells/Shield Other|Shield Other]] [preparada:: 0]
	- You take half of subject’s damage.
- [ ] [[DNDSRD/35eSRD/Spells/Silence|Silence]] [preparada:: 0]
	- Negates sound in 20-ft. radius.
- [ ] [[DNDSRD/35eSRD/Spells/Sound Burst|Sound Burst]] [preparada:: 0]
	- Deals 1d8 sonic damage to subjects; may stun them.
- [ ] [[DNDSRD/35eSRD/Spells/Spiritual Weapon|Spiritual Weapon]] [preparada:: 0]
	- Magic weapon attacks on its own.
- [ ] [[DNDSRD/35eSRD/Spells/Status|Status]] [preparada:: 1]
	- Monitors condition, position of allies.
- [ ] [[DNDSRD/35eSRD/Spells/Summon Monster II|Summon Monster II]] [preparada:: 0]
	- Calls extraplanar creature to fight for you.
- [ ] [[DNDSRD/35eSRD/Spells/Undetectable Alignment|Undetectable Alignment]] [preparada:: 0]
	- Conceals alignment for 24 hours.
- [ ] [[DNDSRD/35eSRD/Spells/Zone of Truth|Zone of Truth]] [preparada:: 0]
	- Subjects within range cannot lie.

#### level 3
max permitido  (`= this.num3rdlevelspell`)
- [x] [[DNDSRD/35eSRD/Spells/Animate Dead|Animate Dead]] [preparada:: 0]
	- Creates undead skeletons and zombies.
- [ ] [[DNDSRD/35eSRD/Spells/Bestow Curse|Bestow Curse]] [preparada:: 0]
	- 6 to an ability score; -4 on attack rolls, saves, and checks; or 50% chance of losing each action.
- [ ] [[DNDSRD/35eSRD/Spells/Blindness_Deafness m|Blindness_Deafness m]] [preparada:: 0]
	- Makes subject blind or deaf.
- [ ] [[DNDSRD/35eSRD/Spells/Contagion|Contagion]] [preparada:: 0]
	-  Infects subject with chosen disease.
- [ ] [[DNDSRD/35eSRD/Spells/Continual Flame|Continual Flame]] [preparada:: 0]
	- Makes a permanent, heatless torch.
- [ ] [[DNDSRD/35eSRD/Spells/Create Food and Water|Create Food and Water]] [preparada:: 0]
	- Feeds three humans (or one horse)/level.
- [ ] [[DNDSRD/35eSRD/Spells/Cure Serious Wounds|Cure Serious Wounds]] [preparada:: 0]
	- Cures 3d8 damage +1/level (max +15).
- [ ] [[DNDSRD/35eSRD/Spells/Daylight|Daylight]] [preparada:: 0]
	- 60-ft. radius of bright light.
- [ ] [[DNDSRD/35eSRD/Spells/Deeper Darkness|Deeper Darkness]] [preparada:: 0]
	- Object sheds supernatural shadow in 60-ft. radius.
- [ ] [[DNDSRD/35eSRD/Spells/Dispel Magic|Dispel Magic]] [preparada:: 1]
	- Cancels magical spells and effects.
- [ ] [[DNDSRD/35eSRD/Spells/Glyph of Warding|Glyph of Warding]] [preparada:: 0]
	- Inscription harms those who pass it.
- [ ] [[DNDSRD/35eSRD/Spells/Helping Hand|Helping Hand]] [preparada:: 1]
	- Ghostly hand leads subject to you.
- [ ] [[DNDSRD/35eSRD/Spells/Inflict Serious Wounds|Inflict Serious Wounds]] [preparada:: 0]
	- Touch attack, 3d8 damage +1/level (max +15).
- [ ] [[DNDSRD/35eSRD/Spells/Invisibility Purge|Invisibility Purge]] [preparada:: 1]
	- Dispels invisibility within 5 ft./level.
- [ ] [[DNDSRD/35eSRD/Spells/Locate Object|Locate Object]] [preparada:: 1]
	- Senses direction toward object (specific or type).
- [ ] [[DNDSRD/35eSRD/Spells/Magic Circle against Evil|Magic Circle against Evil]] [preparada:: 0]
	- As protection from evil, but 10-ft. radius and 10 min./level.
- [ ] [[DNDSRD/35eSRD/Spells/Magic Circle against Chaos|Magic Circle against Chaos]] [preparada:: 0]
	- As protection from chaos, but 10-ft. radius and 10 min./level.
- [ ] [[DNDSRD/35eSRD/Spells/Magic Vestment|Magic Vestment]] [preparada:: 0]
	- Armor or shield gains +1 enhancement per four levels.
- [ ] [[DNDSRD/35eSRD/Spells/Meld into Stone|Meld into Stone]] [preparada:: 0]
	- You and your gear merge with stone.
- [ ] [[DNDSRD/35eSRD/Spells/Obscure Object|Obscure Object]] [preparada:: 0]
	-  Masks object against scrying.
- [ ] [[DNDSRD/35eSRD/Spells/Prayer|Prayer]] [preparada:: 0]
	- Allies +1 bonus on most rolls, enemies -1 penalty.
- [ ] [[DNDSRD/35eSRD/Spells/Protection from Energy|Protection from Energy]] [preparada:: 0]
	- Absorb 12 points/level of damage from one kind of energy
- [ ] [[DNDSRD/35eSRD/Spells/Remove Blindness_Deafness m|Remove Blindness_Deafness m]] [preparada:: 0]
	- Cures normal or magical conditions.
- [ ] [[DNDSRD/35eSRD/Spells/Remove Curse|Remove Curse]] [preparada:: 0]
	- Frees object or person from curse.
- [ ] [[DNDSRD/35eSRD/Spells/Remove Disease|Remove Disease]] [preparada:: 0]
	- Cures all diseases affecting subject.
- [ ] [[DNDSRD/35eSRD/Spells/Searing Light|Searing Light]] [preparada:: 0]
	- Ray deals 1d8/two levels damage, more against undead.
- [ ] [[DNDSRD/35eSRD/Spells/Speak with Dead|Speak with Dead]] [preparada:: 0]
	- Corpse answers one question/two levels.
- [ ] [[DNDSRD/35eSRD/Spells/Stone Shape|Stone Shape]] [preparada:: 0]
	- Sculpts stone into any shape.
- [ ] [[DNDSRD/35eSRD/Spells/Summon Monster III|Summon Monster III]] [preparada:: 0]
	- Calls extraplanar creature to fight for you.
- [ ] [[DNDSRD/35eSRD/Spells/Water Breathing|Water Breathing]] [preparada:: 0]
	- Subjects can breathe underwater.
- [ ] [[DNDSRD/35eSRD/Spells/Water Walk|Water Walk]] [preparada:: 0]
	- Subject treads on water as if solid.
- [ ] [[DNDSRD/35eSRD/Spells/Wind Wall|Wind Wall]] [preparada:: 0]
	- Deflects arrows, smaller creatures, and gases.

#### level 4
max permitido  (`= this.num4thlevelspell`)
- [ ] [[DNDSRD/35eSRD/Spells/Air Walk|Air Walk]] [preparada:: 0]
	- Subject treads on air as if solid (climb at 45-degree angle).
- [ ] [[DNDSRD/35eSRD/Spells/Control Water|Control Water]] [preparada:: 0]
	- Raises or lowers bodies of water.
- [ ] [[DNDSRD/35eSRD/Spells/Cure Critical Wounds|Cure Critical Wounds]] [preparada:: 0]
	- Cures 4d8 damage +1/level (max +20).
- [ ] [[DNDSRD/35eSRD/Spells/Death Ward|Death Ward]] [preparada:: 0]
	- Grants immunity to death spells and negative energy effects.
- [ ] [[DNDSRD/35eSRD/Spells/Dimensional Anchor|Dimensional Anchor]] [preparada:: 0]
	- Bars extradimensional movement.
- [x] [[DNDSRD/35eSRD/Spells/Discern Lies|Discern Lies]] [preparada:: 1]
	- Reveals deliberate falsehoods.
- [ ] [[DNDSRD/35eSRD/Spells/Dismissal|Dismissal]] [preparada:: 0]
	- Forces a creature to return to native plane.
- [ ] [[DNDSRD/35eSRD/Spells/Divination|Divination]] [preparada:: 0]
	- Provides useful advice for specific proposed actions.
- [ ] [[DNDSRD/35eSRD/Spells/Divine Power|Divine Power]] [preparada:: 0]
	- You gain attack bonus, +6 to Str, and 1 hp/level.
- [ ] [[DNDSRD/35eSRD/Spells/Freedom of Movement|Freedom of Movement]] [preparada:: 0]
	- Subject moves normally despite impediments.
- [ ] [[DNDSRD/35eSRD/Spells/Giant Vermin|Giant Vermin]] [preparada:: 0]
	- Turns centipedes, scorpions, or spiders into giant vermin.
- [ ] [[DNDSRD/35eSRD/Spells/Imbue with Spell Ability|Imbue with Spell Ability]] [preparada:: 0]
	- Transfer spells to subject.
- [ ] [[DNDSRD/35eSRD/Spells/Inflict Critical Wounds|Inflict Critical Wounds]] [preparada:: 0]
	- Touch attack, 4d8 damage +1/level (max +20).
- [ ] [[DNDSRD/35eSRD/Spells/Magic Weapon, Greater|Magic Weapon, Greater]] [preparada:: 0]
	- +1/four levels (max +5).
- [ ] [[DNDSRD/35eSRD/Spells/Neutralize Poison|Neutralize Poison]] [preparada:: 1]
	- Immunizes subject against poison, detoxifies venom in or on subject.
- [ ] [[DNDSRD/35eSRD/Spells/Planar Ally, Lesser XP|Planar Ally, Lesser XP]] [preparada:: 0]
	- Exchange services with a 6 HD extraplanar creature.
- [ ] [[DNDSRD/35eSRD/Spells/Poison|Poison]] [preparada:: 0]
	- Touch deals 1d10 Con damage, repeats in 1 min.
- [ ] [[DNDSRD/35eSRD/Spells/Repel Vermin|Repel Vermin]] [preparada:: 0]
	- Insects, spiders, and other vermin stay 10 ft. away.
- [ ] [[DNDSRD/35eSRD/Spells/Restoration|Restoration]] [preparada:: 1]
	- Restores level and ability score drains.
- [ ] [[DNDSRD/35eSRD/Spells/Sending|Sending]] [preparada:: 0]
	- Delivers short message anywhere, instantly.
- [ ] [[DNDSRD/35eSRD/Spells/Spell Immunity|Spell Immunity]] [preparada:: 0]
	- Subject is immune to one spell per four levels.
- [ ] [[DNDSRD/35eSRD/Spells/Summon Monster IV|Summon Monster IV]] [preparada:: 0]
	- Calls extraplanar creature to fight for you.
- [ ] [[DNDSRD/35eSRD/Spells/Tongues|Tongues]] [preparada:: 0]
	- Speak any language.

#### level 5
max permitido  (`= this.num5thlevelspell`)
- [ ] [[DNDSRD/35eSRD/Spells/Atonement XP|Atonement XP]] [preparada:: 0]
	- Removes burden of misdeeds from subject.
- [ ] [[DNDSRD/35eSRD/Spells/Break Enchantment|Break Enchantment]] [preparada:: 1]
	-  Frees subjects from enchantments, alterations, curses, and petrification.
- [ ] [[DNDSRD/35eSRD/Spells/Command, Greater|Command, Greater]] [preparada:: 0]
	- As command, but affects one subject/level.
- [ ] [[DNDSRD/35eSRD/Spells/Commune XP|Commune XP]] [preparada:: 0]
	- Deity answers one yes-or-no question/level.
- [ ] [[DNDSRD/35eSRD/Spells/Cure Light Wounds, Mass |Cure Light Wounds, Mass ]] [preparada:: 0]
	- Cures 1d8 damage +1/level for one creature/level, no two of which can be more than 30 ft. apart.
- [ ] [[DNDSRD/35eSRD/Spells/Dispel Chaos|Dispel Chaos]] [preparada:: 0]
	- +4 bonus against attacks by chaotic creatures.
- [ ] [[DNDSRD/35eSRD/Spells/Dispel Evil|Dispel Evil]] [preparada:: 0]
	- +4 bonus against attacks by evil creatures.
- [ ] [[DNDSRD/35eSRD/Spells/Disrupting Weapon|Disrupting Weapon]] [preparada:: 0]
	- Melee weapon destroys undead.
- [ ] [[DNDSRD/35eSRD/Spells/Flame Strike|Flame Strike]] [preparada:: 0]
	- Smite foes with divine fire (1d6/level damage).
- [ ] [[DNDSRD/35eSRD/Spells/Hallow|Hallow]] [preparada:: 0]
	- Designates location as holy.
- [ ] [[DNDSRD/35eSRD/Spells/Inflict Light Wounds, Mass|Inflict Light Wounds, Mass]] [preparada:: 0]
	- Deals 1d8 damage +1/level to one creature/level, no two of which can be more than 30 ft. apart.
- [ ] [[DNDSRD/35eSRD/Spells/Insect Plague|Insect Plague]] [preparada:: 0]
	- Locust swarms attack creatures.
- [ ] [[DNDSRD/35eSRD/Spells/Mark of Justice|Mark of Justice]] [preparada:: 0]
	- Designates action that will trigger curse on subject.
- [ ] [[DNDSRD/35eSRD/Spells/Plane Shift|Plane Shift]] [preparada:: 0]
	- As many as eight subjects travel to another plane.
- [ ] [[DNDSRD/35eSRD/Spells/Raise Dead|Raise Dead]] [preparada:: 0]
	- Restores life to subject who died as long as one day/level ago.
- [ ] [[DNDSRD/35eSRD/Spells/Righteous Might|Righteous Might]] [preparada:: 0]
	- Your size increases, and you gain combat bonuses.
- [ ] [[DNDSRD/35eSRD/Spells/Scrying|Scrying]] [preparada:: 1]
	- Spies on subject from a distance.
- [ ] [[DNDSRD/35eSRD/Spells/Slay Living|Slay Living]] [preparada:: 0]
	- Touch attack kills subject.
- [ ] [[DNDSRD/35eSRD/Spells/Spell Resistance|Spell Resistance]] [preparada:: 0]
	- Subject gains SR 12 + level.
- [ ] [[DNDSRD/35eSRD/Spells/Summon Monster V|Summon Monster V]] [preparada:: 0]
	- Calls extraplanar creature to fight for you.
- [ ] [[DNDSRD/35eSRD/Spells/Symbol of Pain|Symbol of Pain]] [preparada:: 0]
	- Triggered rune wracks nearby creatures with pain.
- [ ] [[DNDSRD/35eSRD/Spells/Symbol of Sleep|Symbol of Sleep]] [preparada:: 0]
	- Triggered rune puts nearby creatures into catatonic slumber.
- [ ] [[DNDSRD/35eSRD/Spells/True Seeing|True Seeing]] [preparada:: 1]
	- Lets you see all things as they really are.
- [ ] [[DNDSRD/35eSRD/Spells/Unhallow|Unhallow]] [preparada:: 0]
	- Designates location as unholy.
- [ ] [[DNDSRD/35eSRD/Spells/Wall of Stone|Wall of Stone]] [preparada:: 0]
	- Creates a stone wall that can be shaped.
