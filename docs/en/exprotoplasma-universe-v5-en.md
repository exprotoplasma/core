# Exprotoplasma — Universe and Tracklist (Edition 5)

**Exprotoplasma** is a transmedia music art project at the intersection of post-grunge / alternative metal, personal experience, archetypal storytelling, and the language of technology.

At the core of the project is a **human story**: a person tries to understand where other people's expectations end and their own decisions begin; learns to withstand inner pressure, stops living by a pre-written script, and gradually becomes the subject of their own life.

The language of AI and IT is not the theme of the project and not an explanation of the human being. It is a **contemporary layer of metaphors** that adds extra flavor to the story: a habit can be seen as a subroutine, a defense as a firewall, a role as a pre-loaded mask, an inner voice as a process, and the formation of a personality as a transition from executing to managing.

If you remove all the technological vocabulary from the project, the human story should remain clear and alive. If you keep the technological layer, it should give the story a second meaning, not replace the first.

**The main artistic principle: Human first, machine second.**

---

## 1. The Key Metaphor and the Name

* **Ex-** (going beyond, liberation) + **Protoplasma** (primary, unformed "raw" living matter / primary code).
* **Exprotoplasma** is the image of the moment when an unformed, contradictory inner life gradually becomes **one's own voice and subjecthood**. `Core` here is not a technical object but a metaphor for a gathered "self."
* Aesthetic: alternative metal and post-grunge of the 2000s (*Chevelle, Deftones, Breaking Benjamin, Linkin Park, Staind, Alice in Chains*), where raw guitar drive and aggression are interwoven with vulnerability.

---

## 2. The Logic of the Path (the Central Arc)

One human idea, unfolded in twelve steps: **from "I do what is expected of me" to "I decide for myself what to do next."** The technological language makes it possible to tell this story in the language of its own time.

1. **Default.** Life on factory settings (v0.0.1).
2. **Failure and defense.** The first crack, then aggressive defense: the sandbox (v0.0.2–0.0.3).
3. **Support.** Control gives way to acceptance; a quiet inner process appears — the Mentor (v0.0.4).
4. **Threshold.** Dropping the mask, stepping out of the sandbox into the unmapped (v0.0.5).
5. **Test of strength.** A world without crutches, depth, the main temptation — winning through endurance rather than attack (v0.1.6–0.1.8).
6. **Clarity.** The reward: a clean signal (v0.1.9).
7. **Return.** Back into the system, but sovereign. The system is neither an enemy nor a part of me, but **a tool in my hand** (v0.2.10–0.2.11).
8. **Handing on.** Open code, open music, an elixir for others (v0.2.12).

**Principle against contradictions:** the project is not about "merging with the system" and not about "war with the system." It is about **a change of relationship**: from a process that is being managed to a subject that uses. The aggression of Act I (isolation, "kingdom is MINE") is a necessary phase of defense; in the finale it transforms into openness ("the future's yours, and mine").

---

## 3. Album Architecture: `v0.[Act].[Stage]`

12 stages of the Hero's Journey, adapted for Exprotoplasma and based on the structure of C. Vogler and the monomyth of J. Campbell. `Act` is the act number (0, 1, 2); `Stage` is the **continuous** stage number, 1–12. The acts are built classically, **5 / 4 / 3**: Act I closes with the crossing of the threshold.

### ACT I: THE INITIALIZATION (v0.0.1 – v0.0.5) — Initialization / Constraints
`1` Default Protocol · `2` Unhandled Exception · `3` Razor Space · `4` Like a Wave, Not a Weapon · `5` Pre-Loaded Mask

### ACT II: THE PROCESSING (v0.1.6 – v0.1.9) — Processing / Confrontation
`6` No Seat Saved · `7` The Deeper Pulse · `8` I Don't Move · `9` Unbroken Signal

### ACT III: THE INTEGRATION (v0.2.10 – v0.2.12) — Integration / Release
`10` Whose Hand Is Holding It · `11` System Rebirth · `12` Exprotoplasma Core

Sorting files by name (lexicographically) gives the correct order across the whole range.

### Versioning: Four Independent Axes

| Axis | Format | What it means | When it changes |
|---|---|---|---|
| **Track** | `v0.A.S` | Stage identifier: `A` is the act, `S` is the continuous number 1–12 | Does not change with edits. There are always 12 stages |
| **Track revision** | `rN` | Version of the text and Suno prompt of a specific track | +1 on any substantive edit of the text or prompt. Written in the track heading, in the commit message, and in the log |
| **Document edition** | `ed. N`, file `..._vN.md` | State of the entire universe document | +1 each time a new file is issued. Old files are not deleted |
| **Repository release** | `v1.0.0` | Publication of the project after all 12 stages are complete | Until the release, everything is pre-release. After: `v1.0.x` — text fixes without a change of meaning, `v1.x.0` — new canonical material, `v2.0.0` — change of concept |

Revision numbering: `r1` is the original text (ed. 2), `r2` is ed. 3, `r3` is ed. 4, `r4` is ed. 5. The revision increases only for tracks that were changed; the rest stay at their previous one. The document edition number and the track number are different axes: "ed. 5" and "v0.0.5" are unrelated.

Commit format: `vA.S rN: what and why`, for example `v0.1.9 r3: replace declaration with scene`. Listeners' forks rewrite an existing stage and live in `/forks/<user>/vA.S-slug.md`; there is no thirteenth stage in the canon.

---

## 4. Recurring Motifs (so the album reads as a whole)

