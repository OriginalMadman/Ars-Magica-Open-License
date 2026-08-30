# Aldric of Mercere — Character Creation Rules Review

A line-by-line audit of `aldric-of-mercere.md` against the rules text in this
repository (`reviewed/Ars Magica - Definitive Edition (Core Rules).md`, cross-checked
against `wip/Ars Magica 5e - Core Rules.md` where the two editions might differ).

**Verdict:** the concept is sound and most of the arithmetic is right, but there are
**seven rules errors**, three of which change the character's numbers materially, plus
two design assumptions that need a troupe ruling. The corrected, fully-balanced build
is in `aldric-of-mercere-sheet.md`.

---

## Summary table

| # | Issue | Severity | Effect |
|---|---|---|---|
| 1 | Puissant Creo is **+3**, not +2 | Error (in his favour) | Creo 17, not 16 |
| 2 | **Large gives no Strength or Stamina bonus** | Error | Str +1→0, Sta +2→+1 unless paid for |
| 3 | **Vow is a Personality Flaw**, not a Story Flaw | Error | Three Personality Flaws — over the limit |
| 4 | Casting Totals omit **Encumbrance and Aura** | Error | −2 in armour; −3 away from the covenant |
| 5 | Post-Gauntlet XP over budget; **Creo 12→14 never paid for** | Error | ~23 points overspent |
| 6 | Brawl 1 appears in the final list but is **never bought** | Error | 5 XP unaccounted |
| 7 | Three custom spells have **illegal levels or bad maths** | Error | See §7 |
| 8 | *Aura of Martial Precision* at Gauntlet **exceeds his maximum learnable level** | Error | Level 30 vs a cap of 25 |
| 9 | *Endurance of the Berserkers* is **Range: Personal** — self only | Error | Cannot be put on allies as described |
| 10 | Every group buff at level 26+ **Warps the recipients** | Design flaw | Warps his own warband |
| 11 | Only 8 of the available **10 Virtue/Flaw points** used | Missed opportunity | Two free Minor Virtues left unbought |
| 12 | Focus scope is at the generous end | Troupe call | May be Major-focus breadth |

---

## 1. Puissant Creo is +3, not +2

> **Puissant (Art)** — *Minor, Hermetic.* "You add **3** to the value of one Art whenever
> you use it. This means all totals in which the score of the Art is part of the total.
> It does not apply when learning, teaching, or writing about the Art."

The draft uses +2 throughout, which is the value for **Puissant (Ability)** (correctly
applied to Single Weapon). Aldric's effective Creo is **17**, not 16 — so every Creo
casting total and Lab Total in the draft is one point low.

The House choice itself is right: the House table gives Mercere magi *"Puissant Creo or
Puissant Muto"*, and the same entry confirms the flavour: *"Gifted Redcaps take the
Hermetic Magus Status Virtue, and do not take the Redcap Major Status Virtue."* So
"Gifted Redcap of House Mercere" is correct terminology, not a lore slip.

## 2. Large does not give +1 Strength and +1 Stamina

This is the biggest single error. The Virtue reads, in full:

> **Large** — *Minor, General.* "Your Size is +1 instead of 0, so you are between six and
> seven feet tall. This means that the severity of wounds you take increases in six point
> intervals rather than five point intervals."

That is the whole Virtue. The +1 Strength and +1 Stamina the draft attributes to it
belongs to **Giant Blood** (*Major, General*: Size +2, **and** +1 to both Strength and
Stamina) — a three-point Virtue, not a one-point one.

Knock-on effects if left uncorrected: Strength 0 and Stamina +1, so Damage +6 (not +7),
Soak +13 (not +14), every Casting Score one lower, and Encumbrance 3 (not 2) because
Encumbrance is Burden minus Strength.

**Fix used in the corrected sheet:** take **Improved Characteristics a second time**
(explicitly allowed: *"You may take this Virtue multiple times"*), giving 13 Characteristic
points instead of 10, and buy Str +1 and Sta +2 honestly. This lands on exactly the
numbers the draft claimed, but legally.

## 3. Vow is a Personality Flaw — Aldric has one too many

> **Vow** — *Major or Minor, **Personality***.

