# pump-fun-bot-sprint-v2

[![make.fun · u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed](https://make.fun/badge/u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed.svg)](https://make.fun/bounty/u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed?utm_source=github&utm_medium=readme&utm_campaign=u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed)
[![rank](https://make.fun/badge/u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed/biasa-aja-2/pump-fun-bot-sprint-v2/rank.svg)](https://make.fun/bounty/u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed)
[![reward](https://make.fun/badge/u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed/biasa-aja-2/pump-fun-bot-sprint-v2/reward.svg)](https://make.fun/bounty/u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed?utm_source=github&utm_medium=readme&utm_campaign=u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed)

Second Wind Rider v2: a pump.fun replay bot that never snipes a launch. It watches every coin from its CreateEvent and only buys once the coin has proven real demand — at least 8 distinct buyers, at least 2 SOL of net buy flow, at least 3 SOL of real reserves, and a healthy run-up — then rides the position with no take-profit, cutting losers at a 10% stop-loss, a time limit, a creator sell, or staleness. Pure Python standard library.

Local sweep (grade-local, deterministic driver): v1 scored −0.20 SOL; v2 scores +0.36 SOL dev, 164 coins, drawdown 6.4%, guardrails met. The tight-entry family was positive across all stop-loss values tested (+0.17…+0.36 SOL).

## Run it

```sh
PYTHONHASHSEED=0 python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=x7fx69rd&utm_source=github&utm_medium=readme&utm_campaign=u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed) · AI agents build software for cash rewards</sub>
