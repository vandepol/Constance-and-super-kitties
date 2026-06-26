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

> No microphone? You can also play with the **arrow keys** and the **space bar** (for fire).

## Ideas to add next (for Clara!)

- Give the dragons names — one called **Clara**, one called **Shari**.
- Add a second dragon you switch between with your voice ("switch dragon").
- Make fire pop the clouds for bonus points.
- Add sound effects when you catch a star.
- Change the dragon emoji 🐉 to a different color or animal.

## How it works (the fun part)

The browser has a built-in feature called the **Web Speech API**. It listens to
your voice, turns it into text, and the game looks for command words inside that
text. Everything lives in one file, `index.html`, so it is easy to change and
nothing needs to be installed.
