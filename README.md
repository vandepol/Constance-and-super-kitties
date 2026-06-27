# 🐾 Constance & the Super Kitties

A bright, superhero kitty game made for **Constance**, starring **Ginny** and
**Bitsy** — two little kitties who become Super Kitties! 🦸🐱

## How to play

1. Open **`index.html`** in any web browser (just double-click it).
2. **Pick your kitty** — **Ginny** (orange) or **Bitsy** (white) — and press **▶ Play**.
3. Exciting hero music plays — tap the **🔊** button to turn sound on/off.

### Controls (keyboard or touch — no microphone needed)

| Do this | What happens |
| --- | --- |
| **Arrow keys** ← ↑ ↓ → (or **W A S D**) | move your kitty |
| **SPACE bar** (or the 🧶 button) | **throw yarn** to slow down the baddie |
| **On-screen buttons** ▲ ◀ ▶ ▼ | move on a tablet / touch screen |

## 🐟 Level 1 — The Cavern

Ginny & Bitsy are still **regular kitties** (no costumes yet). Catch **cat treats**
to fill your **basket** — you'll see it fill up at the bottom of the screen! Gold
treats are worth **3**.

A sneaky **Cat Burglar** (a black, grey and white cat with a robber mask and a
swag bag) wants the treats too. Press **SPACE** to throw **yarn** and slow her
down, then grab the treats before she does.

**Fill the basket → the kitties SUIT UP into Super Kitties** and zoom to Level 2!

## 📦 Level 2 — Kitty Land

**Mr. Puppy Paws** (a brown-and-white dog with fluffy ears and a white stripe down
his face) is trying to **steal all the cat toys**! This is a **trapping** level:

- Walk into the **wooden crates** to **push** them around.
- Build walls with the crates to **box Mr. Puppy Paws in** and **trap** him.
- Throw **yarn** (SPACE) to slow him down while you wall him off.
- Keep the **cat toys** safe — trap him before he grabs them all!

Trap him and you **win** and save Kitty Land. 🎉

## 🦸 The two kitty heroes

- **Ginny** — orange kitty → **pink** suit, **blue** boots/gloves/belt, **pink mask**.
- **Bitsy** — white kitty → **turquoise** suit, slightly darker **blue** gear.

You play one; the other tags along as your friend, and they suit up together.

## 🎤 Level 3 — Zsa Zsa's Rooftop Concert

**Zsa Zsa** is a glamorous **cockatoo** who loves to **sing and steal voices**! She
swoops around the night rooftops stealing the town's floating voices (musical
notes) and **sings sonic rings** — if a ring touches you, you get dazed and can't
move for a moment, so **dodge them**! Chase her and hit her with **yarn** until
she's all tangled up — that frees the voices.

## 🗑️ Level 4 — The Lab Rat's Dumpster Alley (final level!)

The **Lab Rat** lives in the **dumpsters** and pops out of a different one each
time (like whack-a-mole) — lasso him with **yarn** while he's **out**! His slippery
pal **Otto the Octopus** sits in the middle and **sweeps tentacle rings** you have
to dodge. Tangle the Lab Rat enough times and you **win the whole game** — 🏆 *You
saved Kitty Land!*

> Every baddie is caught the same friendly way: **chase + throw yarn (SPACE)**.
> **Easy** needs fewer yarn hits than **Hard**.

## How it works (the fun part)

Everything lives in **one file**, `index.html` — no installing anything. The
kitties are drawn with **SVG shapes**; the *same* drawing is recoloured for Ginny
and Bitsy, and a "regular kitty" is just the super kitty with its mask/belt/emblem
hidden and the suit coloured like fur — so suiting up just turns those back on. The
**music and sound effects** are generated live by the browser's **Web Audio**, so
there are no audio files to ship. Level 2's trapping is simple physics: the crates
are pushable blocks, the puppy steers around them toward the toys, and when he
can't make progress for a moment he's officially **trapped**.

The original dragon game this was adapted from is kept in
`assets/dragon-original-backup.html`.
