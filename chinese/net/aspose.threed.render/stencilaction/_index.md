---
title: "枚举 StencilAction"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Render.StencilAction 枚举。模板测试操作"
type: docs
weight: 2430
url: /zh/net/aspose.threed.render/stencilaction/
---
## StencilAction enumeration

模板测试操作

```csharp
public enum StencilAction
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Keep | `0` | 保持当前值 |
| Zero | `1` | 将模板缓冲区的值设为 0 |
| Replace | `2` | 将模板缓冲区设置为在 [`StencilReference`](../renderstate/stencilreference/) 中定义的引用 |
| Increment | `3` | 递增当前模板缓冲区的值，限制在最大值。 |
| IncrementWrap | `4` | 递增当前模板缓冲区的值，当达到最大值时将其回绕至零。 |
| Decrement | `5` | 递增当前模板缓冲区的值，限制为 0。 |
| DecrementWrap | `6` | 递减当前模板缓冲区的值，当达到零时将其回绕至最大值。 |
| Invert | `7` | 按位取反当前模板缓冲区的值。 |

### 另请参见

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


