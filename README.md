# GTU EGD plain and diagonal scale: RF to length of scale, with the sheet-size check

GTU Hero's EGD guide lists a plain or diagonal scale as a 7-mark question type, present in Unit 1 of the new scheme (BE01000061 / BE01R00061, 10% weightage) as well as in the old 3110013 scheme. The type repeats, the RF and the maximum length change every session. RF aur max length daalo: this page gives the length of the scale in mm, how many main parts to divide it into, and the steps to mark the secondary (and, for a diagonal scale, the smallest) unit. Practice values are my own, not from a GTU paper. Scale lambe sheet se bahar nikal gaya toh pehle length check kar lo.

Live page: https://princeadvant.github.io/gtu-egd-diagonal-scale-rf/

## Facts used

- Representative fraction RF = drawing length / object length, in the same units. Written 1:50 or 1/50.
- Length of scale (mm) = RF x maximum length to be measured, after you convert that maximum length to mm.
- A plain (plane) scale shows two units. A diagonal scale shows three units, using 10 horizontals and diagonals on the left part.
- Mark 0 after the first main division, not at the left end. The leftover part to the left of 0 is for the smaller unit.
- If 1 cm represents 2.5 m, RF = 10 mm / 2500 mm = 1:250. The default 1:50 scale long enough for 5 m is 100 mm, with 5 parts of 20 mm.

## Test

`node test.js` checks the calculations against hand-worked values and prints `All checks passed`.

## Tips

- Write the RF calculation on the sheet, including the unit conversion. The drawing alone is not the full answer.
- New-scheme and old-scheme students both have scales in Unit 1. GTU Hero's 7-day plan puts this on Day 1, and says you can skip Day 1 only if the exam is tomorrow and you need the 60% from lines, planes and orthographic first.
- Do not mix up isometric scale with this. Isometric projection (old scheme only) uses the 0.816 foreshortening. A diagonal scale question is a units-and-RF construction.
- If the computed length is more than about 180 mm, say so and suggest a shorter maximum, instead of drawing off the sheet.

Unit weightages, the 7-day EGD plan and which topics new-scheme students can skip: [GTU Hero EGD guide](https://gtuhero.com/blogs/gtu-egd-paper-engineering-graphics-pyq) (GTU Hero is my project).
