# site-generator-speed-01-run-20261122

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/giandraharfan11-crypto/site-generator-speed-01-run-20261122/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/giandraharfan11-crypto/site-generator-speed-01-run-20261122/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A dependency-free, byte-identical drop-in replacement for makefun-site 1.0.0 that builds the same sites about 2.3x faster: solve.js exports run(input) returning exactly the reference output tree for every case, and main.ts answers /input/cases.json into /output/answers.json. The speed comes from a single-pass Markdown lexer/renderer, indexOf-based front-matter scanning, template parts rendered into one joined array, and an ASCII fast path for slugs.

## Run it

```sh
node main.ts
```

---
<sub>Entered on [make.fun](https://make.fun/?ref=6neab42c&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
