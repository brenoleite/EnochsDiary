---
{"dg-publish":true,"permalink":"/ficha-auxiliar-enoch/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# [[Personagens/Enoch|Enoch]]
**Level**:: 12
**FOR**:: 4
**DES**:: 0
**CON**:: 2
**INT**:: 0
**SAB**:: 2
**CAR**:: 3

## Combate
- **CA**: 19+6 (escudo)
- **Espada Larga**: (19/20x2)
	- **Ataque:** d20+`=this.FOR+this.BBA+2` => (`dice: 1d20+FOR+BBA+2|noform|none|render`)
	- **Dano:** 2d6+`=this.FOR/2+this.FOR` => (`dice: 2d6+FOR/2+FOR|noform|none|render`)
- **Espada Longa**: (17/20x2)
	- **Ataque:** d20+17
	- **Dano**: 1d8+4
- **Destruir o mal**: 
	- **Ataque**: +`=this.CAR` (Carisma)
	- **Dano**: +`=this.Level` (Nível)
- **Agarrar:** 16
- **BBA**:: 12

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

## Magias Preparadas para o dia

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

## **Testes**: 
- **Fortitude:** 15 => (`dice:d20+15|noform|none|render`)
- **Reflexos:** 9 => (`dice:d20+9|noform|none|render`)
- **Vontade:** 11 => (`dice:d20+11|noform|none|render`)
## Perícias mais usadas

 
 |               Perícia |          Modificador          | resultado |
 | ---------------------:|:-----------------------------:|:---------:|
 |              Cavalgar |       +`=this.Cavalgar`       |`dice:d20+Cavalgar\|noform\|render\|none`|
 |          Concentração |     +`=this.Concentracao`     |`dice:d20+Concentracao\|noform\|render\|none`|
 | Conhecimento Religião | +`=this.ConhecimentoReligiao` |`dice:d20+ConhecimentoReligiao\|noform\|render\|none`|
 |                  Cura |         +`=this.Cura`         |`dice:d20+Cura\|noform\|render\|none`|
 |            Diplomacia |      +`=this.Diplomacia`      |`dice:d20+Diplomacia\|noform\|render\|none`|
 |              Observar |       +`=this.Observar`       |`dice:d20+Observar\|noform\|render\|none`|
 |                 Ouvir |        +`=this.Ouvir`         |`dice:d20+Ouvir\|noform\|render\|none`|
 |      Sentir Motivação |   +`=this.SentirMotivacao`    |`dice:d20+SentirMotivacao\|noform\|render\|none`|
 
---
## Magias
#### level 1
- [ ] [[DNDSRD/35eSRD/SpellsManual/Abençoar Arma|Abençoar Arma]] [preparada:: 0]
	- Arma fica boa e é considerada mágica contra inimigos maus.
- [ ] [[DNDSRD/35eSRD/Spells/Bless|Bless]] [preparada:: 1]
	- Allies gain +1 on attack rolls and +1 on saves against fear. 
- [ ] [[DNDSRD/35eSRD/Spells/Bless Water|Bless Water]] [preparada:: 0]
	- Makes holy water.
- [ ] [[DNDSRD/35eSRD/Spells/Create Water|DNDSRD/35eSRD/Spells/Create Water]] [preparada:: 0]
	- Creates 2 gallons/level of pure water.
- [ ] [[DNDSRD/35eSRD/Spells/Cure Light Wounds|Cure Light Wounds]] [preparada:: 0]
	- Cures 1d8 damage +1/level (max +5).
- [ ] [[DNDSRD/35eSRD/Spells/Detect Poison|Detect Poison]] [preparada:: 0]
	- Detects poison in one creature or small object.
- [ ] [[DNDSRD/35eSRD/Spells/Detect Undead|Detect Undead]] [preparada:: 0]
	- Reveals undead within 60 ft.
- [ ] [[DNDSRD/35eSRD/Spells/Divine Favor|Divine Favor]] [preparada:: 1]
	- You gain +1 per three levels on attack and damage rolls.
- [ ] [[DNDSRD/35eSRD/Spells/Endure Elements|Endure Elements]] [preparada:: 0]
	- Exist comfortably in hot or cold environments.
- [ ] [[DNDSRD/35eSRD/Spells/Magic Weapon|Magic Weapon]] [preparada:: 0]
	- Weapon gains +1 bonus attack and damage. (Doesn't stack with OP)
- [ ] [[DNDSRD/35eSRD/Spells/Protection from Evil m|Protection from Evil m]] [preparada:: 0]
	- +2 to AC and saves, counter mind control (including enchantment (charm) effects and enchantment (compulsion), hedge out elementals and outsiders.
- [ ] [[DNDSRD/35eSRD/Spells/Protection from Chaos|Protection from Chaos]]  [preparada:: 0]
	- igual protection from evil mas para o caos
- [ ] [[DNDSRD/35eSRD/Spells/Read Magic|Read Magic]] [preparada:: 0]
	- Read scrolls and spellbooks.
- [ ] [[DNDSRD/35eSRD/Spells/Resistance|Resistance]] [preparada:: 0]
	- Subject gains +1 on saving throws.
- [ ] [[DNDSRD/35eSRD/Spells/Restoration, Lesser|Restoration, Lesser]] [preparada:: 0]
	- Dispels magical ability penalty or repairs 1d4 ability damage.
- [ ] [[DNDSRD/35eSRD/Spells/Virtue|Virtue]] [preparada:: 0]
	- Subject gains 1 temporary hp.

#### level 2
- [ ] [[DNDSRD/35eSRD/Spells/Resist Energy m|Resist Energy m]]  [preparada:: 1]
	- 10 redução de dano contra 1 elemento escolhido
- [ ] [[Bull’s Strength|Bull’s Strength]] [preparada:: 1]
	- Subject gains +4 to Str for 1 min./level.
- [ ] [[DNDSRD/35eSRD/Spells/Delay Poison|Delay Poison]] [preparada:: 0]
	- Stops poison from harming subject for 1 hour/level.
- [ ] [[Eagle’s Splendor|Eagle’s Splendor]] [preparada:: 0]
	- Subject gains +4 to Cha for 1 min./level.
- [ ] [[Owl’s Wisdom|Owl’s Wisdom]] [preparada:: 0]
	- Subject gains +4 to Wis for 1 min./level.
- [ ] [[DNDSRD/35eSRD/Spells/Remove Paralysis|Remove Paralysis]] [preparada:: 0]
	- Frees one or more creatures from paralysis or slow effect.
- [ ] [[DNDSRD/35eSRD/Spells/Shield Other|Shield Other]] [preparada:: 0]
	- You take half of subject’s damage.
- [ ] [[DNDSRD/35eSRD/Spells/Undetectable Alignment|Undetectable Alignment]] [preparada:: 0]
	- Conceals alignment for 24 hours.
- [ ] [[DNDSRD/35eSRD/Spells/Zone of Truth|Zone of Truth]] [preparada:: 0]
	- Subjects within range cannot lie.

#### level 3
- [ ] [[DNDSRD/35eSRD/Spells/Cure Moderate Wounds|Cure Moderate Wounds]] [preparada:: 0]
	- Cures 2d8 damage +1/level (max +10).
- [ ] [[DNDSRD/35eSRD/Spells/Daylight|Daylight]] [preparada:: 0]
	- 60-ft. radius of bright light + 60-ft of dim light.
- [ ] [[DNDSRD/35eSRD/Spells/Discern Lies|Discern Lies]] [preparada:: 0]
	- Reveals deliberate falsehoods.
- [ ] [[DNDSRD/35eSRD/Spells/Dispel Magic|Dispel Magic]] [preparada:: 0]
	- Cancels spells and magical effects.
- [ ] [[DNDSRD/35eSRD/Spells/Heal Mount|Heal Mount]]  [preparada:: 0]
	- Removes various conditions And heal 10hp/level (max 150) of the paladins' mount.
- [ ] [[DNDSRD/35eSRD/Spells/Magic Circle against Chaos|Magic Circle against Chaos]] [preparada:: 0]
	- As [[Protection from Evil Or Chaos|Protection from Evil Or Chaos]], but 10-ft. radius and 10 min./level.
- [ ] [[DNDSRD/35eSRD/Spells/Magic Circle against Evil|Magic Circle against Evil]] [preparada:: 1]
	- As [[Protection from Evil Or Chaos|Protection from Evil Or Chaos]], but 10-ft. radius and 10 min./level.
- [ ] [[DNDSRD/35eSRD/Spells/Magic Weapon, Greater|Magic Weapon, Greater]] [preparada:: 0]
	- +1 bonus on attack and damage per four levels (max +5)
- [ ] [[DNDSRD/35eSRD/Spells/Prayer|Prayer]] [preparada:: 0]
	- Allies +1 bonus on most rolls, enemies -1 penalty. (attack rolls, weapon damage rolls, saves, and skill checks)Pe
- [ ] [[DNDSRD/35eSRD/Spells/Remove Blindness_Deafness m|Remove Blindness_Deafness m]] [preparada:: 0]
	- Cures normal or magical conditions.
- [ ] [[DNDSRD/35eSRD/Spells/Remove Curse|Remove Curse]] [preparada:: 0]
	- Frees object or person from curse. 


