<!-- Written from coverage.json by tools/coverage/docs.py when the Coverage workflow publishes. Do not edit. -->

# GLSL

Measured on commit [`d698cde`](https://github.com/AryanSingh2029/crosstl/commit/d698cde012f05b2329600c69dbcac6634b78bc09) at 2026-11-27T08:41:51Z (CrossTL 3.9.0) by the [Coverage workflow](https://github.com/AryanSingh2029/crosstl/actions/workflows/coverage.yml). The Coverage workflow writes this page from `coverage.json` each time it publishes; [COVERAGE.md](../COVERAGE.md) defines each outcome. Score = supported / (supported + refused + wrong).

The [backend guide](https://github.com/AryanSingh2029/crosstl/blob/main/docs/source/backends/glsl.rst) describes how CrossTL translates GLSL.

| Direction | Score | Supported | Refused | Wrong | Untested | Executed | Reference tool |
|---|---:|---:|---:|---:|---:|---|---|
| output | 100.0 % | 604 | 0 | 0 | 0 | 391 on opengl-llvmpipe, 80 on vulkan-lavapipe | glslangValidator (Glslang Version: 11:16.6.0) |
| input | 100.0 % | 604 | 0 | 0 | 0 | 391 on opengl-llvmpipe, 80 on vulkan-lavapipe | glslangValidator (Glslang Version: 11:16.6.0) |

## Feature lists

- [GLSL 4.60 specification, chapter 8 (built-in functions)](https://github.com/KhronosGroup/GLSL/blob/0099bf83b0288469917fc2e2972cb0a2b74d6711/chapters/builtinfunctions.adoc), pinned at `0099bf83b028`
- [GL_EXT_shader_quad_control (quad votes)](https://github.com/KhronosGroup/GLSL/blob/0099bf83b0288469917fc2e2972cb0a2b74d6711/extensions/ext/GLSL_EXT_shader_quad_control.txt), pinned at `0099bf83b028`
- [GL_KHR_shader_subgroup (section 8.18, shader invocation group functions)](https://github.com/KhronosGroup/GLSL/blob/0099bf83b0288469917fc2e2972cb0a2b74d6711/extensions/khr/GL_KHR_shader_subgroup.txt), pinned at `0099bf83b028`
- [GL_NV_shader_subgroup_partitioned (partitioned subgroup operations)](https://github.com/KhronosGroup/GLSL/blob/0099bf83b0288469917fc2e2972cb0a2b74d6711/extensions/nv/GL_NV_shader_subgroup_partitioned.txt), pinned at `0099bf83b028`
- [GL_KHR_shader_subgroup_rotate (subgroup rotations)](https://github.com/KhronosGroup/GLSL/blob/0099bf83b0288469917fc2e2972cb0a2b74d6711/extensions/khr/GL_KHR_shader_subgroup_rotate.txt), pinned at `0099bf83b028`

## By category

Each cell counts the supported features of a category over its supported, refused and wrong ones.

| Category | output | input |
|---|---:|---:|
| compute | 28/28 | 28/28 |
| control-flow | 59/59 | 59/59 |
| function | 251/251 | 251/251 |
| graphics | 69/69 | 69/69 |
| operator | 51/51 | 51/51 |
| resource | 67/67 | 67/67 |
| stage | 14/14 | 14/14 |
| type | 65/65 | 65/65 |