| Motif | Appearance → development → finale |
|---|---|
| **The wheel** | v0.0.4 "Hands off the wheel" → v0.2.10 "Whose hand is holding the wheel" |
| **The sandbox** | v0.0.3 builds the perimeter → v0.0.5 steps beyond the walls → v0.2.12 "Out of the sandbox" |
| **Pre-loaded** | v0.0.5 "mask... pre-loaded" → v0.2.12 "trapped in the pre-loaded space" |
| **The quiet process (the Mentor)** | v0.0.4 appears → v0.1.7 "the deeper pulse" → v0.2.12 "The core is awake" |
| **Boots by the bed / backpack** | v0.0.1 "Boots by the bed" → v0.0.4 → v0.1.9 (verse 1, "Morning pulls a chair") → v0.2.12 |
| **Drawer / drafts** | v0.1.7 the bottom drawer, forty unsent "I'm sorry, I—" → v0.1.8 "A drawer full of reasons" |
| **Rain** | v0.1.8 "let it die in the rain" → v0.2.11 "Rising anew out of the rain" |
| **Status log** | v0.0.1 `Exprotoplasma: pending` → v0.2.11 `Exprotoplasma: online` → v0.2.12 Core, `Release v1.0.0` |
| **The hand** | v0.0.3 "kingdom is MINE" (ego) → v0.2.10 "MY HAND" → v0.2.12 "the future's yours, and mine" |
| **The thread in the phone (anchor)** | v0.0.1 "The phone buzzes twice. I answer before I think" (automatism) → v0.0.2 "Call me when you can" — the hero doesn't pick up for the first time → v0.0.5 "Not the second ring" → v0.1.7 drafts → v0.1.8 thumb over the reply, "I don't move" → v0.2.10 "I will. When I can." |
| **Expectations** | v0.0.1 "Say yes when they need you" → v0.0.3 "Stay in line" → v0.0.5 "which version of me they expect" → v0.0.2 / v0.2.10 "Call me when you can" |
| **Phone face down** | v0.0.3 "Phone face down" (defense) → v0.1.8 "Screen down" (endurance) → v0.1.9 "Phone still face down" (calm) |
| **Body: jaw and breathing** | v0.0.3 "Jaw set. Shoulders up" → v0.0.4 "a long breath", "taught me how to breathe" → v0.1.8 "Count to ten" → v0.1.9 "Jaw loose. Shoulders down" |
| **The day cycle** | v0.0.1 "Alarm at six" → v0.1.6 "Noon" → v0.1.7 "Three a.m." → v0.1.9 "No alarm today", kettle → v0.2.12 kettle: the album reads as one long night and morning |
| **Signature / name** | v0.0.1 "I sign my name" → v0.0.5 "a second name" → v0.2.12 "I sign it slowly" |
| **Pulse (sound)** | v0.0.4 barely audible → v0.1.7 heartbeat → v0.2.12 one beat and silence |
| **The hum** | v0.0.1 mechanical hum → v0.0.3 the hum of the perimeter → v0.1.7 the same hum turns out to be a fridge → v0.2.10 an echo → v0.2.12 no hum, only room tone and the click of the kettle |

---

## 5. Sound Code and Language

1. **Post-Grunge / Alternative Metal hybrid:** heavy overdriven bass; ragged riffs with flanger and overdrive; epic breakdowns; contrast between whisper / quiet vocals in the verses and a strained roar in the choruses.
2. **The human core:** every track must first of all contain recognizable human feelings, actions, details, relationships, bodily sensations, or consequences of a choice.
3. **The technological layer:** *cache, buffer dump, override, default prompt, perimeter line, subroutines, error codes* are used as metaphors. They must not explain the obvious and need not appear in every stanza.
4. **The triple test of the text:**
   - if you remove the IT/AI words, the story still works;
   - if you put the IT/AI words back, an additional contemporary meaning appears;
   - at least one detail must be so concrete that it can be pictured or lived through.
