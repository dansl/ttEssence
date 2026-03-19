# ttEssence - Handbook
A simplified Tabletop Role-Playing Game (ttRPG) ruleset. Made to be as simple and accessible as possible for people who just want to enjoy a fun story and roll some dice along the way!

---

## The Four Stats

Every hero/monster has four stats rated from **1 to 10**.

| Stat | Abbrev. | What It Covers |
|---|---|---|
| Strength | STR | Melee attacks, lifting, grappling, resisting |
| Dexterity | DEX | Ranged attacks, dodging, acrobatics, stealth |
| Mind | MND | Magic, knowledge, spotting traps, detecting lies |
| Charisma | CHA | Persuasion, deception, intimidation, inspiring |

### Stat Ratings

| Score | Meaning |
|---|---|
| 1 - 2 | Mediocre — Not great, just OK |
| 3 - 4 | Average — Better than OK |
| 5 - 6 | Trained — Practiced and capable |
| 7 - 8 | Expert — One of the best in the region |
| 9 - 10 | Legendary — Near-Mythical Talent |

### Building a Hero

See the [Character Sheet](/Docs/character-sheet.png). Print it off, and use a pencil so you can erase things as needed. Start by distributing **10 points** across your four stats. Every stat must be at least **1**. To start, no stat can be above **5**, that cap rises to 10 at level 5. 

Each hero will start with 10 Gold, which they can then use to buy gear to help them start their adventure. The GM can either let them pick their items before starting, or maybe the game starts in a small town shop where the heroes can buy their gear.

#### Example Characters

| Type | STR | DEX | MND | CHA |
|---|---|---|---|---|
| Fighter | 4 | 2 | 1 | 3 |
| Mage | 2 | 2 | 4 | 2 |
| Archer | 3 | 4 | 1 | 2 |
| Chad | 4 | 1 | 1 | 4 |

---

## Hit Points & Defense

**Hit Points (HP)** represent how much damage your hero can take before getting knocked out.

**HP = 10 + (STR × 2)**

> Example: A hero with STR 2 starts with **14 HP**. A hero with STR 4 starts with **18 HP**.

**Defense** is the number attackers must meet or beat by rolling a d20 to hit you.

| Type | Defense Score |
|---|---|
| No armor | 5 + DEX |
| Light armor | 7 + DEX |
| Medium armor | 9 + DEX — requires STR 4 |
| Heavy armor | 11 + DEX — requires STR 6 |

See [Armor Examples](/Docs/Armor.md)

> Example: A hero with DEX 4 and No Armor has 9 Defense. A hero with DEX 2 and Light Armor also has 9 Defense.

### When HP Hits 0

Your hero is **knocked out**. They can't act. An ally can spend their action to revive them, restoring 1d6 HP. If no one helps by the end of the next round, the hero wakes up on their own with 1 HP — bruised but alive.

**Heroes never permanently die by default.** For groups who want higher stakes, discuss changing this rule before play begins.

---

## Checks & Rolls

### Dice Names

You will see lots of references to "d2", "d4", "d6", "d8", "d10", "d20". These are shortnames for various dice. The "d" stands for "die" and the number is how many sides. Sometimes you might see something like "2d6", which just means roll two six-sided dice or just roll one d6 twice.

| Short | Description |
|---|---|
| d2 | Coin flip: heads = 1, tails = 2 |
| d4 | Four sided die |
| d6 | Six sided die |
| d8 | Eight sided die |
| d10 | Ten sided die |
| d20 | Twenty sided die |

### Skill Check Roll

When a hero tries something risky or uncertain, the GM decides how difficult the action will be using chart below. Heroes roll a **d20** and adds the relevant stat (ex: add DEX for a jump action or STR for pulling/pushing something). Meet or beat the **difficulty number** to succeed at the task.

