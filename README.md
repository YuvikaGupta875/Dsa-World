# Dsa-World


**DSA Worlds** is a lightweight web app to visualize and track Data Structures & Algorithms progress interactively.
**Link :** https://yuvikagupta875.github.io/Dsa-World/
---

## Overview
Each DSA topic appears as an animated “world.”  
Problems are displayed as draggable bubbles that open directly on LeetCode.  
Progress is stored locally in the browser.

---

## Topics
```

Arrays
Two Pointers
Stack
Binary Search
Linked List
Trees
Heap
Recursion
Graphs
DP
Greedy
Intervals
Math
Bit Manipulation

```

---

## Usage
1. Open `index.html` (or `dsa-worlds.html`) in any modern browser.  
2. Click **Add / Import ➕** to add problems using the format:
```

Title;URL;Topic;Difficulty

```
3. Double-click a bubble to mark it as completed.  
4. Progress is saved automatically in `localStorage`.

---

## Seed Data
A default LeetCode-based problem set (~150 problems) is preloaded.  
You can modify it in `loadData()` by editing the `seed` array.

---

## Tech
- HTML, CSS, JavaScript  
- D3.js for SVG visualization  
- localStorage for persistence  

---

## License
MIT © 2025
