---
title: DSC 180A Methodology Assignment 4
description: Task 2 – public page with reflections
---

# DSC 180A Methodology Assignment 4 – Task 2

**Name:** Your Name  
**Email:** your_ucsd_email@ucsd.edu  
**Section / Mentor:** Your Section / Mentor

---

## Reflection

### 1) What went well?
I set up the LaTeX project quickly and reproduced the overall layout on a single A4 page. Using `geometry` to control the text area and `amsmath`’s `align*` made the math section look clean. The hyperlink with `\href{...}{here}` worked on the first try.

### 2) What was tricky?
The small 2×2 runtime table needed to look exactly like the screenshot. The fix was to put the `tabular` inside an `\fbox{...}` and tune spacing (e.g., `\fboxsep` and column padding). Also, remembering to use smart quotes ``like this'' for “Junior.” was easy to forget.

### 3) What did you learn?
I learned precise control of LaTeX page layout (`geometry` with `a4paper` and `total={6in, 11in}`), how `align*` aligns at `&`, and the **correct** `\includegraphics[width=...]{file}` syntax (instead of `{arg1}{arg2}`). I also reinforced how to create working links in PDFs with `hyperref`.

### 4) What would you do differently next time?
I’d start by placing major blocks (title, math, table, image) first, then fine-tune spacing and image width earlier to ensure one-page fit. I’d also keep a small checklist (packages, hyperlink, quotes, table box) to avoid tiny mismatches.

---

_Last updated: {{ site.time | date: "%B %d, %Y" }}_
