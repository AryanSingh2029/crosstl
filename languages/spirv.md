<!-- Written from coverage.json by tools/coverage/docs.py when the Coverage workflow publishes. Do not edit. -->

# SPIR-V

Measured on commit [`d698cde`](https://github.com/AryanSingh2029/crosstl/commit/d698cde012f05b2329600c69dbcac6634b78bc09) at 2026-11-27T08:41:51Z (CrossTL 3.9.0) by the [Coverage workflow](https://github.com/AryanSingh2029/crosstl/actions/workflows/coverage.yml). The Coverage workflow writes this page from `coverage.json` each time it publishes; [COVERAGE.md](../COVERAGE.md) defines each outcome. Score = supported / (supported + refused + wrong).

The [backend guide](https://github.com/AryanSingh2029/crosstl/blob/main/docs/source/backends/spirv.rst) describes how CrossTL translates SPIR-V.

| Direction | Score | Supported | Refused | Wrong | Untested | Executed | Reference tool |
|---|---:|---:|---:|---:|---:|---|---|
| output | 100.0 % | 565 | 0 | 0 | 3 | 414 on vulkan-lavapipe | spirv-val (SPIRV-Tools v2026.4 ef96ed763b43b59b33b31b362f09a02b729fa1c9) |
| input | 100.0 % | 567 | 0 | 0 | 1 | 417 on vulkan-lavapipe | spirv-val (SPIRV-Tools v2026.4 ef96ed763b43b59b33b31b362f09a02b729fa1c9) |

## Feature lists

- [SPIR-V GLSL.std.450 extended instruction grammar](https://github.com/KhronosGroup/SPIRV-Headers/blob/496543121ce6419f23d6fa5d7194ba66c36212d2/include/spirv/unified1/extinst.glsl.std.450.grammar.json), pinned at `496543121ce6`
- [SPIR-V core grammar (execution models, capabilities, storage classes, instructions)](https://github.com/KhronosGroup/SPIRV-Headers/blob/496543121ce6419f23d6fa5d7194ba66c36212d2/include/spirv/unified1/spirv.core.grammar.json), pinned at `496543121ce6`

## By category

Each cell counts the supported features of a category over its supported, refused and wrong ones.

| Category | output | input |
|---|---:|---:|
| compute | 28/28 | 28/28 |
| control-flow | 62/62 | 62/62 |
| function | 199/199 | 201/201 |
| graphics | 73/73 | 73/73 |
| operator | 52/52 | 52/52 |
| resource | 67/67 | 67/67 |
| stage | 14/14 | 14/14 |
| type | 70/70 | 70/70 |

## Gaps

A diagnostic drops its line numbers and writes the probe's own variables as `<probe>`, and one that several features share writes each feature's name as `<feature>`.

### Output

Untested, by reason:

- `alternative encoding of Frexp, chosen by the compiler`: `FrexpStruct`
- `alternative encoding of Modf, chosen by the compiler`: `ModfStruct`
- `reserved by the GLSL.std.450 specification, not a valid instruction`: `IMix`

### Input

Untested, by reason:

- `reserved by the GLSL.std.450 specification, not a valid instruction`: `IMix`
