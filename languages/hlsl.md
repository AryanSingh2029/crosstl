<!-- Written from coverage.json by tools/coverage/docs.py when the Coverage workflow publishes. Do not edit. -->

# HLSL

Measured on commit [`d698cde`](https://github.com/AryanSingh2029/crosstl/commit/d698cde012f05b2329600c69dbcac6634b78bc09) at 2026-11-27T08:41:51Z (CrossTL 3.9.0) by the [Coverage workflow](https://github.com/AryanSingh2029/crosstl/actions/workflows/coverage.yml). The Coverage workflow writes this page from `coverage.json` each time it publishes; [COVERAGE.md](../COVERAGE.md) defines each outcome. Score = supported / (supported + refused + wrong).

The [backend guide](https://github.com/AryanSingh2029/crosstl/blob/main/docs/source/backends/directx.rst) describes how CrossTL translates HLSL.

| Direction | Score | Supported | Refused | Wrong | Untested | Executed | Reference tool |
|---|---:|---:|---:|---:|---:|---|---|
| output | 99.9 % | 830 | 0 | 1 | 0 | 530 on d3d12-warp, 360 on vulkan-lavapipe | dxc (libdxcompiler.so: 1.9(5191-d355aa83)(1.9.0.5191)) |
| input | 100.0 % | 831 | 0 | 0 | 0 | 531 on d3d12-warp, 361 on vulkan-lavapipe | dxc (libdxcompiler.so: 1.9(5191-d355aa83)(1.9.0.5191)) |

## Feature lists

- [DXC v1.9.2602.24 intrinsic table](https://github.com/microsoft/DirectXShaderCompiler/blob/d355aa8364d34df3f0822ba0de8d1dfc75ae6f48/utils/hct/gen_intrin_main.txt), pinned at `d355aa8364d3`
- [DXC v1.10.2605.37 (Shader Model 6.10 preview) intrinsic table](https://github.com/microsoft/DirectXShaderCompiler/blob/c4d8f4f99aa221da58cd540bf2099a2889632ab6/utils/hct/gen_intrin_main.txt), pinned at `c4d8f4f99aa2`

## By category

Each cell counts the supported features of a category over its supported, refused and wrong ones.

| Category | output | input |
|---|---:|---:|
| compute | 13/13 | 13/13 |
| control-flow | 62/62 | 62/62 |
| function | 205/205 | 205/205 |
| graphics | 63/63 | 63/63 |
| method | 291/291 | 291/291 |
| operator | 50/50 | 50/50 |
| resource | 66/67 | 67/67 |
| stage | 14/14 | 14/14 |
| type | 66/66 | 66/66 |

## Gaps

A diagnostic drops its line numbers and writes the probe's own variables as `<probe>`, and one that several features share writes each feature's name as `<feature>`.

### Output

Wrong, by cause ([open bug issues](https://github.com/AryanSingh2029/crosstl/issues?q=is:issue%20is:open%20label:coverage%20label:bug%20label:backend:hlsl%20label:direction:output)):

- `on vulkan-lavapipe as SPIR-V from dxc, the translation binds other resources than the native probe`: `read-only-buffer`
