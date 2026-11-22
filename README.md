# Fast makefun-site

[![make.fun](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/Noddy1012/site-generator-speed-01/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/Noddy1012/site-generator-speed-01/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)

A faster drop-in for makefun-site 1.0.0: `solve.js` answers exactly as
makefun-site does on every case — the same output tree, byte for byte — in
much less CPU time. `main.ts` is the program the harness runs: it reads every
case from `/input/cases.json`, answers each one alone with `run`, and writes
`/output/answers.json`.

Written from the behaviour stated in makefun-site's README (its front matter,
template dialect, Markdown subset, slug rule and report), without copying its
code. No dependencies; Node 22 standard library only.
