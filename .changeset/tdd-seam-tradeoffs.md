---
"mattpocock-skills": patch
---

`tdd` now gives each proposed seam a one-line note on what it catches and what it misses, so choosing between seams is no longer a guess (#607). The note also covers whether a seam exercises the real behavior or only a proxy, and says to split driving the behavior from observing it when no seam does both.
