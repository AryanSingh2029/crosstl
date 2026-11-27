<!-- Written from coverage.json by tools/coverage/docs.py when the Coverage workflow publishes. Do not edit. -->

# HIP

Measured on commit [`d698cde`](https://github.com/AryanSingh2029/crosstl/commit/d698cde012f05b2329600c69dbcac6634b78bc09) at 2026-11-27T08:41:51Z (CrossTL 3.9.0) by the [Coverage workflow](https://github.com/AryanSingh2029/crosstl/actions/workflows/coverage.yml). The Coverage workflow writes this page from `coverage.json` each time it publishes; [COVERAGE.md](../COVERAGE.md) defines each outcome. Score = supported / (supported + refused + wrong).

The [backend guide](https://github.com/AryanSingh2029/crosstl/blob/main/docs/source/backends/hip.rst) describes how CrossTL translates HIP.

| Direction | Score | Supported | Refused | Wrong | Untested | Executed | Reference tool |
|---|---:|---:|---:|---:|---:|---|---|
| output | 100.0 % | 567 | 0 | 0 | 0 | compile-only | hipcc (HIP version: 5.7.31921-0) |
| input | 100.0 % | 567 | 0 | 0 | 0 | compile-only | hipcc (HIP version: 5.7.31921-0) |

## Feature lists

- [LLVM 17.0.6 device-side HIP math functions and intrinsics](https://github.com/llvm/llvm-project/blob/6009708b4367171ccdbf4b5905cb6a803753fe18/clang/lib/Headers/__clang_hip_math.h), pinned at `6009708b4367`
- [ROCm 5.7.1 HIP atomic functions](https://github.com/ROCm/clr/blob/1949b1621a802ffb1492616adbae6154bfbe64ef/hipamd/include/hip/amd_detail/amd_hip_atomic.h), pinned at `1949b1621a80`
- [ROCm 5.7.1 HIP device functions (integer intrinsics, conversions, barriers)](https://github.com/ROCm/clr/blob/1949b1621a802ffb1492616adbae6154bfbe64ef/hipamd/include/hip/amd_detail/amd_device_functions.h), pinned at `1949b1621a80`
- [ROCm 5.7.1 HIP warp shuffles and lane permutes](https://github.com/ROCm/clr/blob/1949b1621a802ffb1492616adbae6154bfbe64ef/hipamd/include/hip/amd_detail/amd_warp_functions.h), pinned at `1949b1621a80`

## By category

Each cell counts the supported features of a category over its supported, refused and wrong ones.

| Category | output | input |
|---|---:|---:|
| compute | 18/18 | 18/18 |
| control-flow | 60/60 | 60/60 |
| function | 361/361 | 361/361 |
| operator | 34/34 | 34/34 |
| resource | 45/45 | 45/45 |
| stage | 1/1 | 1/1 |
| type | 48/48 | 48/48 |