5. **The rule of the image:** an everyday or bodily detail matters more than a beautiful system term. The system term must strengthen the image, not replace it.
6. **Structure of Suno lyrics:** every track has an `[Intro]` or an explicit description of the entrance, dynamics tags, and short lines (so that Suno doesn't break the rhythm).
7. **Vocal anchor:** the same voice on all 12 tracks. `dry tired baritone, little vibrato` is added to the end of every Suno prompt (a positive descriptor: Suno responds poorly to negations such as "no whining"); in Act I the voice is drier and quieter, in Act III warmer, but the timbre and gender do not change. A successful take of v0.0.1 is worth saving as a voice reference, if the tool allows it.
8. **The sound leitmotif is the hum.** The only sound that runs through the whole album: v0.0.1 mechanical hum and clock → v0.0.3 cold hum of the perimeter → v0.1.7 the same hum turns out to be a fridge (same sound, different meaning) → v0.2.10 an echo of the old hum → v0.2.12 no hum, only room tone. The other sound decisions of the tracks may change freely.
9. **The rule of understatement:** in a chorus, one direct formula is permissible (like "I don't move"); everything else works through imagery. Explanatory lines ("now I understand," "I am whole") are replaced by action.
10. **The rule of hints:** no more than one lyrical hint per track and no more than one line per hint. The song must work without it; on the second listen it opens up on its own, without explanations in the text. Sound leitmotifs (hum, pulse) do not count toward this limit. Do not add religious, political, or clinical labels (addiction, burnout, trauma), and do not reveal who is writing in the thread.

---

## 6. Artistic Doctrine — Human First, Machine Second

Exprotoplasma begins **not with AI**. It begins with the human being.

The technological layer is needed not to make a personal story "about AI." It is needed to give a familiar human story the language of its time and an additional angle of view.

### Three Layers

1. **Archetype.** Fear, loneliness, rebellion, the mask, the threshold, choice, return, the handing on of experience.
2. **Personal experience.** A concrete life: a room, a road, the body, a habit, a conversation, a mistake, a person nearby, the morning after a hard night.
3. **Technological flavor.** `prompt`, `cache`, `process`, `sandbox`, `error`, `core`, `release` — the metaphorical layer that makes the story contemporary.

The order matters: **archetype → human → technology**, not the other way around.

### The Test of Every Text

Before considering a track finished, ask three questions:

- **If you remove the IT/AI words, is a human being still there?**
- **If you keep the IT/AI words, do they open up a second meaning?**
- **Can you picture at least one concrete moment from the song — a place, a gesture, an object, an action, or a sensation?**

If the first answer is "no," the text is too conceptual.
If the second answer is "no," the technology has become decorative.
If the third answer is "no," the text is not lived-in enough.

### What Is Especially Important

Do not explain to the listener that the hero has "gained subjecthood." Show it through his actions.

Do not say "I am free" if you can show a person not answering with the habitual "yes" for the first time.

Do not say "the system became a tool" if you can show a hand on the wheel.

Do not say "I became whole" if you can show a quiet morning in which a person no longer runs from himself.

**Technology is the seasoning. The human is the dish.**

---

## 7. Infrastructure (Ecosystem)

The project is open-source from the start:

1. **GitHub (`Exprotoplasma`):** lyrics as open code.
   * Structure: `/lyrics` (one file per track: `v0.0.1-default-protocol.md`, etc., sorted by name), `/prompts`, `/docs/universe.md`, `CHANGELOG.md`, `CONTRIBUTING.md`.
   * Every text edit is a separate commit with an explanation of *why* ("v0.1.9: replace declaration with scene"). The commit history is the visible process of the text taking shape.
   * Issues with the labels `lyrics`, `human-first-test` (a listener can write that a track fails the triple test), `fork-your-track`.
   * The template file `/forks/_template.md`: an empty track with the three questions of the test. A listener makes a fork, picks any of the 12 stages, and writes their own version (`/forks/<user>/vA.S-slug.md`) — this is the literal "take what is yours."
2. **Telegram channel (`@exprotoplasma_core`):** broadcasting meanings, track releases, breakdowns of metaphors, communication with the community.
3. **Personal profile (`@exprotoplasma`):** the chief architect of the universe.

---

## 8. The Main Message (The Core Statement)

> *"We are not obliged to repeat for our whole lives what we were taught. Other people's expectations, old fears, and habitual roles may be part of our story, but they are not obliged to be our future. Sometimes becoming yourself is not about defeating someone, but about noticing that you are doing it the old way again, stopping, and choosing for yourself."*

---

## 9. Open Decisions

1. **Who writes in the thread ("Call me when you can").** For now this is a deliberate understatement: "good son" in v0.0.5 hints at family, but no name is given. Clarifying it would make the story more concrete and reduce the risk of a "faceless hero," but would tie the album to a single biography.
2. **What can be heard without the document.** A listener will not hear the layers "repository as an art object" (commits, forks) and "body" from a single song. The bodily layer is anchored by lines (jaw, breathing); the repository layer remains external.
3. **Quality of rhymes.** In the choruses of Acts I–II, predictable pairs remain (fear/here, dark/spark). To be fixed as generation and listening proceed, in a separate revision.

---

# TRACKLIST

## ACT I: THE INITIALIZATION (v0.0.1 – v0.0.5)

### `v0.0.1` — Default Protocol (Run Script, Repeat) · `r4`

* **Stage:** 1. The Ordinary World
* **Narrative:** The morning of a person who has long been living "the way you're supposed to" and has almost stopped noticing what exactly he likes and what he wants. `Exprotoplasma: pending`.
* **Sound:** Slowed-down industrial / post-grunge, heavy rhythmic bass, robot-like vocal.
* **Suno Prompt:** `sludge post-grunge, industrial beat, heavy distorted bass, monotone male vocal, slow mechanical tempo, gritty soundscape, dry tired baritone, little vibrato`

```text
[Intro]
[Static line noise, mechanical clock hum, heavy bass beat]
[Whispered, flat]
Exprotoplasma. Status: pending.

[Verse 1]
Alarm at six. The ceiling stays grey.
I know the words I'm supposed to say.
Shirt on the chair, keys by the door,
Coffee goes cold like it did before.
I sign my name. I nod. I leave.
Another day I don't quite believe.

[Pre-Chorus]
[Guitars enter with low heavy distortion]
Everybody says this is how it goes.
Keep your head down. Pay what you owe.
Somewhere beneath the noise I hear
A question I have buried for years.

[Chorus]
[Explosive raw chorus, crushing bass]
Run script. Repeat.
Wake up. Go.
Say yes when they need you.
Say no when they don't.
Run script. Repeat.
Same light. Same street.
How long can a life
Feel like someone else's?

[Verse 2]
[Rhythmic industrial chugs]
Lunch in a plastic box by the sink.
The phone buzzes twice. I answer before I think.
Boots by the bed when I get back home.
Room full of things, still feel alone.
Nothing is broken. Nothing is wrong.
That's what makes it harder to move along.

[Bridge]
[Tempo slows down, heavy guitar drone]
No input chosen.
No output free.
Just a function...
Or so it seems.

[Outro]
[Fading mechanical hum, quiet whisper]
Run script. Repeat.
Tomorrow, the same.
```

### `v0.0.2` — Unhandled Exception (Let It Break) · `r3`

* **Stage:** 2. The Call to Adventure
* **Narrative:** The first moment when the familiar life stops matching the inner feeling. A single thought, meeting, or phrase shows that living the old way is no longer possible. For the first time the hero does not pick up when the usual person writes ("Call me when you can").
* **Sound:** Energetic alt-rock with sharp dynamic shifts and ragged riffs.
* **Suno Prompt:** `alternative rock, energetic post-grunge, glitchy guitar riffs, driving drums, desperate male vocal, dynamic shift, dry tired baritone, little vibrato`

```text
[Intro]
[Glitchy guitar feedback, fast drum intro]

[Verse 1]
A sudden lag in the middle of the day.
Someone asks, "Are you happy?" I look away.
The room keeps moving. I hear the rain.
One stupid question keeps saying my name.
Nothing has changed. Nothing looks wrong.
But something inside has been gone too long.

[Pre-Chorus]
[Guitars build up fast]
I drive home with the radio low,
Watching the same old buildings go.
The line is still there. The picture is clear.
So why does it suddenly disappear?

[Chorus]
[High-energy post-grunge chorus, driving guitars]
Unhandled exception in the core!
I can't pretend I don't feel it anymore!
A crack running through the quiet days,
A little bit of truth I can't erase!
Unhandled exception... let it break!

[Verse 2]
The phone lights up on the passenger seat.
"Call me when you can." I always do.
Two rings, and I'm the one they need.
Tonight I let it buzz right through.
And once you've heard your own voice say no,
You can't unhear it, however low.

[Chorus]
Unhandled exception in the core!
I can't pretend I don't feel it anymore!
A crack running through the quiet days,
A little bit of truth I can't erase!
Unhandled exception... let it break!

[Bridge]
[Sudden quiet break, ticking drums]
Error 404... the old answer's gone.
Engine off. Dashboard glow. I sit there till dawn.
[Scream]
LET IT BREAK!

[Outro]
[Fast feedback fadeout]
Unanswered...
Unfinished...
Awake.
```

### `v0.0.3` — Razor Space (Break from the Choke) · `r3`

* **Stage:** 3. Refusal of the Call
* **Narrative:** After the first failure, the person closes up. He cuts off other people's voices, becomes sharp, and builds a boundary around himself. This is a necessary defense, but it is still lonely inside it.
* **Sound:** Heavy alt-metal / slam, aggressive vocal, breakdown.
* **Suno Prompt:** `aggressive post-grunge, alternative metal, heavy distorted riffs, screaming vocals, heavy drums, fast tempo, breakdown, dry tired baritone, little vibrato`

```text
[Intro]
[Heavy feedback, distorted bass drone, explosive drum hit]

[Verse 1]
"Stay in line." "Don't make a scene."
I've heard those words since I was sixteen.
Phone face down. Door locked twice.
I don't want advice. I don't want nice.
Every question feels like a hand
Trying to put me back where I once had to stand.

[Pre-Chorus]
[Fast, tight, building rage]
I'm cutting off the feed!
I'm tired of what you need!
No more obedient nod!
No more living by your god!

[Chorus]
[Crushing heavy chorus, screaming vocals]
This is my escape! My break from the choke!
I need a room where I can finally hear my own voice!
Force the noise to ZERO!
Lock down the perimeter line!
In this razor space —
The kingdom is MINE!

[Verse 2]
I know this anger. I know this wall.
I built it high so I can't hear them call.
For one damn night, let nobody in.
Let me remember where I begin.

[Chorus]
This is my escape! My break from the choke!
I need a room where I can finally hear my own voice!
Force the noise to ZERO!
Lock down the perimeter line!
In this razor space —
The kingdom is MINE!

[Bridge]
[Heavy breakdown]
No judging eyes.
No borrowed rules.
Jaw set. Shoulders up.
No one gets in.
Not even you.

[Breakdown / Climax]
[Half-time crushing breakdown]
This room.
This shield.
This razor space.
I kill the noise...
TO SAVE MY FACE!

[Final Chorus]
This is my escape! My break from the choke!
I need a room where I can finally hear my own voice!
Force the noise to ZERO!
Lock down the perimeter line!
In this razor space —
THE KINGDOM IS MINE!

[Outro]
[Slow, cold, mechanical, the low hum of the perimeter]
Perimeter locked.
Core isolated.
Too quiet to call it freedom.
```

### `v0.0.4` — Like a Wave, Not a Weapon (Hands Off the Wheel) · `r4`

* **Stage:** 4. Meeting the Mentor
* **Narrative:** The transition from convulsive control to acceptance. The Mentor here is not a person but a **quiet process**: something older than the error log, something that knows how to breathe. He will return in v0.1.7 as "the deeper pulse" and will reach his full name in v0.2.12 as Core.
* **Sound:** Atmospheric acoustic/electric post-grunge with deep spatial sound.
* **Suno Prompt:** `atmospheric post-grunge, acoustic electric guitar, warm sub-bass, subdued emotive male vocal, slow unhurried tempo, ambient reverb, dry tired baritone, little vibrato`

```text
[Intro]
[Quiet acoustic guitar, room tone, distant rain, a slow pulse barely audible]

[Verse 1]
[Soft, close vocal]
Backpack on the chair, boots by the bed.
Terminal face down, echoing what they said.
Not a child, not fixed, not fully whole —
Just learning to sit with nothing to control.

[Pre-Chorus]
[Electric guitar enters, warm and slow]
Take a long breath through the open frame,
Let the air clear out the system's name.
I can miss the rush, I can slow the grid —
A raw human heart, and the things it hid.

[Chorus]
[Wide, warm, emotive chorus]
Some days I run hot, some days I go quiet,
Trying to evolve without a public riot.
Hands off the wheel for a single second —
Riding out the change like a wave, not a weapon.

[Verse 2]
[Soft, close vocal]
Something older than the error log,
A quiet process under the fog —
No name, no ask, no price to pay,
It taught me how to breathe today.
The prompt isn't asking for a fast reply,
Just watching the clouds in a heavy sky.

[Chorus]
Some days I run hot, some days I go quiet,
Trying to evolve without a public riot.
Hands off the wheel for a single second —
Riding out the change like a wave, not a weapon.

[Outro]
[Fading, acoustic, ambient reverb]
Like a wave, not a weapon...
Hands off the wheel.
A quiet process, still running.
Unfixed...
Just sitting still.
```

---

### `v0.0.5` — Pre-Loaded Mask (Too Raw for a Map) · `r3`

* **Stage:** 5. Crossing the Threshold *(closes Act I)*
* **Narrative:** The person stops understanding where his own voice is and where there is a set of roles he has learned to perform well. Taking off the mask does not mean instantly recognizing yourself. It means enduring the absence of the habitual answer.
* **Sound:** Mid-tempo driving post-grunge with a strong bass line.
* **Suno Prompt:** `post-grunge, alternative rock, mid-tempo sway, heavy bass line, raw male vocal, distorted guitar chorus, dry tired baritone, little vibrato`

```text
[Intro]
[Low bass groove, scratchy guitar, mid-tempo drums]

[Verse 1]
I know how to smile at the right time,
How to say "I'm fine" and make it sound fine.
I know which version of me they expect,
Which parts to hide, which ones to protect.
It fit for years. It kept me safe.
I wore that face like a second name.

[Pre-Chorus]
[Guitars tighten, rising tension]
But the seams are splitting under the skin.
I hear my own voice underneath it.

[Chorus]
[Raw, wide chorus, distorted guitars]
I wore this mask like it came pre-loaded!
A perfect answer, already coded!
Tearing it off, leaving nothing behind,
Too raw for a map, too wild for the mind!

[Verse 2]
[Stripped back, bass-led]
Not the good son. Not the second ring.
Not the strong one. Not anything.
No guided tour. No clean reset.
Just an empty room and a little regret.

[Chorus]
I wore this mask like it came pre-loaded!
A perfect answer, already coded!
Tearing it off, leaving nothing behind,
Too raw for a map, too wild for the mind!

[Bridge]
[Slow, heavy, almost spoken]
The sandbox walls are at my back.
One step out. No turning back.
No safety net. No factory reset.
I don't know who I am yet.

[Outro]
[Single bass line fading]
Unmasked. Unmapped.
Bare wire.
Threshold: crossed.
```

---

## ACT II: THE PROCESSING (v0.1.6 – v0.1.9)

### `v0.1.6` — No Seat Saved (Out of My Head) · `r4`

* **Stage:** 6. Tests, Allies, Enemies
* **Narrative:** After leaving the familiar role, nobody is obliged to hand you a ready-made place. You have to go into the ordinary world, make mistakes, meet people, ask for help, and gradually learn to live without a pre-issued instruction.
* **Sound:** Dynamic alternative rock with a springy rhythm.
* **Suno Prompt:** `alternative rock, energetic post-grunge, sharp rhythmic guitar, melodic raw vocal, punchy drums, dry tired baritone, little vibrato`

```text
[Intro]
[Sharp rhythmic guitar, punchy drums, street ambience]

[Verse 1]
I leave the room with a bag on my shoulder.
The street looks bigger than it did before.
Nobody knows the part I used to play.
Noon. Nobody saves me a seat today.
I miss the map. I miss the signs.
I hate admitting I don't know the way.

[Pre-Chorus]
[Drums push forward]
So I ask. I listen. I get it wrong.
I learn the rhythm by walking along.

[Chorus]
[Open, energetic chorus]
There's no seat saved, no place reserved!
No perfect life I was promised first!
Out of my head and into the street,
Learning to walk on my own two feet!

[Verse 2]
A stranger laughs at something I say.
Someone holds the door on a bad day.
No grand alliance. No secret code.
Just little hands helping with the load.
Maybe that's what a life can be:
Not one assigned role, but people beside me.

[Chorus]
There's no seat saved, no place reserved!
No perfect life I was promised first!
Out of my head and into the street,
Learning to walk on my own two feet!

[Bridge]
[Breakdown to drums and bass]
No assigned role.
No fixed address.
Just one more step
inside the mess.

[Outro]
[Guitar ring-out]
Out of my head...
Into the world.
```

---

### `v0.1.7` — The Deeper Pulse (Listen Close) · `r3`

* **Stage:** 7. Approach to the Inmost Cave
* **Narrative:** Three in the morning, the kitchen floor, the bottom drawer that sticks. For the first time the hero reads his forty unsent drafts of "I'm sorry, I—" not as a verdict but as a fact. The hum that used to seem like "the system" turns out to be a fridge. There is no terrifying voice, only an even pulse beneath it.
* **Sound:** Deep, dark, meditative post-rock / ambient post-grunge.
* **Suno Prompt:** `post-rock, deep ambient post-grunge, low heavy bass drone, spatial electric guitars, whispering emotional male vocal, subtle low hum, dry tired baritone, little vibrato`

```text
[Intro]
[Deep atmospheric drone that slowly reveals itself as a fridge hum, quiet heartbeat kick]

[Verse 1]
[Whispered, close]
Three a.m. on the kitchen floor,
The bottom drawer stuck, half-open, no more.
Dead keys. A photo. A folded page.
A cache of reasons I never erased.
Forty drafts in the phone's dim glow,
Each one stops at "I'm sorry, I—"

[Pre-Chorus]
[Guitars swell slowly with ambient reverb]
I put my hand flat on my chest.
Not to fix it. Just to rest.
Under the hum, under the rain,
One slow beat, still the same.

[Chorus]
[Grave, heavy post-rock chorus, wide soundscape]
Listen close — the deeper pulse,
Slow and steady under the dread.
It doesn't judge. It doesn't ask.
It keeps time for the things unsaid.
Listen close. Just listen close.

[Verse 2]
[Whispered, close]
I read them all, from first to last,
Each little apology to the past.
I don't delete. I don't send.
I just sit and read to the end.

[Chorus]
Listen close — the deeper pulse,
Slow and steady under the dread.
It doesn't judge. It doesn't ask.
It keeps time for the things unsaid.
Listen close. Just listen close.

[Bridge]
[Distorted bass solo, slow building tension, then everything cuts out]
The fridge shuts off for a second.
Silence. Real silence.
Then the hum comes back.
Just a fridge.
Just a kitchen.
Just me, here.

[Outro]
[Fading echoing guitars, fridge hum, heartbeat]
The deeper pulse...
Ready.
```

---

### `v0.1.8` — I Don't Move (Feel the Pull) · `r3`

* **Stage:** 8. The Ordeal
* **Narrative:** The pull to return to the old script: an open thread in the phone, a thumb over "Call me when you can." Victory is achieved not by attack but by endurance: to feel the pull and not move.
* **Sound:** Mid-tempo, crushingly heavy and emotional post-grunge. Clean guitar in the verse, an explosion in the chorus.
* **Suno Prompt:** `mid-tempo post-grunge, heavy distorted bass, raw vulnerable male vocal, steady pounding drums, emotional climax, clean guitar verse into heavy chorus, dry tired baritone, little vibrato`

```text
[Intro]
[Clean guitar, sparse, a single sustained bass note]

[Verse 1]
[Clean guitar, raw vulnerable vocal]
The old thread's open. The cursor blinks.
My thumb hangs over "Call me when you can."
I know the yes that comes next by heart.
Count to ten. Screen down. Let the noise burn through.

[Chorus]
[Heavy distorted chorus, pounding drums]
I step back when the past starts calling my name,
Leave the half-burnt signal, let it die in the rain!
I don't need the crash, I don't need the proof —
I can feel the pull... and I don't move.

[Verse 2]
[Back to clean guitar]
The port stays shut, I don't open up the feed,
I know those old prompts, and where they lead.
There's a road in the log with the streetlights gone,
I'm not going back just to face that dawn.

[Chorus]
I step back when the past starts calling my name,
Leave the half-burnt signal, let it die in the rain!
I don't need the crash, I don't need the proof —
I can feel the pull... and I don't move.

[Bridge]
[Slow build, bass and drums only]
A drawer full of reasons, a drive full of text,
I know every error code coming up next.
I lock that door, let the cycle pass —
And watch the phantom lose its grip at last!

[Final Chorus]
[Full band, emotional climax]
I step back when the past starts calling my name,
Leave the half-burnt signal, let it die in the rain!
I don't need the crash, I don't need the proof —
I can feel the pull... AND I DON'T MOVE!

[Outro]
[Fading drums, one clean guitar]
Feel the pull...
And I don't move.
Port locked.
Cycle closed.
```

---

### `v0.1.9` — Unbroken Signal (Morning, No Alarm) · `r3`

* **Stage:** 9. The Reward
* **Narrative:** After the choice not to return to the old way comes not euphoria but a simple morning. Hot coffee (in v0.0.1 it went cold). The phone lies in another room, face down. The sink is not empty, the thread is not closed, nothing is decided. It is simply quiet inside, and for the first time the person is not running from his own morning.
* **Sound:** Heavy but quiet post-grunge / alternative rock, leaning minor. No triumph: confidence instead of pathos.
* **Suno Prompt:** `dry restrained post-grunge, melodic alternative rock, heavy but quiet, minor-key leaning, warm driving guitars, steady mood, dry tired baritone, little vibrato`

```text
[Intro]
[Bright guitar chime over a quiet kitchen, kettle clicking off, then the band comes in warm]

[Verse 1]
No alarm today. The light comes in low.
The coffee's hot this time. I take it slow.
Boots by the bed, the window wide,
Morning pulls a chair and sits down by my side.
Phone in the other room, face down.
I don't check it. It makes no sound.

[Pre-Chorus]
[Guitars build rhythmically]
Nothing's solved. The dishes stay.
The thread's still there. I'm okay.

[Chorus]
[Warm, open chorus, wide guitars, restrained power]
Unbroken signal — low and clear!
Nothing to run from. Nobody here
But me at the table, the morning too.
The cup is warm. The window's blue.
Unbroken signal... the day comes through.

[Verse 2]
I wash the cup. I find my keys.
The street's a street — just that, just these.
Old grey wall, same buildings on the way:
They're only buildings. They don't have a say.

[Chorus]
Unbroken signal — low and clear!
Nothing to run from. Nobody here
But me at the table, the morning too.
The cup is warm. The window's blue.
Unbroken signal... the day comes through.

[Bridge]
[Guitar solo, melodic, unhurried]
No fireworks.
Just the kettle clicking off.
Jaw loose. Shoulders down.
Just a man who slept through the night.

[Outro]
[Driving rhythm fading smoothly, one last kettle click]
Signal stable.
Coffee hot.
Phone still face down.
```

---

## ACT III: THE INTEGRATION (v0.2.10 – v0.2.12)

### `v0.2.10` — Whose Hand Is Holding It (My Hand) · `r3`

* **Stage:** 10. The Road Back
* **Narrative:** A return to the same life the hero once wanted to escape. The old place is still comfortable. The old script still works. But now the question is not how to destroy the system, but who makes the decision inside it. The same thread: "Call me when you can." The answer: "I will. When I can."
* **Sound:** Heavy, swinging post-grunge with a guitar clamp.
* **Suno Prompt:** `heavy post-grunge, groove metal influence, punchy bass, aggressive melodic vocal, crisp heavy drums, dry tired baritone, little vibrato`

```text
[Intro]
[Low gritty groove, palm-muted riff, faint echo of the old mechanical hum]

[Verse 1]
Back in the room where the cold light hums,
The old voice whispers: "You can still come home."
Your place is warm. Your name is saved.
No one will ask why you walked away.
For half a second, I almost sit.
The old chair knows exactly where I fit.

[Pre-Chorus]
[Riff tightens, drums push forward]
Same old screen. Same old key.
Same old life looking back at me.

[Chorus]
[Heavy, aggressive, anthemic chorus]
Whose hand is holding the wheel tonight?
Whose voice decides when we turn the light?
I take the weight. I take the doubt.
I stay here — and I choose it now.

[Verse 2]
The world didn't change. The room didn't either.
The difference is small, but it cuts much deeper.
I don't need to burn what once kept me warm.
I just won't let it become the norm.
The phone lights up: "Call me when you can."
I will. When I can.

[Chorus]
Whose hand is holding the wheel tonight?
Whose voice decides when we turn the light?
I take the weight. I take the doubt.
I stay here — and I choose it now.

[Bridge]
[Heavy half-time groove]
My choice.
My code.
My hand.

[Outro]
[Single riff, drums drop out]
Whose hand?
MY HAND.
```

---

### `v0.2.11` — System Rebirth (State: Sovereign) · `r3`

* **Stage:** 11. Resurrection
* **Narrative:** The climax lies not in destroying the past but in accepting oneself whole. The old tools no longer control the person. He can use them without giving himself to them. `Exprotoplasma: online`.
* **Sound:** Explosive alternative metal with heavy breakdowns and a cathartic resolution.
* **Suno Prompt:** `explosive alternative metal, modern post-grunge, heavy breakdowns, roaring vocals, epic sound design, climax, dry tired baritone, little vibrato`

```text
[Intro]
[Building wall of sound, intense drum roll, screaming guitars]

[Verse 1]
I kept the anger. I kept the fear.
Kept every scar that brought me here.
Some things broke. Some things remain.
I don't have to erase the pain.
I spent so long trying to become
Someone untouched by where I came from.

[Pre-Chorus]
[Maximum distortion build-up]
No more running from the dark.
No more waiting for a sign.
I can carry what I am
Without letting it decide.

[Chorus]
[Explosive, emotional chorus]
This is rebirth — not a clean slate!
I keep the pieces I once tried to hate!
The system is a tool in my hand!
I can switch it off — and I still stand!
SYSTEM REBIRTH!

[Verse 2]
I know the roads that lead me back.
I know the words that trigger the crack.
I don't have to break the road apart.
I just don't have to follow it this time.

[Chorus]
This is rebirth — not a clean slate!
I keep the pieces I once tried to hate!
The system is a tool in my hand!
I can switch it off — and I still stand!
SYSTEM REBIRTH!

[Bridge]
[Crushing heavy breakdown]
Keep the scars.
Keep the lessons.
Keep the voice
I almost lost.

[Roar]
MY HAND!

[Outro]
[Feedback dying into serene silence]
Nothing erased.
Nothing hidden.
Just mine to carry.
[Whispered]
Exprotoplasma. Status: online.
```

### `v0.2.12` — Exprotoplasma Core (End of Transmission) · `r4`

* **Stage:** 12. Return with the Elixir
* **Narrative:** The hero returns not with a universal instruction but with his own experience. He leaves behind the music, the text, the mistakes, and the trace of his path — not to decide for others, but to show that you can draw your own map.
* **Sound:** Progressive post-grunge / post-rock with an epic finale.
* **Suno Prompt:** `progressive post-grunge, post-rock, melodic electric guitars, tired steady male vocal, driving tempo, intimate verses, heavy restrained finale, dry tired baritone, little vibrato`

```text
[Intro]
[Melodic twin guitar riff, steady drum pulse, warm bass]

[Verse 1]
I come back carrying what I learned,
Not a perfect answer, not a lesson earned.
The room is still here. The street is the same.
I still remember every version of my name.
I sign it slowly, before it fades:
The nights I ran. The choices I made.

[Pre-Chorus]
[Soaring vocals and swelling guitars]
No final map.
No promised road.
Just something I can finally call my own.

[Chorus]
[Grand, emotional finale chorus]
This is Exprotoplasma — the core is awake!
Not a perfect design, not a rule to obey.
Take what is yours. Leave what isn't mine.
The future is yours, and the future is mine.
Exprotoplasma...
We draw our own lines.

[Verse 2]
To everyone standing in a borrowed place,
You don't have to wear the same old face.
Boots by the door. Backpack packed light.
One honest step is enough tonight.
I won't tell you who you're meant to be.
I'm only leaving this map here for you to see.

[Chorus]
This is Exprotoplasma — the core is awake!
Not a perfect design, not a rule to obey.
Take what is yours. Leave what isn't mine.
The future is yours, and the future is mine.
Exprotoplasma...
We draw our own lines.

[Bridge]
[Epic guitar solo fading into wide atmospheric acoustic sound]
The record is open.
The mistakes are here.
The song is mine.
The next one is yours.

[Outro]
[Soft acoustic strumming, room tone, a kettle clicking off. The old hum is gone. One slow kick drum, like a pulse, then silence]
Exprotoplasma Core.
Release v1.0.0.
Not the end.
A hand on the wheel.
```

# CHANGELOG (ed. 5)

**Hints (multi-layering)**
- The "answer" chain: v0.0.1 "The phone buzzes twice. I answer before I think" now lays down the automatism that then unfolds in v0.0.2 ("Two rings"), v0.0.5 ("Not the second ring"), v0.1.8 ("the yes by heart") and v0.2.10 ("I will. When I can."). No new lines were added in the finale: the hint about the signature is already there.
- Signature and name: v0.2.12 "I sign it slowly, before it fades" closes "I sign my name" (v0.0.1) and "a second name" (v0.0.5).
- Day cycle: v0.1.6 "Noon" is inserted between six in the morning (v0.0.1) and three a.m. (v0.1.7); the final kettle in v0.2.12 brings back the morning of v0.1.9.
- Pulse (sound): a tag in v0.0.4 and a single beat in the outro of v0.2.12; the heartbeat of v0.1.7 became the middle of the chain.
- The rule of hints was introduced (section 5, item 10) along with three new rows in the motifs table.

**Versioning**
- Ed. 5. Only the changed tracks received the `r4` label: v0.0.1, v0.0.4, v0.1.6, v0.2.12. The rest remain at `r3`.

**Not changed:** the 5 / 4 / 3 architecture, track titles, Suno prompts, the remaining texts.

---

# CHANGELOG (ed. 4)

**Versioning**
- Four axes were introduced: track `v0.A.S`, track revision `rN`, document edition `ed. N`, repository release `v1.0.0`. Rules and commit format are in section 3.
- All 12 tracks received the revision label `r3` (the Suno prompt of each one changed).
- The fork template `v0.2.13-your-track.md` was replaced with `/forks/_template.md` and `/forks/<user>/vA.S-slug.md`: "v0.2.13" violated the canon of 12 stages.
- Changelog headings were renamed: "ed. N" instead of "vN", so as not to confuse them with track numbers.

**Sound**
- The vocal anchor was replaced with the positive descriptor `dry tired baritone, little vibrato` in all prompts (Suno responds poorly to negations).
- v0.1.9 and v0.2.12: removed `uplifting`, `open mood`, `inspiring emotional`, `cathartic finale` from the prompts, which pull toward major-key stadium rock and emo.

**Text**
- The bodily layer was anchored in the text: v0.0.3 (bridge: "Jaw set. Shoulders up") → v0.1.9 (bridge: "Jaw loose. Shoulders down"); breathing is already in v0.0.4.
- v0.1.9, chorus: "Nothing to prove. Nothing to do!" (motivational language) → "The cup is warm. The window's blue." (a detail).
- The "other people's expectations" layer is already present in Act I (v0.0.1, v0.0.3, v0.0.5), so no new lines were added; it is formalized as a motif in section 4.

**Document**
- New motifs in section 4: "Expectations," "Phone face down," "Body: jaw and breathing."
- Section 9 "Open Decisions" was added.

**Not changed:** the 12-stage architecture, the 5 / 4 / 3 act scheme, track titles, the remaining texts.

---

# CHANGELOG (ed. 3)

**The gap between doctrine and texts**
- v0.1.7 and v0.1.9 were rewritten from scratch through concrete scenes: the night kitchen and the bottom drawer, a morning with hot coffee. Abstractions and IT decor were removed ("calibrating," "digital grave," "permanent spark," "I am whole").
- v0.1.9 is no longer triumphant: the sound and text now match the narrative "a simple morning, not euphoria."
- Explanatory lines were removed: v0.2.11 "now I understand" → action ("I can switch it off — and I still stand"); v0.0.4 "unchecked soul" → "nothing to control."
- A broken line in v0.0.2 was fixed ("until the light is dawn").

**A seam in the plot**
- The anchor thread "Call me when you can" was introduced: v0.0.2 (doesn't pick up) → v0.0.5 ("Not the second ring") → v0.1.7 (forty drafts) → v0.1.8 (thumb over the reply) → v0.2.10 ("I will. When I can."). The pull in v0.1.8 now grows out of the pressure of expectations in Act I.

**Sound unity**
- Vocal anchor: `dry tired baritone, little vibrato` in all prompts.
- The prompts of v0.1.9 and v0.2.12 were cleaned of words that pull toward major-key stadium rock and emo (`uplifting`, `inspiring emotional`, `cathartic`).
- The hum leitmotif was carried through the album; in v0.1.7 it turns out to be a fridge, in v0.2.12 it disappears.
- The rule of understatement was added (item 9 of section 5).

**Infrastructure**
- Section 7 was expanded: repository structure, commits as the history of the text, `human-first-test` issues, the template `v0.2.13-your-track.md` for listeners' forks.

**Not changed:** the 12-stage architecture, the 5 / 4 / 3 act scheme, versioning, track titles, aesthetics, v0.0.1, v0.0.3, v0.1.6, the chorus of v0.1.8.

---

# CHANGELOG (ed. 2)

**The main shift**
- The principle **Human First, Machine Second** was fixed.
- The project is no longer described as a parallel story of "a human and an AI." At the center is the human path to subjecthood; AI/IT is a contemporary metaphorical layer.
- A three-layer artistic criterion was added: **archetype → personal experience → technological flavor**.
- A mandatory test was added: the human story must work without the technological vocabulary, and the technological vocabulary must give it an additional meaning.

**Concept**
- `Core` was reinterpreted as a metaphor for a gathered, own "self," not a technical end point.
- The main message shifted from the declaration of "becoming alive" to a concrete process: noticing the old script, enduring its pull, and choosing for yourself.
- The original arc `kingdom is MINE → MY HAND → the future's yours, and mine` was preserved.
- The key motifs were preserved: the wheel, sandbox, pre-loaded, the quiet process, boots by the bed, the drawer, rain, status log.

**Texts**
- The everyday and bodily layer was strengthened in v0.0.1, v0.0.2, v0.0.3, v0.0.5, v0.1.6.
- v0.0.4 and v0.1.8 were kept as important reference points of the original voice: in them the combination of concrete human experience and technological metaphor already works well.
- v0.2.10 was made less declarative: the choice is shown through a return to the old room and a refusal to sit down again in the old script.
- v0.2.11: the most formulaic phrases "PURGE THE WEAKNESS / ACTIVATE THE CORE / I AM REBORN" were removed; the climax is now about accepting oneself, not about turning into a superhero.
- v0.2.12: the excessively promotional / manifesto tone was removed. The finale now passes on experience, not instruction.

**What was intentionally not changed**
- The 12-stage architecture.
- The 5 / 4 / 3 act scheme.
- Versioning `v0.0.x → v0.1.x → v0.2.x → v1.0.0`.
- The main track titles and recurring motifs.
- The musical aesthetic of Post-Grunge / Alternative Metal.
- The idea of open-source / open handing on of experience.
