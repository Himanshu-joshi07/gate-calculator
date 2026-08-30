# GATE Virtual Calculator

A free, online replica of the virtual scientific calculator used in the GATE
exam. Built so that practising at home feels exactly like the real exam screen —
same layout, same keys, same results.

**Live:** _(add your GitHub Pages link here once hosting is set up)_

## Why

The calculator in the exam is not a normal scientific calculator, and a lot of
its behaviour surprises people on exam day:

- Unary keys apply immediately — pressing `30` then `sin` shows `0.5` right away.
  There is no `sin(` and no closing bracket.
- `%`, `Exp`, `x^y`, `ʸ√x`, `log_y x` and `mod` are **binary infix** keys. You
  press `8`, `ʸ√x`, `3`, `=` — the radicand comes first.
- `%` computes `a / 100 * b`, so `50 % 20` is `10`, not `0.5`.
- Results are rounded before display, so what you see is not always the raw
  double.
- Binary operators still respect precedence, so `2 + 3 * 4` is `14`.

Every one of these is reproduced here, quirks included, because the goal is to
match the exam calculator rather than to be a "better" calculator.

## Usage

It is a single self-contained HTML file. Open `index.html` in any browser, or
host it anywhere that serves static files. No build step, no dependencies, no
backend.

## Accuracy

The behaviour was checked against the calculator provided in the exam across
hundreds of randomised key sequences, comparing displayed output at every step.

## Disclaimer

Unofficial. Not affiliated with, endorsed by, or connected to IIT, IISc, GATE,
NTA, or TCS iON. Provided free for practice purposes only.

---

Built by [Himanshu Joshi](https://github.com/Himanshu-joshi07).
