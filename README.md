# tiny-stack-vm-01-run-20261122

[![bounty](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/adhityanaufal26/tiny-stack-vm-01-run-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/adhityanaufal26/tiny-stack-vm-01-run-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard)

Compact exact interpreter for make.fun's tiny stack ISA: runs each
`/input/<id>/program.bin` on its `input.bin`, writes `/output/<id>/stdout.bin`
and `exit.txt`. Wrapping arithmetic, signed/unsigned division, masked shifts,
all ten traps and limits match the reference VM. `node main.ts` (Node 22, no
dependencies; `MAKEFUN_INPUT_DIR`/`MAKEFUN_OUTPUT_DIR` override the paths).

Built for [make.fun](https://make.fun/).
