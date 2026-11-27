<!-- Written from coverage.json by tools/coverage/docs.py when the Coverage workflow publishes. Do not edit. -->

# WebGL

Measured on commit [`d698cde`](https://github.com/AryanSingh2029/crosstl/commit/d698cde012f05b2329600c69dbcac6634b78bc09) at 2026-11-27T08:41:51Z (CrossTL 3.9.0) by the [Coverage workflow](https://github.com/AryanSingh2029/crosstl/actions/workflows/coverage.yml). The Coverage workflow writes this page from `coverage.json` each time it publishes; [COVERAGE.md](../COVERAGE.md) defines each outcome. Score = supported / (supported + refused + wrong).

The [backend guide](https://github.com/AryanSingh2029/crosstl/blob/main/docs/source/backends/webgl.rst) describes how CrossTL translates WebGL.

| Direction | Score | Supported | Refused | Wrong | Untested | Executed | Reference tool |
|---|---:|---:|---:|---:|---:|---|---|
| output | 100.0 % | 298 | 0 | 0 | 0 | compile-only | glslangValidator (Glslang Version: 11:16.6.0) |
| input | 100.0 % | 298 | 0 | 0 | 0 | compile-only | glslangValidator (Glslang Version: 11:16.6.0) |

## Feature lists

- [ANGLE's GLSL ES built-in function table](https://github.com/google/angle/blob/1ff891807e391d842c33d552ea26ab26b5341ef4/src/compiler/translator/builtin_function_declarations.txt), pinned at `1ff891807e39`

## By category

Each cell counts the supported features of a category over its supported, refused and wrong ones.

| Category | output | input |
|---|---:|---:|
| control-flow | 58/58 | 58/58 |
| function | 89/89 | 89/89 |
| graphics | 12/12 | 12/12 |
| operator | 50/50 | 50/50 |
| resource | 32/32 | 32/32 |
| stage | 2/2 | 2/2 |
| type | 55/55 | 55/55 |
