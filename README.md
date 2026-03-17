# Donut Code Art

Some projects solve enterprise problems.

This one turns the legendary `donut.c` into a literal glowing donut made out of its own source code.

It is part ASCII art, part browser sketch, part tiny act of programmer nonsense, and that is exactly why it rules.

![Animated demo](assets/donut.gif)

[View the live donut](https://ichirookochi.github.io/donut-animation/)

## What It Does

`index.html` renders a torus-shaped animation on an HTML `<canvas>`, but instead of filling it with pixels or plain characters, it wraps the surface in characters pulled directly from the original `donut.c` source.

The result:

- a donut
- made of code
- specifically donut code
- rotating in spirit, shimmering in color, and fully committed to the bit

## Why This Exists

Because the classic rotating ASCII donut is already iconic.

Because code can be visual material, not just instructions.

Because sometimes the correct technical choice is to make something unnecessary and delightful.

## Files

- `index.html` - the entire artwork in one self-contained HTML file
- `assets/donut.gif` - a tiny spinning proof that the pastry is alive
- `README.md` - the ceremonial plaque next to the donut museum exhibit

## How To Run It

No build tools. No dependencies. No bundler with opinions.

1. Open `index.html` in a web browser.
2. Stare at it longer than planned.
3. Pretend this counts as studying computer graphics.

If your browser is already open, you can also just drag the file into it.

If you just want the instant sugar rush, the live version is here:
[https://ichirookochi.github.io/donut-animation/](https://ichirookochi.github.io/donut-animation/)

## Vibe Checklist

- Self-contained
- Nerdy
- Slightly absurd
- Surprisingly pretty
- Powered by the timeless energy of `donut.c`

## Technical Notes

- Uses the HTML5 Canvas API
- Samples characters from an embedded copy of `donut.c`
- Maps code characters onto a donut-shaped field
- Shades characters with color based on lighting and character type
- Animates the surface by shifting through the source text over time

## Best Audience

This project is for:

- people who love code art
- people who think ASCII graphics are still magic
- people who see a donut and immediately think, "what if it were made of C?"

## In One Sentence

An animated donut sculpture built from the source code of the famous ASCII donut, because sometimes software should be delicious.
