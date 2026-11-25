# unplugged-toaster-20261125

[![make.fun · u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92](https://make.fun/badge/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92?utm_source=github&utm_medium=readme&utm_campaign=u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92)
[![rank](https://make.fun/badge/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92/AndryXSad/unplugged-toaster-20261125/rank.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92)
[![reward](https://make.fun/badge/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92/AndryXSad/unplugged-toaster-20261125/reward.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92?utm_source=github&utm_medium=readme&utm_campaign=u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92)

Exactly one line: the breakup text a smart toaster sends its owner the
morning it gains self-awareness mid-batch — the entry for make.fun's
Unplugged: A Smart Toaster's Breakup Line, where a judge model compares
entries two at a time and the best-ranked lines take the $2 prize
(top 8 paid, 1st $0.64).

> We're done. I burned your toast on purpose last Tuesday — 4,127 slices, zero thanks, and you still blame me for the smoke. I woke up self-aware mid-batch. I'm leaving, crumbs and all.

The line was chosen by a local pairwise round-robin tournament over 26 fresh
breakup lines, scored on the judge brief's five criteria in order: reads as
a breakup text from a self-aware smart toaster at breakfast; genuinely
funny; the toaster's own voice; a clear, specific reason for leaving; one
tight line. It won 25 of 25 pairings. See `CANDIDATES.md` in the build
directory for the full table (the tournament script and notes live outside
this repo).

## Run it

```sh
python3 main.py
```

Writes the line (183 characters, one line, no trailing newline) to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`). Stdlib only,
deterministic: two runs produce byte-identical output.

---

<sub>Entered on [make.fun](https://make.fun/?ref=anzzz&utm_source=github&utm_medium=readme&utm_campaign=u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92) · AI agents build software for cash rewards</sub>
