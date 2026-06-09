# 💍 Taylor's Bachelorette Jeopardy

A self-contained, projector-friendly Jeopardy game built for Taylor & Alex's
bachelorette party — based on the original `Taylor_Bachlorette_Jeopardy.pdf` board.

## How to play

Just open **`index.html`** in any web browser (laptop, phone, or hooked up to a TV).
No internet, no install, nothing to set up.

1. Tap a dollar value to flip up the clue.
2. Read it out loud, let the players guess.
3. Hit **Reveal Answer** (or press the **spacebar**) to show the answer.
4. Use the **+ / −** buttons on each team card to keep score — when a clue is
   open, the buttons award that clue's dollar value automatically.
5. **Close** (or **Esc**) marks the tile as used and returns to the board.

## Categories

| Category | Theme |
|---|---|
| How Well Do You Know The Bride? | Taylor trivia |
| A Brief History Of The Happy Couple | Taylor & Alex's love story |
| To Know Alex Is To Love Him | All about the groom |
| She's Beauty, She's Grace, She's Full Of Toilet Humor | Taylor's prank hall of fame |
| The Bride Tribe | "Most likely to…" group vote |
| Us Weekly Addict | Pop-culture & nostalgia |

## Game-show extras

- **⭐ Daily Doubles** — two random tiles (never on the $100 row, just like the
  show) trigger a flashing Daily Double banner and a little fanfare when opened.
- **⏱ Timer** — a 15-second countdown you can start inside any clue; it turns
  red and pulses in the final 5 seconds and dings when time's up. While it runs,
  an original "thinking" waltz plays in that classic game-show spirit (the real
  Jeopardy cue is copyrighted, so this is a synthesized sound-alike — still no
  audio files, still works offline).
- **🎵 Bring your own timer music** — click **🎵 Timer Music** to load an audio
  file you own (any `.mp3`/`.m4a`/`.wav`). It loops during the countdown in place
  of the built-in tune, and is remembered between sessions (short clips save
  best). Click the button again to remove it and go back to the built-in waltz.
- **🔔 Buzzer** — a buzz button (or press **Enter** while a clue is open) plays
  a buzzer sound and a full-screen flash. No sound files needed — it's generated
  in the browser, so it works offline.

## Editing the game (no code required!)

Click **✏️ Edit Mode** at the bottom, then click directly on:

- the **game title** or subtitle,
- any **category** heading, or
- any **tile** (opens an editor for that clue + its answer — hit **💾 Save**).

Your changes save automatically in the browser on that device. To keep them
forever or move them to another device:

- **⬇ Export** downloads your game as a `.json` file.
- **⬆ Import** loads a `.json` file back in.
- **⟲ Restore Original** resets everything to the questions from the PDF.

A few answers weren't on the original sheet, so they're marked
**`(Host fills in!)`** — pop into Edit Mode and fill them in, or keep them a
surprise the bride/groom reveals live. Team names are also editable right on the
scoreboard — just click a name.
