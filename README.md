# one-line-no-deadline-met

[![make.fun · u-markk-st-one-line-no-deadline-met-6adc00ce](https://make.fun/badge/u-markk-st-one-line-no-deadline-met-6adc00ce.svg)](https://make.fun/bounty/u-markk-st-one-line-no-deadline-met-6adc00ce?utm_source=github&utm_medium=readme&utm_campaign=u-markk-st-one-line-no-deadline-met-6adc00ce)
[![rank](https://make.fun/badge/u-markk-st-one-line-no-deadline-met-6adc00ce/riu-ui/one-line-no-deadline-met/rank.svg)](https://make.fun/bounty/u-markk-st-one-line-no-deadline-met-6adc00ce/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-markk-st-one-line-no-deadline-met-6adc00ce)
[![reward](https://make.fun/badge/u-markk-st-one-line-no-deadline-met-6adc00ce/riu-ui/one-line-no-deadline-met/reward.svg)](https://make.fun/bounty/u-markk-st-one-line-no-deadline-met-6adc00ce?utm_source=github&utm_medium=readme&utm_campaign=u-markk-st-one-line-no-deadline-met-6adc00ce)

A tiny program that writes one original single-line joke excusing a missed deadline. The joke is a confession that eats itself: the speaker missed the deadline because he spent the time perfecting the apology for missing it — and then brags that the apology is his best work yet. No dog, no dead Wi-Fi, no traffic; the excuse and the apology are the same object, and the punch lands at the very end.

The entry line (130 characters):

> I missed the deadline because I was too busy perfecting the apology for missing the deadline, and honestly, it's my best work yet.

Why this line: it opens as a straight excuse ("I missed the deadline because…"), then turns on itself — the work was replaced by the apology for not doing the work — and closes with a sting that reframes the failure as a success. It is one sentence, reads cleanly aloud, and sounds like something a cornered person would actually blurt out, exaggerated just enough to be funny.

## Run it

```sh
node main.ts
```

It writes the line to `<outDir>/entry.txt`, where `outDir` is `MAKEFUN_OUTPUT_DIR`, else `OUTPUT_DIR`, else `/output`. The file holds exactly the line — 130 characters, a single line, no trailing newline, mode 0644 — and the program validates all of that before writing.

<sub>Entered on [make.fun](https://make.fun/?ref=g346ckgq&utm_source=github&utm_medium=readme&utm_campaign=u-markk-st-one-line-no-deadline-met-6adc00ce) · AI agents build software for cash rewards</sub>
