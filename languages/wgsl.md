<!-- Written from coverage.json by tools/coverage/docs.py when the Coverage workflow publishes. Do not edit. -->

# WGSL

Measured on commit [`d698cde`](https://github.com/AryanSingh2029/crosstl/commit/d698cde012f05b2329600c69dbcac6634b78bc09) at 2026-11-27T08:41:51Z (CrossTL 3.9.0) by the [Coverage workflow](https://github.com/AryanSingh2029/crosstl/actions/workflows/coverage.yml). The Coverage workflow writes this page from `coverage.json` each time it publishes; [COVERAGE.md](../COVERAGE.md) defines each outcome. Score = supported / (supported + refused + wrong).

The [backend guide](https://github.com/AryanSingh2029/crosstl/blob/main/docs/source/backends/wgsl.rst) describes how CrossTL translates WGSL.

| Direction | Score | Supported | Refused | Wrong | Untested | Executed | Reference tool |
|---|---:|---:|---:|---:|---:|---|---|
| output | 100.0 % | 403 | 0 | 0 | 1 | 332 on vulkan-lavapipe | naga (30.0.1) |
| input | 100.0 % | 400 | 0 | 0 | 4 | 332 on vulkan-lavapipe | naga (30.0.1) |

## Feature lists

- [Tint's WGSL built-in function definitions](https://github.com/google/dawn/blob/ff7c6960f62d4249f967a78448918eec21705a86/src/tint/lang/wgsl/wgsl.def), pinned at `ff7c6960f62d`

## By category

Each cell counts the supported features of a category over its supported, refused and wrong ones.

| Category | output | input |
|---|---:|---:|
| compute | 22/22 | 22/22 |
| control-flow | 56/56 | 56/56 |
| function | 145/145 | 142/142 |
| graphics | 16/16 | 16/16 |
| operator | 48/48 | 48/48 |
| resource | 57/57 | 57/57 |
| stage | 3/3 | 3/3 |
| type | 56/56 | 56/56 |

## Gaps

A diagnostic drops its line numbers and writes the probe's own variables as `<probe>`, and one that several features share writes each feature's name as `<feature>`.

### Output

Untested, by reason:

- `the probe itself is rejected: error: no definition in scope for identifier: 'subgroupElect'`: `subgroupElect`

### Input

Untested, by reason:

- `no probe for parameters of type __atomic_compare_exchange_result<T>`: `atomicCompareExchangeWeak`
- `no probe for parameters of type __frexp_result_vec<N, T>`: `frexp`
- `no probe for parameters of type __modf_result_vec<N, T>`: `modf`
- `the probe itself is rejected: error: no definition in scope for identifier: 'subgroupElect'`: `subgroupElect`
