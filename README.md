# 🐉 Clara, Shari, and the Dragons

A voice-controlled flying dragon game, made by Clara and Shari.

You fly a dragon by **talking to it** — say "up", "down", "fire" and watch it move!

## How to play

1. Open **`index.html`** in **Google Chrome** (just double-click it).
2. Press the big **▶ Play** button.
3. The first time, Chrome asks to use your microphone — click **Allow**.
4. Talk to your dragon!

### Voice commands

| Say this        | The dragon does       |
| --------------- | --------------------- |
| **"up"**        | flies up (and flaps!) |
| **"down"**      | flies down            |
| **"left"**      | flies left            |
| **"right"** / **"go"** / **"fly"** | flies right |
| **"fire"** / **"burn"** / **"flame"** | breathes fire 🔥 |
| **"land"**      | comes down and rests  |
| **"stop"**      | hovers in place       |

### Points

| Catch this   | Worth | Notes                              |
| ------------ | ----- | ---------------------------------- |
| ⭐ **star**  | 1     | just fly into it                   |
| 🧪 **potion** | 5     | it **explodes** 💥 when you eat it |
| 🐲 **boss**  | 20    | **breathe fire** at it 3 times!    |

The dragon **flaps** while flying and **settles down** when it lands. And it's **pink**! 🩷

### ⚠️ Watch out — spinning stars!

A whirling, red-glowing **🌟 spinning star** flies across the screen now and then.
If it touches your dragon, **💫 stars spin around its head and it gets dizzy** —
you can't move, fire, or do anything for a few seconds. Then the dizziness wears
off and you can play normally again. **Dodge them!**

## The five magical lands 🗺️

Every **200 points**, your dragon flies to a brand-new land — each with its own
magical sky, twinkling sparkles, and scenery:

| Points | Land | Magic |
| ------ | ---- | ----- |
| 0   | 🏰 **Sky Kingdom**     | dawn sky and drifting clouds |
| 200 | 🧚 **Midsummer Forest** | a deep enchanted wood with **twinkling fairies**, mushrooms, and butterflies |
| 400 | 🧜 **Mermaid Lagoon**   | underwater blues with floating bubbles |
| 600 | ❄️ **Aurora Peaks**    | icy mountains under glowing northern lights |
| 800 | 🌈 **Rainbow Castle**   | a candy-colored sky full of rainbows |

A sparkly **"Welcome to..."** banner appears each time you arrive somewhere new.

> No microphone? You can also play with the **arrow keys** and the **space bar** (for fire).

## Ideas to add next (for Clara!)

- Give the dragons names — one called **Clara**, one called **Shari**.
- Add a second dragon you switch between with your voice ("switch dragon").
- Make fire pop the clouds for bonus points.
- Add sound effects when you catch a star.
- Change the dragon emoji 🐉 to a different color or animal.

## Sound 🔊

The game makes its own sounds — a beep for catching a star, a boom for
explosions, a happy tune when you reach a new land, and a woozy slide when you
get dizzy. Sound turns on the moment you press **▶ Play** (browsers don't allow
sound before you click). If you hear nothing, check your computer's volume and
make sure the browser tab isn't muted.

## How it works (the fun part)

The browser has a built-in feature called the **Web Speech API**. It listens to
your voice, turns it into text, and the game looks for command words inside that
text. Everything lives in one file, `index.html`, so it is easy to change and
nothing needs to be installed.
