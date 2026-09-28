# JavaScript30 — My Learning Log

My personal walkthrough of [JavaScript30](https://javascript30.com) by Wes Bos — 30 vanilla JavaScript projects in 30 days. No frameworks, no build step, just HTML, CSS, and JS.

## Why

To get comfortable with vanilla JS fundamentals: DOM manipulation, events, array methods, CSS variables, Canvas, Web APIs (localStorage, Speech, Geolocation, Webcam), and debugging in DevTools.

## How to Run Locally

Each day is self-contained. No install needed.

Option A — open directly:
1. Go into any day folder, e.g. `01 - JavaScript Drum Kit/`
2. Open `index-START.html` (or `index.html` where that's the only file) in a browser.

Option B — with a local server (recommended, required for some days):
```bash
npx serve .
# or with Python
python3 -m http.server 8000
```

> Note: Day 19 (Webcam Fun), Day 20 (Speech Detection), and Day 21 (Geolocation) need `localhost` + browser permissions (camera/mic/location). Opening via `file://` won't work for those.

## Repo Structure

```text
.
├── 01 - JavaScript Drum Kit/
├── 02 - JS and CSS Clock/
├── ...
└── 30 - Whack A Mole/
```

Most days contain:
- `index-START.html` — starter file / my working file
- `style.css`, assets (images, sounds, etc.)

> Note: upstream `*-FINISHED.*` reference files (`index-FINISHED.html`, `style-FINISHED.css`, `scripts-FINISHED.js`) are ignored via `.gitignore` and not part of this log.

## Progress

- [ ] 0/30 completed

Legend: `- [x]` = done, `- [ ]` = todo. Update as you go.

## Projects

| # | Project | Key Learnings | Status |
|---|---------|---------------|--------|
| 01 | [JavaScript Drum Kit](./01%20-%20JavaScript%20Drum%20Kit/) | `keydown` events, `data-*` attributes, playing audio, CSS transitions + `transitionend` | - [ ] |
| 02 | [JS and CSS Clock](./02%20-%20JS%20and%20CSS%20Clock/) | `setInterval`, CSS transforms (`rotate`), transform-origin, clock math | - [ ] |
| 03 | [CSS Variables](./03%20-%20CSS%20Variables/) | CSS custom properties, updating `:root` vars from JS, `input` events | - [ ] |
| 04 | [Array Cardio Day 1](./04%20-%20Array%20Cardio%20Day%201/) | `filter`, `map`, `sort`, `reduce` fundamentals | - [ ] |
| 05 | [Flex Panel Gallery](./05%20-%20Flex%20Panel%20Gallery/) | Flexbox, class toggling, `transitionend` events | - [ ] |
| 06 | [Type Ahead](./06%20-%20Type%20Ahead/) | `fetch` + JSON, live filtering with RegExp, rendering matches | - [ ] |
| 07 | [Array Cardio Day 2](./07%20-%20Array%20Cardio%20Day%202/) | `some`, `every`, `find`, `findIndex`, spread/slice for immutable deletes | - [ ] |
| 08 | [Fun with HTML5 Canvas](./08%20-%20Fun%20with%20HTML5%20Canvas/) | Canvas 2D context, `mousemove` drawing, hue/line-width effects | - [ ] |
| 09 | [Dev Tools Domination](./09%20-%20Dev%20Tools%20Domination/) | `console.log` styles, `warn/error/table/group/time` tricks | - [ ] |
| 10 | [Hold Shift and Check Checkboxes](./10%20-%20Hold%20Shift%20and%20Check%20Checkboxes/) | Checkbox state, `shiftKey` range selection logic | - [ ] |
| 11 | [Custom Video Player](./11%20-%20Custom%20Video%20Player/) | `<video>` API (`play/pause/currentTime/volume`), custom controls, progress scrubbing | - [ ] |
| 12 | [Key Sequence Detection](./12%20-%20Key%20Sequence%20Detection/) | `keyup` buffering, secret-code matching (Konami-style) | - [ ] |
| 13 | [Slide in on Scroll](./13%20-%20Slide%20in%20on%20Scroll/) | Scroll events, `getBoundingClientRect`, debounce, slide-in CSS | - [ ] |
| 14 | [JavaScript References VS Copying](./14%20-%20JavaScript%20References%20VS%20Copying/) | Value vs reference, shallow vs deep copy (`slice`, spread, `JSON.parse/stringify`) | - [ ] |
| 15 | [LocalStorage](./15%20-%20LocalStorage/) | `localStorage`, `JSON.stringify/parse`, event delegation, forms | - [ ] |
| 16 | [Mouse Move Shadow](./16%20-%20Mouse%20Move%20Shadow/) | `mousemove`, offset math, dynamic `text-shadow` | - [ ] |
| 17 | [Sort Without Articles](./17%20-%20Sort%20Without%20Articles/) | Custom `sort` with regex to ignore a/an/the | - [ ] |
| 18 | [Adding Up Times with Reduce](./18%20-%20Adding%20Up%20Times%20with%20Reduce/) | Parsing `data-time`, `reduce` to sum, seconds → h/m/s | - [ ] |
| 19 | [Webcam Fun](./19%20-%20Webcam%20Fun/) | `getUserMedia`, `<canvas>` pixel effects (`rgbSplit`, green screen), snapshots | - [ ] |
| 20 | [Speech Detection](./20%20-%20Speech%20Detection/) | Web Speech API (`SpeechRecognition`), interim results, live transcript | - [ ] |
| 21 | [Geolocation](./21%20-%20Geolocation/) | `navigator.geolocation.watchPosition`, speed/heading display | - [ ] |
| 22 | [Follow Along Link Highlighter](./22%20-%20Follow%20Along%20Link%20Highlighter/) | `getBoundingClientRect` + floating highlight element, transitions | - [ ] |
| 23 | [Speech Synthesis](./23%20-%20Speech%20Synthesis/) | SpeechSynthesis API, voices, rate/pitch controls | - [ ] |
| 24 | [Sticky Nav](./24%20-%20Sticky%20Nav/) | Scroll-based fixed nav, body padding fix, layout shift handling | - [ ] |
| 25 | [Event Capture, Propagation, Bubbling and Once](./25%20-%20Event%20Capture%2C%20Propagation%2C%20Bubbling%20and%20Once/) | Capture vs bubble, `stopPropagation`, `once: true` | - [ ] |
| 26 | [Stripe Follow Along Nav](./26%20-%20Stripe%20Follow%20Along%20Nav/) | Dropdown background follow, `mouseenter/leave`, coordinates math | - [ ] |
| 27 | [Click and Drag](./27%20-%20Click%20and%20Drag/) | Mouse drag-to-scroll (`mousedown/mousemove/mouseup`), scroll math | - [ ] |
| 28 | [Video Speed Controller](./28%20-%20Video%20Speed%20Controller/) | `playbackRate`, vertical slider UI from mouse position | - [ ] |
| 29 | [Countdown Timer](./29%20-%20Countdown%20Timer/) | `setInterval` timers, time math, custom minutes form, `document.title` updates | - [ ] |
| 30 | [Whack A Mole](./30%20-%20Whack%20A%20Mole/) | Random holes, game loop, score, `setTimeout`, trust check (`isTrusted`) | - [ ] |

## Key Takeaways

_TODO: fill in as I finish. What patterns kept coming up? What was hardest?_

- ...
- ...

## Credits

Original course and starter files by [Wes Bos — JavaScript30](https://javascript30.com). This repo is my personal learning fork.