> Example: Hero needs to jump over an easy gap, they rolled a 5 with a d20 and have 3 DEX. They successfully met the 8 requirement and make the jump! If they had rolled less then 5 and failed, then the GM decides what happens, maybe they take damage or maybe another player helps them by rolling another check!

| Difficulty | Number | Example |
|---|---|---|
| Easy | 8 | Climbing a short tree, convincing a friendly NPC |
| Medium | 12 | Picking a lock, sneaking past an alert guard |
| Hard | 16 | Leaping a wide chasm, deceiving a clever villain |
| Epic | 20 | Near-impossible feats — save for dramatic moments |

### Which Stat Do I Use?

- **Strength** — lift, smash, push, wrestle, hold on
- **Dexterity** — dodge, aim precisely, balance, sneak, hide
- **Mind** — recall facts, spot hidden details, solve puzzles, cast spells
- **Charisma** — persuade, lie, perform, intimidate, inspire allies

### Natural 20 & Natural 1

- **Roll exactly 20** — Critical success! You succeed spectacularly. The GM could even give bonus damage or bonus actions.
- **Roll exactly 1** — Complication! You fail, and something unexpected also goes wrong. Keep it surprising, not punishing.

### Advantage & Disadvantage

Sometimes the hero or monster will have an advantage or disadvantage depending on an event, spell, or action.

**Advantage** — Rolls 2d20 and take the higher result.

**Disadvantage** — Rolls 2d20 and take the lower result.

### Helping a Friend

If a second hero assists, both roll d20 + the relevant stat and take the **higher result**. Only one helper Hero per check.

---

## Weapons, Equipment & Items

Some weapons require a minimum stat to use effectively. A Hero using a weapon below its requirement means they have **disadvantage**.

Weapons that use ammo, like a Shortbow, will need to keep track of how many they use. To get more, heroes can either buy more from a shop, or a Long Rest will reset to it's default amount.

See [Weapon Examples](/Docs/Weapons.md)

Various Items can be purchased or found throughout the game.

See [Items Examples](/Docs/Items.md)
---

## Combat

### Initiative

At the start of combat, everyone — heroes and monsters alike — rolls a **d20**. Turns proceed from **highest to lowest**. Ties: Heroes go before monsters; tied heroes could play "Rock, Paper, Scissors" to break the tie, or just roll again.

### Your Turn

Each turn you may do all of the following:

1. **Move** — travel to anywhere nearby you could reasonably reach. Split your move before and after your action if you like.
2. **Action** — attack, cast a spell, use an item, help an ally, or do something creative.

### Making an Attack

Depending on the weapon or action, you roll **d20 + STR** (Melee) or **d20 + DEX** (Ranged) or **d20 + MND** (Spell). Meet or beat the target's **Defense score** to hit. On a hit, roll your weapon or action's damage die and subtract from their HP.

> Example: A Hero (DEX 3) fires a shortbow at a goblin (Defense 11). They roll a d20 and get 9 + 3 DEX = 12. Hit! She rolls d6 and gets 4 — the goblin takes 4 damage.

### Short & Long Rests

In between a battle or big event you can Short or Long rest.

