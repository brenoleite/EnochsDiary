---
{"dg-publish":true,"permalink":"/ficha-auxiliar-enoch/","dgHomeLink":true,"dgPassFrontmatter":false}
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
let lv1s = dv.pages(dv.current().file.title).file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "level 1")
	//	.limit(dv.current().num1stlevelspell)
if ( lv1s.length > 0 ) {
	dv.header(5, "Level 1")
	if ( lv1s.length > dv.current().num1stlevelspell)
		dv.span("**Há mais magias preparadas que o limite diário**")
	dv.taskList(lv1s,false)
}

let lv2s = dv.pages(dv.current().file.title).file.tasks
	.where(m => m.preparada && m.preparada >= 1 &&
	m.header.subpath == "level 2")
		//.limit(dv.current().num2ndlevelspell)
if (lv2s.length > 0 ) {
	dv.header(5, "Level 2")
	if ( lv2s.length > dv.current().num2ndlevelspell)
		dv.span("**Há mais magias preparadas que o limite diário**")
	dv.taskList(lv2s,false)
}

let lv3s = dv.pages(dv.current().file.title).file.tasks
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
#### level 1
- [ ] [[DNDSRD/35eSRD/Spells/Abençoar Arma|Abençoar Arma]] [preparada:: 1]
	- Arma fica boa e é considerada mágica contra inimigos maus.
- [ ] [[teste/Bless|Bless]] [preparada:: 0]
	- Allies gain +1 on attack rolls and +1 on saves against fear. 
- [ ] [[DNDSRD/35eSRD/Spells/Bless Water (M)|Bless Water (M)]] [preparada:: 0]
	- Makes holy water.
- [ ] [[teste/Create Water|Create Water]] [preparada:: 0]
	- Creates 2 gallons/level of pure water.
- [ ] [[teste/Cure Light Wounds|Cure Light Wounds]] [preparada:: 0]
	- Cures 1d8 damage +1/level (max +5).
- [ ] [[teste/Detect Poison|Detect Poison]] [preparada:: 0]
	- Detects poison in one creature or small object.
- [ ] [[teste/Detect Undead|Detect Undead]] [preparada:: 0]
	- Reveals undead within 60 ft.
- [ ] [[teste/Divine Favor|Divine Favor]] [preparada:: 1]
	- You gain +1 per three levels on attack and damage rolls.
- [ ] [[teste/Endure Elements|Endure Elements]] [preparada:: 0]
	- Exist comfortably in hot or cold environments.
- [ ] [[teste/Magic Weapon|Magic Weapon]] [preparada:: 0]
	- Weapon gains +1 bonus attack and damage. (Doesn't stack with OP)
- [ ] [[DNDSRD/35eSRD/Spells/Protection from Evil Or Chaos|Protection from Evil Or Chaos]] [preparada:: 0]
	- +2 to AC and saves, counter mind control (including enchantment (charm) effects and enchantment (compulsion), hedge out elementals and outsiders.
- [ ] [[DNDSRD/35eSRD/Spells/Read Magic (F)|Read Magic (F)]] [preparada:: 0]
	- Read scrolls and spellbooks.
- [ ] [[teste/Resistance|Resistance]] [preparada:: 0]
	- Subject gains +1 on saving throws.
- [ ] [[teste/Restoration, Lesser|Restoration, Lesser]] [preparada:: 0]
	- Dispels magical ability penalty or repairs 1d4 ability damage.
- [ ] [[teste/Virtue|Virtue]] [preparada:: 0]
	- Subject gains 1 temporary hp.

#### level 2
- [ ] [[DNDSRD/35eSRD/Spells/Resistência a elementos|Resistência a elementos]]  [preparada:: 0]
	- 10 redução de dano contra 1 elemento escolhido
- [ ] [[DNDSRD/35eSRD/Spells/Bull’s Strength|Bull’s Strength]] [preparada:: 1]
	- Subject gains +4 to Str for 1 min./level.
- [ ] [[teste/Delay Poison|Delay Poison]] [preparada:: 0]
	- Stops poison from harming subject for 1 hour/level.
- [ ] [[DNDSRD/35eSRD/Spells/Eagle’s Splendor|Eagle’s Splendor]] [preparada:: 1]
	- Subject gains +4 to Cha for 1 min./level.
- [ ] [[DNDSRD/35eSRD/Spells/Owl’s Wisdom|Owl’s Wisdom]] [preparada:: 0]
	- Subject gains +4 to Wis for 1 min./level.
- [ ] [[teste/Remove Paralysis|Remove Paralysis]] [preparada:: 0]
	- Frees one or more creatures from paralysis or slow effect.
- [ ] [[DNDSRD/35eSRD/Spells/Shield Other (F)|Shield Other (F)]] [preparada:: 0]
	- You take half of subject’s damage.
- [ ] [[teste/Undetectable Alignment|Undetectable Alignment]] [preparada:: 0]
	- Conceals alignment for 24 hours.
- [ ] [[teste/Zone of Truth|Zone of Truth]] [preparada:: 0]
	- Subjects within range cannot lie.

#### level 3
- [ ] [[teste/Cure Moderate Wounds|Cure Moderate Wounds]] [preparada:: 0]
	- Cures 2d8 damage +1/level (max +10).
- [ ] [[teste/Daylight|Daylight]] [preparada:: 0]
	- 60-ft. radius of bright light + 60-ft of dim light.
- [ ] [[teste/Discern Lies|Discern Lies]] [preparada:: 0]
	- Reveals deliberate falsehoods.
- [ ] [[teste/Dispel Magic|Dispel Magic]] [preparada:: 0]
	- Cancels spells and magical effects.
- [ ] [[teste/Heal Mount|Heal Mount]]  [preparada:: 0]
	- Removes various conditions And heal 10hp/level (max 150) of the paladins' mount.
- [ ] [[teste/Magic Circle against Chaos|Magic Circle against Chaos]] [preparada:: 0]
	- As [[DNDSRD/35eSRD/Spells/Protection from Evil Or Chaos|Protection from Evil Or Chaos]], but 10-ft. radius and 10 min./level.
- [ ] [[teste/Magic Circle against Evil|Magic Circle against Evil]] [preparada:: 1]
	- As [[DNDSRD/35eSRD/Spells/Protection from Evil Or Chaos|Protection from Evil Or Chaos]], but 10-ft. radius and 10 min./level.
- [ ] [[teste/Magic Weapon, Greater|Magic Weapon, Greater]] [preparada:: 0]
	- +1 bonus on attack and damage per four levels (max +5)
- [ ] [[teste/Prayer|Prayer]] [preparada:: 0]
	- Allies +1 bonus on most rolls, enemies -1 penalty. (attack rolls, weapon damage rolls, saves, and skill checks)Pe
- [ ] [[DNDSRD/35eSRD/Spells/Remove Blindness or Deafness|Remove Blindness or Deafness]] [preparada:: 0]
	- Cures normal or magical conditions.
- [ ] [[teste/Remove Curse|Remove Curse]] [preparada:: 0]
	- Frees object or person from curse. 