The draft files it as a Story Flaw. It isn't. That gives Aldric **three** Personality
Flaws (Compassionate Major, Overconfident Minor, Vow Minor), and the rules are explicit:

> "You should not take more than two Personality Flaws, and **may not** take more than one
> Major Personality Flaw."

He is inside the Major limit but over the total. He also has **no** Story Flaw, which for a
magus is a missed opportunity rather than a violation.

**Fix:** drop the Vow as a mechanical Flaw — fold "never abandon a companion" into
Compassionate, which already says *"You help anyone who is wounded or in trouble. You
cannot bear to see suffering in others"* — and take a Story Flaw instead. **Favors**
(*Major, Story* — "You owe a boon to someone… and may be called upon to return the favor at
any time") fits a Gifted Redcap who gets lent out to expeditions almost perfectly, and
brings him to the full 10 points. **Hermetic Patron** (*Minor, Story*) is the lighter option.

## 4. Casting Totals are missing Encumbrance and Aura

> **CASTING SCORE: Technique + Form + Stamina − Encumbrance + Aura Modifier**

The draft's casting totals are just Technique + Form + Focus + Stamina. Two things are missing:

- **Encumbrance −2.** Full chain mail (Load 6) + longsword (1) + heater shield (2) = Load 9,
  which is Burden 3 on the table; Encumbrance is the amount by which Burden exceeds
  Strength, so **2** with Str +1. Note that the rules single spellcasting out: *"Most
  athletic activities are penalized, **as is spell casting**, but, in combat, Attack and
  Defense are not, as long as the Encumbrance is largely due to weapons and armor."* So
  Aldric's armour costs him casting and Initiative but nothing on his sword arm.
- **Aura.** The draft assumes Aura +3 for Lab Totals (fair) but then quietly carries the
  same assumption into combat. On campaign the aura is normally **0**, so his field casting
  totals are 3 lower than his covenant ones. This matters: it is the difference between
  "always works" and "sometimes costs a Fatigue level".

## 5. Post-Gauntlet experience is over budget, and Creo is unpaid

The rule for a magus generated some years past Gauntlet:

> "For every year, the magus gets 30 points. Each point can be an experience point in an Art
> or Ability **or one level of spell**… For each season that your magus spends working on a
> lab project, the character loses 10 points from the yearly 30 experience points, **to a
> minimum of 0 if three or four seasons are spent** on lab work."

Five years = **150 points**. The draft's table lists 155 and calls it "~150 XP; slight
approximation acceptable". Two problems:

- It is 5 over, not approximately equal.
- **Creo rises from 12 at Gauntlet to 14 in the final scores and is never bought.** That is
  27 raw points, or 18 after the Affinity, which is nowhere in the budget. Real total: ~173
  against a 150 allowance.

There is also a small efficiency point: the draft charges 40 points for four lab seasons
spread over four years. Putting **three or four seasons into a single year costs only 30**,
because that year's allowance simply drops to zero. Same lab output, ten points cheaper.

## 6. Brawl 1 is never bought

Brawl 1 appears in the Final Scores list marked "(from childhood)", but the Early Childhood
table spends all 45 experience points on Normandy Lore 2, Athletics 2 and Awareness 2. It
is 5 XP that does not exist. (Brawl *is* on the legal childhood list, so it is purely an
accounting slip.) The corrected sheet buys it properly.

## 7. Custom spell levels

The relevant arithmetic rule:

> "Add one magnitude (five levels) to the level of the spell for every step by which the
> parameter is raised… **Below level 5, adding a magnitude only adds one level.**"

So above 5, spell levels are always multiples of five.

| Spell | Draft | Problem | Correct |
|---|---|---|---|
| *Rally of the Fallen* | CrCo **34** | 34 is not a legal spell level. Base 4 (+9 Recovery) +1 Touch +3 Moon +2 Group = 30 | **CrCo 30** |
| *Shield of the Iron Body* | MuCo **30** | Calculated as "Base 25 + 5 (Touch)" but listed as D: Sun — Sun is +2 magnitudes, which was never added | **MuCo 40** as designed, and 40 exceeds his MuCo Lab Total of 36 |
| *Aura of Martial Precision* | MuCo **30** | Arithmetic is fine (5+5+10+10), but the guideline it cites is *"Make a body resistant to damage (+1 Soak)"* — a Soak guideline being used for an Attack bonus | See below |
| *Precision of the Hawk* | MuCo **20** | No base given; Touch + Concentration is only +2 magnitudes, so it implies base 10, which is the *"+2 Soak"* guideline | Rebuild |
| *Blessing of the Steadfast Champion* | CrCo **45** Ritual | **Correct.** Base 40 = *"Increase one of a person's physical Characteristics by one point, to no more than +2"*, +1 Touch = 45; magnitude 9 = 9 pawns | ✓ |

On the attack buff specifically: there is **no Muto Corpus guideline for a combat bonus**.
The Muto Corpus list runs from *"Change someone to give them a minor ability"* (base 2)
through the Soak ladder (base 5/10/15/20/25 for +1/+2/+3/+4/+5 Soak) to whole-body
transformation. The two defensible readings are:

1. **Muto Corpus base 2, "a minor ability"** — sharpened reflexes and an unerring sense of an
   opponent's guard, for **+1 Attack**. Cheap, and this is what the corrected sheet uses.
2. **Creo Corpus, temporary Characteristic increase** — base 35 raises a physical
   Characteristic to no more than +1, base 40 to no more than +2. A Touch/Sun/Group version
   is level 60, well beyond a five-year magus.

The draft's "+2 to all Attack Totals" is closer to (2) in power but priced like (1). Pick a
lane with the troupe.

## 8. *Aura of Martial Precision* is illegal at Gauntlet

> "The highest level spell you can learn is equal to Technique + Form + Intelligence +
> Magic Theory + 3… any Virtues and Flaws your character has apply to this total if they
> would apply to a Lab Total in play."

At Gauntlet, Aldric had Muto 3, Corpus 10, Int +3, Magic Theory 3, and the focus adds the
lower Art again (+3):

**Muto Corpus cap = 3 + 10 + 3 + 3 + 3 + 3 = 25.**

*Gift of the Bear's Fortitude* at MuCo 25 just squeaks in. *Aura of Martial Precision* at
MuCo 30 does not. (His Creo Corpus cap was 44, so the CrCo spells were never in danger —
the problem is that his signature spell is his *weak* Technique.)

## 9. *Endurance of the Berserkers* cannot be cast on other people

The book's version is **R: Per** — Personal range, self only:

> *Endurance of the Berserkers* — R: Per, D: Conc, T: Ind. "Your body acts as though it were
> unwounded and unfatigued for as long as you concentrate."

The "Attack Total in Play" section says *"Combined with Endurance of the Berserkers on each
key fighter…"*. That needs a reinvented Touch-range version: base 10 +1 Touch +1 Conc = **ReCo
20**, and his Rego Corpus Lab Total is only 25, so it is buildable but tight — and a Group
version at ReCo 30 would cross the Warping line (below).

Related and worth knowing: **Range: Personal spells are the only ones that skip your own
Magic Resistance.**

> "Spells cast with Personal Range do not have to overcome the caster's own Magic Resistance.
> Spells cast with any other Range, **even if cast by the maga on herself**, do have to
> overcome the caster's own Magic Resistance."

Aldric's own resistance against Corpus magic is Corpus 12 + (5 × Parma 1) = **17**. So his
Touch-range self-buffs must either penetrate 17, or be cast *before* he performs the Parma
Magica ritual. Practically: buff first, raise Parma second. Both of his book self-buffs
(*Bear's Fortitude*, *Berserkers*) are R: Per and dodge this entirely — which is exactly why
they are written that way.

## 10. The concept's real hidden cost: he Warps his own warband

This is the most interesting rules interaction in the whole build, and the draft misses it.

> "Anyone subjected to a powerful supernatural effect gains a Warping Point, unless they
> themselves were responsible for the effect or it was specifically and carefully designed
> to work on them. 'Powerful effect' is subjective, but **any Hermetic spell of sixth
> magnitude or higher counts**."

Sixth magnitude is **level 26+**. *Aura of Martial Precision* (30), *Shield of the Iron Body*
(30/40) and *Rally of the Fallen* (34) are all over the line. Every grog Aldric buffs before
every battle takes a Warping Point each time. Warping Score 1 arrives at 5 points, Score 2 at
15 — so a warband that fights a dozen skirmishes a year is visibly Warped inside two seasons.

There is a second, slower source that applies even to legal-level spells:

> "A character who is constantly under the influence of one or more active supernatural
> effects gains one Warping Point per year for each effect… A character under the effect of
> a different Sun Duration spell from sunrise to sunset every day for a year would gain a
> Warping Point."

**Design rule for this character: keep every buff you cast on other people at level 25 or
less.** That single constraint is what shapes the corrected spell list.

It also, incidentally, resolves the draft's Warping Score. A 30-year-old magus five years
out of apprenticeship, living in an Aura 3 covenant with no Longevity Ritual, should have
**Warping Score 0**: auras only Warp above strength 5, and Hermetic magi are immune to Magic
auras anyway. The draft's "Warping Score 1 (5 points)" is the exact package granted by the
Minor Supernatural Flaw **Warped by Magic** — which he hasn't taken. Either take that Flaw
(it comes with a free extra Minor Flaw representing the source, unbalanced by a Virtue) or
set Warping to 0. Keeping a Sun-duration self-buff running most days is a perfectly good
in-fiction justification for taking it.

## 11. Two Virtue/Flaw points are being left on the table

> "Like companions, magi may take up to **ten** points of Flaws, and the same number of
> points of Virtues."

The draft stops at 8/8. Combined with the Vow correction, there is room for a Story Flaw
plus two more Minor Virtues. See the Min-Max section below for what to spend them on.

## 12. Focus scope — a troupe call, but flag it

> **Minor Magical Focus** — "the field should be slightly narrower than a single Technique
> and Form combination, although it may include restricted areas of several such
> combinations. **Healing**, for example, is a part of Creo Corpus, Creo Animal, and possibly
> Creo Herbam."

So spanning several Technique/Form pairs is explicitly fine. The question is narrowness.
"Healing" is a *slice* of Creo Corpus. "Enhancing the human body" is closer to *all
beneficial Creo Corpus plus all beneficial Muto Corpus* — two nearly-whole combinations. It
is the most generous Minor Focus in the build and the first thing a storyguide will push
back on. Narrowing it to **"improving the body's Characteristics"** keeps every spell in his
actual list inside the focus while sounding like a Minor focus, and I'd lead with that.

Mechanically the draft applies it correctly: *"add the lowest applicable Art score twice"*,
so the bonus equals the lower of Technique and Form — +12 for Creo Corpus, +7 for Muto Corpus.

---

## Things the draft got right

Worth saying, because most of it is right:

- Virtue/Flaw balance (8/8), one Major Personality Flaw, one Hermetic Flaw ✓
- Deficient Technique text: *"All totals, including Lab and Casting totals, including a
  particular Technique are halved"* ✓
- Characteristic costs: Int +3 = 6, Dex +2 = 3, Sta +1 = 1, Qik +1 = 1, Pre −1 gains 1 = 10 ✓
- Early childhood 45 XP, later life 15/year, apprenticeship 240 XP + 120 spell levels ✓
- Recommended minimum Abilities (Latin 4, Artes Liberales 1, Magic Theory 3, Parma 1 = 90 XP) ✓
- Affinity arithmetic: 52 spent × 1.5 = 78 = Creo 12 ✓
- Art costs (Creo 12 = 78, Corpus 10 = 55) ✓, and 120 spell levels totalling exactly 120 ✓
- Weapon and armour stats: Long Sword Init +2 / Atk +4 / Dfn +1 / Dam +6 / Load 1; Heater
  Shield Dfn +3 / Load 2; Full Chain Mail Prot 9 / Load 6 ✓
- Combat formulae, and adding weapon + shield modifiers together ✓
- Burden 3 from Load 9 ✓
- Size +1 wound intervals: 1–6 / 7–12 / 13–18 / 19–24 / 25+ ✓
- Magic Resistance = Form + 5 × Parma ✓
- All six book spells quoted at their correct Art, level, Range, Duration and Target ✓
- *Blessing of the Steadfast Champion* — correct guideline, correct level, correct vis cost ✓
- Confidence 1 / 3 points ✓

---

# Min-Maxing a Hermetic Warrior — What Else Is Legal

Everything below is core-rules only.

## The single most important thing about this concept

> **DAMAGE TOTAL: Strength + Weapon Damage Modifier + Attack Advantage**
>
> **ATTACK ADVANTAGE: Attacker's Attack Total − Defender's Defense Total**

**Attack Advantage rolls straight into damage.** A +1 to Attack is not just a better chance
to hit — it is a flat +1 damage on every hit that lands. An attack buff on six grogs is worth
+6 damage across the line *per round*, on top of turning near-misses into hits. Aldric's
"+to hit" magic is quietly the most damage-efficient magic in the party, and that is the
argument to make when a storyguide balks at the guideline.

Two corollaries the draft doesn't exploit:

- **Melee Soak has no die.** Compare the combat example: damage total minus a flat Soak. So
  Soak buffs are perfectly reliable — no variance, unlike attack rolls.
- **A botched Defense roll sets the Defense Total to zero**, handing the attacker an Attack
  Advantage equal to their entire Attack Total. Usually fatal. Anything that removes botch
  dice or keeps allies out of desperate defensive rolls is worth more than it looks.

## Spell-design tricks

**1. Stay under magnitude 6 (level ≤ 25) for anything cast on other people.** See §10. This
is the discipline that separates a buff-mage who is welcome in the turb from one whose
grogs sprout Twilight scars.

**2. Diameter, not Sun.** Diameter duration is *"almost exactly two minutes (twenty combat
rounds)"* and costs **one** magnitude. Sun costs two. Twenty rounds covers essentially any
melee. Trading Sun for Diameter saves 5 levels — often exactly the 5 levels that keeps a
spell under the Warping line. Cast it as the enemy comes into view rather than at dawn.

**3. Multiple Casting instead of Target: Group.** Target: Group is +2 magnitudes baked into
the spell forever. The **Multiple Casting** spell mastery ability instead lets you *"cast a
number of additional copies of the spell equal to or less than your Mastery Score"*, all
simultaneously, as a single action. A level 10 Individual buff with Mastery 3 buffs four
people in one action and never approaches magnitude 6. Group is better when you need to
cover ten people at once; Multiple Casting is better in every other respect, and it scales
as he studies. Take the **Mastered Spells** Virtue (50 experience points of mastery) to
seed it.

**4. Moon duration for the campaign, Diameter for the fight.** Moon is +3 magnitudes but
lasts up to a month. Cast the standing buffs at home *in the covenant's +3 aura*, where the
casting total is comfortable, and march out already buffed. Keep the short, expensive stuff
for the moment of contact. (Watch the constant-effect Warping clock if you do this all year.)

**5. Range: Personal for anything on yourself.** It is the only Range that skips your own
Magic Resistance, and it is a full magnitude cheaper than Touch. Every self-buff Aldric owns
should be R: Per if it possibly can be.

**6. Buffing a fellow magus needs Penetration.** Grogs have no Magic Resistance and are free.
A sodalis has Form + 5 × Parma, and *"Penetration Total = Casting Total + Penetration Bonus −
Spell Level"* — so low-level buffs penetrate far better than high-level ones. Another
argument for cheap spells cast many times.

**7. Ceremonial casting for Rituals.** Ritual casting totals add **Artes Liberales +
Philosophiae**. Aldric has Artes Liberales 1 and no Philosophiae — that is 5–10 experience
points buying a permanent bonus to his signature ritual.

**8. Vis boosting.** *"Each pawn of vis expended increases the Casting Score by two"*, capped
at his score in that Art — so up to 17 pawns of Creo. But *"+1 botch die per pawn of vis
used"*, which in a stressful fight is how magi die. Combine with the **Cautious Sorcerer**
Virtue (−3 botch dice) if he plans to do this.

## Character-build tricks

**Strength is a spellcasting stat for an armoured magus.** Encumbrance is Burden minus
Strength, and Encumbrance comes off the Casting Score and Initiative. Aldric sits at Burden
3; going from Str +1 to Str +3 would buy him **+2 casting, +2 Initiative and +2 damage** in
one purchase. Nothing else in the game does that.

Best uses for the two spare Virtue points (and any others the troupe allows):

| Virtue | Cost | Why |
|---|---|---|
| **Method Caster** | Minor Hermetic | *"+3 bonus to the Casting Total of any Formulaic or Ritual spell"*. Flat, permanent, applies to literally everything he casts. The strongest single point in the book for a formulaic caster. Caveat: you lose it if you vary your gestures or voicing, so it doesn't stack with sneaky casting. |
| **Skilled Parens** | Minor Hermetic | *"an additional 60 experience points and 30 spell levels during apprenticeship"*. The best raw value of any Minor Virtue at creation — a 25% bigger apprenticeship for one point. |
| **Improved Characteristics** (again) | Minor General | +3 more Characteristic points. Repeatable. This is how you legitimately pay for the Strength and Stamina that Large doesn't give. |
| **Mastered Spells** | Minor Hermetic | 50 experience points of spell mastery — Mastery also adds to the Casting Score and *subtracts from botch dice*, before you even pick the special abilities. Unlocks Multiple Casting. |
| **Enduring Constitution** | Minor General | *"Decrease the penalties for reduced Fatigue levels by one point, and reduce your total penalty from wounds by one point"*. He is a mage who stands in the line; he will be wounded, and wound penalties hit his casting too. |
| **Affinity with Single Weapon** | Minor General | Turns Warrior's 50 experience points into 75 (Single Weapon 5 at Gauntlet), and *"you may exceed the normal age-based cap… by two points"* — so Single Weapon 8 is reachable at 30 instead of 6. |
| **Cautious Sorcerer** | Minor Hermetic | Three fewer botch dice on every cast and every lab season. Battle-casting is stressful casting. |
| **Self-Confident** | Minor General | Confidence Score 2 and five points instead of three. Confidence is +3 to a roll, and +3 on an Attack roll is +3 damage. |
| **Berserk** | Minor General | *"+2 to Attack and Soak scores, but a −2 penalty to Defense"*, and it grants Martial Abilities at creation. Flatly incompatible with Compassionate in play — *"if you are still berserk when there are no enemies present, you attack your friends"* — which may be exactly the story you want. |

Not available, despite looking tempting: **Great (Characteristic)** requires the score to
*already* be +3, so it cannot lift Strength from +1.

## Tactical tricks in play

- **Armour costs casting, not swinging.** *"in combat, Attack and Defense are not [penalized],
  as long as the Encumbrance is largely due to weapons and armor."* Only Initiative and
  Casting Score suffer. So there is never a reason for Aldric to fight unarmoured — but there
  is a reason to cast his buffs *before* he straps on the harness, at Encumbrance 0.
- **Buff order.** Buffs at Encumbrance 0 in the covenant aura → don harness → cast Parma
  Magica → march. This is worth roughly **+5 to +8** on each buff's casting total compared to
  casting it armoured in the field, and it sidesteps the self-resistance problem entirely.
- **Against archers, only the shield counts.** *"If you are defending against missile weapons,
  only a shield's Defense Bonus adds to your Defense Total."* The heater shield's +3 is the
  whole of his equipment defence at range — don't drop it to free a hand.
- **Wound penalties do not apply to Soak** (*"Soak is not an action"*). A badly wounded Aldric
  is bad at hitting, defending and casting, but just as hard to hurt. Fighting on is
  mechanically sound; it's the Attack rolls that collapse.
- **Fast Caster** gives +3 Initiative on a round he casts *and* +3 to fast-casting speed,
  where the Ease Factor is *"the opponent's Initiative Total"* — a genuine defensive option
  he already owns and the draft never mentions.
- **A Group buff cast on one member reaches all of them**, but *"Things that join the Group
  during the spell duration are not affected"*. Buff after the line forms, not before.
- **Confidence** is 3 points a session at +3 each. On an Attack roll that is +3 damage; spent
  on a Casting Total it can turn a Fatigue-costing cast into a free one.
