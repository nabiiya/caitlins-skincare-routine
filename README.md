# Caitlin's Skincare Routine

An interactive, scroll-through story of my real morning and night Korean
skincare routine using HTML and CSS.

I've struggled with acne since I was younger, and over the past 2 years I
finally found products that work for me. This page shares that routine in a
fun, interactive way.

# Live demo
https://nabiiya.github.io/caitlins-skincare-routine/

# Features

- Morning & night split: the two routines sit side by side, styled
  differently (soft pink vs. cozy brown) so day and night feel distinct.
- Hover popovers: hover any step to reveal the exact product, why I use
  it, its key ingredient, and a personal note.
- Clickable product links: each product links out to where you can buy it.
- Smooth animations: cards lift and tooltips fade in using CSS
  transitions.
- Responsive: the layout stacks neatly on smaller screens.

# Built with

- HTML5
- CSS3 (Flexbox, transitions, hover states, positioning)
- Google Fonts (Fuzzy Bubbles, Caveat, Quicksand)

# What I learned

- Building a multi-section layout with Flexbox
- Creating hover tooltips with `position: absolute` and `:hover`
- Using CSS transitions to make interactions feel smooth
- Debugging real issues like a tooltip hiding behind another element
  (fixed with `z-index`) and links that weren't clickable (fixed with
  `pointer-events`)
- Working with image files, file paths, and accessible `alt` text
