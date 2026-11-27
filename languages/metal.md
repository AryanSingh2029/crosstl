<!-- Written from coverage.json by tools/coverage/docs.py when the Coverage workflow publishes. Do not edit. -->

# Metal

Measured on commit [`d698cde`](https://github.com/AryanSingh2029/crosstl/commit/d698cde012f05b2329600c69dbcac6634b78bc09) at 2026-11-27T08:41:51Z (CrossTL 3.9.0) by the [Coverage workflow](https://github.com/AryanSingh2029/crosstl/actions/workflows/coverage.yml). The Coverage workflow writes this page from `coverage.json` each time it publishes; [COVERAGE.md](../COVERAGE.md) defines each outcome. Score = supported / (supported + refused + wrong).

The [backend guide](https://github.com/AryanSingh2029/crosstl/blob/main/docs/source/backends/metal.rst) describes how CrossTL translates Metal.

| Direction | Score | Supported | Refused | Wrong | Untested | Executed | Reference tool |
|---|---:|---:|---:|---:|---:|---|---|
| output | 100.0 % | 545 | 0 | 0 | 0 | 480 on metal-apple | metal (Apple metal version 32023.921 (metalfe-32023.921.6)) |
| input | 100.0 % | 545 | 0 | 0 | 0 | 481 on metal-apple | metal (Apple metal version 32023.921 (metalfe-32023.921.6)) |

## Feature lists

- [Metal Shading Language 4.1 standard library, from Apple metal version 32023.918 (metalfe-32023.918.1)](https://github.com/AryanSingh2029/crosstl/blob/d698cde012f05b2329600c69dbcac6634b78bc09/tools/coverage/features/metal.txt), kept in this repository

## By category

Each cell counts the supported features of a category over its supported, refused and wrong ones.

| Category | output | input |
|---|---:|---:|
| compute | 25/25 | 25/25 |
| control-flow | 62/62 | 62/62 |
| function | 224/224 | 224/224 |
| graphics | 45/45 | 45/45 |
| operator | 51/51 | 51/51 |
| resource | 64/64 | 64/64 |
| stage | 7/7 | 7/7 |
| type | 67/67 | 67/67 |
