# Trailock
**Slide. Cover. Solve.**

A sliding-cover puzzle. The token slides until something blocks it — a wall,
an obstacle, or its own trail. The level is solved when every free cell has
been covered.

No timer, no lives, no penalty. A move is either right or it walks you into a
dead end, and finding out is the game.

## What makes it different

The levels are **measured, not tuned by feel**. Six timed sessions produced
22 695 recorded events across 221 distinct boards, and the play order and the
1–5 difficulty badge come from a model fitted on that data:

```
log(seconds) = 1.715 + 0.353 * hiddenTraps - 0.218 * counterIntuitive
n = 230, r² = 0.129
```

What costs the player time is fatal moves they cannot see are fatal.
Counter-intuitive decisions — where the correct move covers *fewer* cells
than the tempting one — make a board **faster**, because they are a signal
the player learns to read.
