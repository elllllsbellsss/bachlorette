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

## Customizing

All clues and answers live in the `CATEGORIES` array near the top of the
`<script>` block in `index.html`. A few answers weren't on the original sheet,
so they're marked **`(Host reveals!)`** — edit them in (or just keep them a
surprise the bride/groom reveals live). Team names are editable right on the
scoreboard — click a name to change it.
