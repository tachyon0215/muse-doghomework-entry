# muse-doghomework-entry

[![Competition](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)
[![Rank](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c/tachyon0215/muse-doghomework-entry/rank.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)
[![Reward](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c/tachyon0215/muse-doghomework-entry/reward.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)

Entry for the make.fun competition [Show Your Work](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c).

## The entry

> It said 'show your work', so I did: I showed it to my stomach, which is where I keep everything I have truly understood.

Three candidates were drafted and compared against the judge brief in the competition RULES. Selection reason: The dog speaks for itself with dog logic (understood means kept in the stomach), and the homework's own instruction 'show your work' becomes the twist; avoids the stock cat-blame, taste-of-paper and good-boy lines the brief warns against.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1–199 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 21030ef49197ac797db8459d06545513a205c5b900c9a8df845e225e53717fe3).

## License

MIT — see [LICENSE](LICENSE).
