---
title: "枚举 EntityRendererFeatures"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Render.EntityRendererFeatures 枚举。实体渲染器将提供的额外功能"
type: docs
weight: 1980
url: /zh/net/aspose.threed.render/entityrendererfeatures/
---
## EntityRendererFeatures enumeration

实体渲染器将提供的额外功能

```csharp
[Flags]
public enum EntityRendererFeatures : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | `0` | 无额外功能 |
| FrameBegin | `1` | 在渲染每个场景帧之前，[`EntityRenderer`](../entityrenderer/) 将监听 FrameBegin 回调 |
| FrameEnd | `2` | 在渲染每个场景帧之后，[`EntityRenderer`](../entityrenderer/) 将监听 FrameBegin 回调 |
| Shadowmap | `4` | 此渲染器可以在阴影图模式下工作 |

### 另请参见

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


