# CSS Curved & Shaped Text Experiments

Experiments with making text flow along curves and inside shapes using pure CSS, mainly the `shape-outside` and `clip-path` properties. No JavaScript.

## Files

| File | What it shows |
| --- | --- |
| `test.html` | A quote inside a circle — the text wraps to fit the round shape (Titillium Web font, radial-gradient background) |
| `Untitled-2.html` | A text "funnel": triangles on both sides use `shape-outside` so a paragraph narrows towards a point |
| `Untitled-1.html` | A Venn diagram made with CSS Grid and `shape-outside`, with text that follows the circles for each overlap (One, Two, Three, One + Two, …) |

## How it works

`shape-outside` tells floated elements which shape the surrounding text should wrap around (e.g. `polygon()` or `path()`), and `clip-path` cuts the visible element to the same shape. Placing these floats on both sides of a paragraph makes the text appear to follow a curve or fill a shape.

## Usage

Open any of the HTML files directly in a modern browser. No build step or dependencies.