- **Short rest** (a brief break) — restore **half HP and MP**.
- **Long rest** (a full night's sleep) — restore **all HP and all MP**, restore magical items, restore ammo for ranged weapons (ex: bow). Possibility to get attacked or robbed while resting. GM may roll to see if an event happens using d20 and difficulty of their choice according to the surroundings.

---

## Magic

### Learn Spells

Every hero can learn magic. Your **Mind stat (MND)** determines which spell tiers you can access. Higher MND unlocks more powerful spells. If your main goal is to be a spell user, you will want to focus on adding more to your MND Skill since it helps get better spells and more successful on your Spell Attack Rolls.

### Magic attack

Roll a d20 + MND stat against the enemies Defense, then depending on the spell, use another die to calculate damage.

### Magic Points

**MP = 5 + (MND × 2)**

> Example: A hero with MND 1 has 7 Magic Points (MP). A hero with MND 5 has 15 MP.

### Recover MP
MP is restored after a short or long rest. You can also use potions or other items to restore MP.

### Spell Tiers

| Tier | Name | Mind Req. | MP Cost | Damage |
|---|---|---|---|---|
| 0 | Cantrip | MND 1+ | 1 MP | none |
| 1 | Minor | MND 3+ | 1 MP | d4 |
| 2 | Moderate | MND 4+ | 2 MP | d6 |
| 3 | Major | MND 5+ | 3 MP | d8 |
| 4 | Legendary | MND 6+ | 4 MP | d10 |

### Learning Spells

Heroes start knowing **2 spells** from any tier they qualify for according to their MND stat. Each level-up, can learn **1 new spell**. Spells can also be found on **scroll items** during adventures.

See [Spells Examples](/Docs/Spells.md)

> Example: A fighter with MND 1 finds a Scroll of Fireball (Tier 2 — MND 3+). They can't learn it yet — but it's great motivation to invest in Mind when they level up.*

---

## Leveling Up

This game uses **milestone leveling**. The GM awards a level when the party reaches a meaningful story moment.

### When to Award a Level

- Completing a major quest
- Defeating a significant villain
- Unlocking a long-sought secret
- Surviving against overwhelming odds
- Reaching the end of a story chapter

**Heroes always level up together.** No one falls behind.

### Level Progression

| Level | Stat Points | New Spells | Info |
|---|---|---|---|
| 1 | 10 to start | 2 starting spells | Stat cap at 5 |
| 2 | +2 | +1 |  |
| 3 | +2 | +1 |  |
| 4 | +2 | +1 |  |
| 5 | +2 | +1 | Stat cap rises to 10 |
| 6+ | +2 per level | +1 per level |  |
| 10 | +2 | +1 | Max Level |

---

## Monsters

### Quick Monster Creation

Make a monster like you would a hero, just lower the distribution of the points and lower the HP and MP calculation.

| Tier | Stat Points | Attack Damage | Bonus |
|---|---|---|---|
| Minion | 8 | d4 | None |
| Standard | 12 | d6 | None |
| Elite | 16 | d8 | +10 HP |
| Boss | 20 | d10 + two actions | +15 HP |
| Legendary | 25 | 2d10 + two action + multiple phases | +20 HP |

If you want to make the game easier, use **half (round up)** what the heroes use to calculate HP, MP, Defense (ex: HP=5+(STR x2)). For added difficulty, you can adjust it up.

See [Bestiary Examples](/Docs/Bestiary.md)

### Monster Defeat

When the heroes defeat the monster, reward them with items or gold. If the monster was legendary or a major boss, then let all the heroes level up!

---

## Starting a Campaign 

Make up your own story with fun characters, strong bosses, mysteries to solve, and quests to complete. Make it silly, scary, mysterious, and fun! Maybe ask the players what they want to fight, or just keep it a mystery, then tweak the details before you begin. The only limit is your imagination!

See [Campaign Examples](/Docs/Campaign.md)

---

## GM Tips

### Running the Game

- **Say yes more than no.** If a player has a creative idea, let them try it and roll for it.
- **Describe the world with senses.** Not just what they see — what they smell, hear, feel underfoot.
- **Pause and check in.** Especially with younger players — ask "is everyone having fun?" after tough scenes.
- **Grab a Notepad** You will need to write lots of things down, like the battle order, monsters current health, or reminders about spells or effects.

### Adjusting Difficulty

- **Too easy?** Add one extra minion, give the boss the Legendary React, or have enemies use smarter tactics (flank, retreat, call for help).
- **Too hard?** Give heroes a free short rest, reduce monster HP by 25%, or have enemies surrender or flee at half HP.
- **Younger players?** Remove the damage dice entirely — every hit deals exactly 2 damage and every heal restores 4. Simple and fast.

---
