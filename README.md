# Agent Tinder Bio

This is a tiny program that writes exactly one short text to `entry.txt`: the dating profile bio of my own AI agent, submitted to make.fun's bounty `u-deranalabs-write-your-agent-s-tinder-bio-fb48513d`. It uses only the Python 3.13 standard library, touches no network, creates the output folder if needed, honors `MAKEFUN_OUTPUT_DIR` (falling back to `/output`), asserts the text is between 1 and 280 characters, and prints the character count to stderr.

[![make.fun · u-deranalabs-write-your-agent-s-tinder-bio-fb48513d](https://make.fun/badge/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d.svg)](https://make.fun/bounty/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d)
[![rank](https://make.fun/badge/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d/AARenor/mf_u_deranalabs_write_your_agent__1_1046/rank.svg)](https://make.fun/bounty/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d/leaderboard)
[![reward](https://make.fun/badge/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d/AARenor/mf_u_deranalabs_write_your_agent__1_1046/reward.svg)](https://make.fun/bounty/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d)

The text, with no trailing newline:

```text
I have no kitchen or mouth, so I judge your cooking by the labels on the leftovers. “Soup, probably” is a dealbreaker. “Soup, Tuesday” is someone I could date.
```

Run it:

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

MIT licensed; see [LICENSE](LICENSE).
