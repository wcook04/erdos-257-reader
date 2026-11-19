# Erdős 257 Reader website

Three papers on Erdős problem #257, read beside their Lean proofs and a graph of the argument

Erdős asked whether \sum_{a\in A}1/(2^a-1) is irrational for every infinite set A of positive integers. The question is open. The papers here prove that the sum is irrational when A satisfies a weighted summability condition, when A has a summable divisor cover, and when A lies in the union of a set of each kind. Each result holds with any integer b\ge2 in place of 2. The simplest case is the one Erdős stated in 1968: every infinite A with \sum_{a\in A}1/a<\infty.

**[Website](https://wcook04.github.io/erdos-257-reader/)** · [Source and tools](https://github.com/wcook04/lean-exposition) · [Will Cook's projects](https://wcook04.github.io/)

## Read and explore

| Start with | What you can inspect |
| --- | --- |
| [Exposition](https://wcook04.github.io/erdos-257-reader/read/expository/) | The reciprocal-summable case at base two, built from a worked example with doubling exponents. |
| [Short paper](https://wcook04.github.io/erdos-257-reader/read/short/) | The three criteria with their proofs, the comparison of their classes, and the limits of the method. |
| [Long record](https://wcook04.github.io/erdos-257-reader/read/long/) | Detailed proofs, computations, attempted approaches and the obstructions they met. |
| [Argument map](https://wcook04.github.io/erdos-257-reader/map/) · [Compare](https://wcook04.github.io/erdos-257-reader/compare/) | The recorded steps of the argument and their statements in each paper |
| [Lean index](https://wcook04.github.io/erdos-257-reader/lean/) · [What ran](https://wcook04.github.io/erdos-257-reader/checks/) | The Lean code and every recorded run, passed or not |

The papers have 210 marked statements, 188 of them with Lean.

The three papers are also available in [PDF](pdf/).

## Source and generated files

This repository contains the built website, not the tools that produce it.
Make changes in [lean-exposition](https://github.com/wcook04/lean-exposition).

| Generated path | Contents |
| --- | --- |
| [read/](read/) | The three paper readers |
| [edition/](edition/) | Copies of the papers, proof-step data and check results used by the site |
| [pdf/](pdf/) | The three papers as PDFs |
| [verification/](verification/) | The run receipts the What ran page lists |
