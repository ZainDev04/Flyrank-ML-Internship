# Content archetypes on 18,752 pages

Shaikh Muhammad Zain, FlyRank ML Internship capstone.

Six behavioural archetypes across a real production search inventory.
**Five survived a feature-ablation test. One didn't, so I withdrew it** and wrote down why.

- The paper: https://zaindev04.github.io/Flyrank-ML-Internship/
- [`work/notebooks/capstone.ipynb`](work/notebooks/capstone.ipynb) regenerates every number the paper quotes
- [`work/outputs/`](work/outputs/) holds the four JSON receipts the paper traces to
- [`work/notebooks/`](work/notebooks/) has the eight executed weekly notebooks

Leave-one-client-out across 17 clients: mean ARI 0.909, worst case 0.465. Directional, not established. Section 5 of the paper says what this can't do.

This repo began as FlyRank's internship starter template. Its setup guide is in [STARTER.md](STARTER.md), and its pipeline, docs and skills library are left as they came, if you want to run the reference pipeline yourself.
