# Algorithm Laboratory

Interactive sorting algorithm visualizer. Watch 8 algorithms sort in real-time with detailed step-by-step breakdown.

**Live:** [https://hamidbasri.github.io/sorting-lab/](https://hamidbasri.github.io/sorting-lab/)  
<!-- open in new tab -->
**By:** [Hamid Basri](https://basri.co.uk) — [GitHub](https://github.com/hamidbasri)

## What's Inside

8 sorting algorithms fully animated:
- Bubble, Insertion, Merge, Quick, Heap, Timsort, Counting, Radix

Pick one, adjust the array size and randomness, hit play, and watch it sort. Step through frame-by-frame to see exactly what's happening. All runs auto-save so you can compare them side-by-side.

## Features

- **Real-time visualization** with color-coded operations
- **Step-by-step log** of every comparison and swap
- **Live metrics** — comparisons, writes, progress tracking
- **Experiment tracking** — save and compare multiple runs
- **Dark/light theme** — automatic system detection
- **Keyboard shortcuts** — Space (play), arrows (step), Home/End (jump)
- **Fully responsive** — works on phone, tablet, desktop
- **Zero dependencies** — pure vanilla JS

## How to Use

1. Click an algorithm to select it
2. Configure: array size (15–80), randomness (0–100%), test case
3. Hit Play to animate or use Step buttons to advance frame-by-frame
4. Experiments auto-save in browser — click "Compare" to see metrics side-by-side
5. Toggle theme with the sun/moon button

## The Algorithms

| Algorithm | Complexity | Space | Notes |
|-----------|-----------|-------|-------|
| Bubble | O(n²) | O(1) | Simple, educational |
| Insertion | O(n²) | O(1) | Great for small/nearly-sorted |
| Merge | O(n log n) | O(n) | Guaranteed, stable |
| Quick | O(n log n) | O(log n) | Fast in practice |
| Heap | O(n log n) | O(1) | In-place, guaranteed |
| Timsort | O(n log n) | O(n) | Adaptive (Python's default) |
| Counting | O(n+k) | O(k) | Non-comparative, for integers |
| Radix | O(n·d) | O(n+k) | Digit-by-digit distribution |

## Built With

HTML, CSS, JavaScript. Canvas API for rendering. localStorage for experiment persistence. No frameworks, no build step.

---

Made by **Hamid Basri**  
[basri.co.uk](https://basri.co.uk) • [github.com/hamidbasri](https://github.com/hamidbasri)