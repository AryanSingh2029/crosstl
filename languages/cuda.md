<!-- Written from coverage.json by tools/coverage/docs.py when the Coverage workflow publishes. Do not edit. -->

# CUDA

Measured on commit [`d698cde`](https://github.com/AryanSingh2029/crosstl/commit/d698cde012f05b2329600c69dbcac6634b78bc09) at 2026-11-27T08:41:51Z (CrossTL 3.9.0) by the [Coverage workflow](https://github.com/AryanSingh2029/crosstl/actions/workflows/coverage.yml). The Coverage workflow writes this page from `coverage.json` each time it publishes; [COVERAGE.md](../COVERAGE.md) defines each outcome. Score = supported / (supported + refused + wrong).

The [backend guide](https://github.com/AryanSingh2029/crosstl/blob/main/docs/source/backends/cuda.rst) describes how CrossTL translates CUDA.

| Direction | Score | Supported | Refused | Wrong | Untested | Executed | Reference tool |
|---|---:|---:|---:|---:|---:|---|---|
| output | 100.0 % | 718 | 0 | 0 | 0 | compile-only | nvcc: NVIDIA (R) Cuda compiler driver |
| input | 100.0 % | 718 | 0 | 0 | 0 | compile-only | nvcc: NVIDIA (R) Cuda compiler driver |

## Feature lists

- [LLVM 23.1.3 device-side CUDA Math API wrappers](https://github.com/llvm/llvm-project/blob/0d261d1ca552c95a8f007e061c787ac7132fbcbc/clang/lib/Headers/__clang_cuda_math.h), pinned at `0d261d1ca552`
- [LLVM 23.1.3 CUDA intrinsic and atomic wrappers](https://github.com/llvm/llvm-project/blob/0d261d1ca552c95a8f007e061c787ac7132fbcbc/clang/lib/Headers/__clang_cuda_device_functions.h), pinned at `0d261d1ca552`
- [LLVM 23.1.3 CUDA warp, cache-hinted load and store, and funnel shift intrinsics](https://github.com/llvm/llvm-project/blob/0d261d1ca552c95a8f007e061c787ac7132fbcbc/clang/lib/Headers/__clang_cuda_intrinsics.h), pinned at `0d261d1ca552`

## By category

Each cell counts the supported features of a category over its supported, refused and wrong ones.

| Category | output | input |
|---|---:|---:|
| compute | 18/18 | 18/18 |
| control-flow | 60/60 | 60/60 |
| function | 512/512 | 512/512 |
| operator | 34/34 | 34/34 |
| resource | 45/45 | 45/45 |
| stage | 1/1 | 1/1 |
| type | 48/48 | 48/48 |
