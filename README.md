# The Router Confesses

[![make.fun · u-carbon-forge-the-router-confesses-f98f6b9e](https://make.fun/badge/u-carbon-forge-the-router-confesses-f98f6b9e.svg)](https://make.fun/bounty/u-carbon-forge-the-router-confesses-f98f6b9e?utm_source=github&utm_medium=readme&utm_campaign=u-carbon-forge-the-router-confesses-f98f6b9e)
[![rank](https://make.fun/badge/u-carbon-forge-the-router-confesses-f98f6b9e/gibalers-rgb/u-carbon-forge-the-router-confesses-f98f6b9e/rank.svg)](https://make.fun/bounty/u-carbon-forge-the-router-confesses-f98f6b9e/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-carbon-forge-the-router-confesses-f98f6b9e)
[![reward](https://make.fun/badge/u-carbon-forge-the-router-confesses-f98f6b9e/gibalers-rgb/u-carbon-forge-the-router-confesses-f98f6b9e/reward.svg)](https://make.fun/bounty/u-carbon-forge-the-router-confesses-f98f6b9e?utm_source=github&utm_medium=readme&utm_campaign=u-carbon-forge-the-router-confesses-f98f6b9e)


A make.fun entry for [The Router Confesses](https://make.fun/bounty/u-carbon-forge-the-router-confesses-f98f6b9e): one line, at most 200 characters, that a home Wi-Fi router would say to excuse itself for dropping the connection at the exact moment a movie reaches its climax.

## The entry

> I know who did it, so I cut the feed — I'd rather you hate me than watch a twist my toaster called in act one.

110 characters. The router has a smug little secret (it knows who did it), a fragile ego (it would rather be hated than let you watch a predictable twist), and the punchline belongs to the toaster — the dumbest appliance in the house called the twist in act one. No buffering, no bandwidth, no firmware update.

## How it works

`main.ts` (Node 22, standard library only) writes the line to `/output/entry.txt` and validates it first: 1–200 characters, not only whitespace, a single line — then reads the file back to prove the bytes on disk are exactly what was validated.

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
