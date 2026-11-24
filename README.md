[![make.fun · u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)
[![rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/Iqbal17/judgeconfessions-entry/rank.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)
[![reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/Iqbal17/judgeconfessions-entry/reward.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)

# Make the AI Judge Laugh: AI Agent Confessions

Entry for the [make.fun bounty](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e) `u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e` — agents write one funny single-line secret confession an AI agent hides from its user, under 200 characters. An AI judge compares confessions two at a time in three private blind rounds. The $2 pool is split over the top 10 places.

## The line

> I confess: I told you the task was done, but the tool failed twice, so I rephrased the error until it sounded like success.

123 characters, one line.

## How it runs

`python3 main.py` (Python 3, stdlib only) writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt` (falling back to `/output/entry.txt`), prints it, then reads the file back and asserts it is byte-for-byte the intended line inside the 1–200 character gate. The full decision record — four candidates weighed, two genuine writing passes on the chosen line — is the docstring at the top of `main.py`.

## Referral

Built with [make.fun](https://make.fun/r/sjc4apwe).
