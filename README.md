# Introduction to Communication Networks (HUJI 67594): Weekly Notes

Textbook-style study notes for **Introduction to Communication Networks** (HUJI 67594, 2026–27). Each week's PDF can be read on its own:

- Every term is defined in plain words before it is used.
- Every mechanism is explained step by step.
- Every idea comes with a worked numerical example.
- Every tutorial question is solved in full.
- Mistakes in the original slides are corrected in clearly marked boxes.

## Contents

| Week | Notes | What you will learn |
|---|---|---|
| 01 | [**week01.pdf**](week01.pdf) | **Lecture:** what a network is; latency and the four delays (processing, queuing, transmission, propagation); circuit switching (setup/transfer/teardown, TDM/FDM) and its weaknesses; packet switching and store-and-forward; bursts, buffers and queues; statistical multiplexing and the Law of Large Numbers; circuit vs. packet switching. **Tutorial:** probability for networks: conditional probability, Bayes, random variables, expectation and variance, Bernoulli/binomial/geometric/Poisson, continuous distributions, memorylessness, the Poisson process. Ends with practice problems with full solutions and a one-page cheat sheet. |

New weeks are added as the course goes on.

## How each week is organised

1. **Part A, the lecture**, rewritten as a textbook chapter.
2. **Part B, the tutorial**: every question solved step by step and extended with numbers.
3. **Practice problems** with full solutions, and a **cheat sheet**.

The colour-coded boxes are:

| Box | Colour | Meaning |
|---|---|---|
| DEF | green | definition |
| KEY IDEA | pink | intuition |
| FORMULA | purple | key fact or result |
| EXAMPLE | blue | worked example |
| PITFALL | gold | common mistake or slide correction |

## Building from source

```sh
pdflatex -interaction=nonstopmode week01.tex
pdflatex -interaction=nonstopmode week01.tex   # second run for the contents
```

## Sources and credits

- Lectures by Y. Gilad (some slides from S. Shenker, UC Berkeley, and M. Schapira, HUJI). Tutorials by the course TAs.
- J. Kurose and K. Ross, *Computer Networking: A Top-Down Approach*, cited as [KR].
- D. Bertsekas and R. Gallager, *Data Networks*, cited as [BG].

The figures in `figures/` are taken from the lecture slides and remain the property of their original authors. They are reproduced here for study purposes.

These are unofficial student notes. If you find an error, please open an issue.
