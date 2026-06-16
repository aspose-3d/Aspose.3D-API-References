---
title: "类 EntityRenderer"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Render.EntityRenderer 类。子类化此类以实现不同类型实体的渲染"
type: docs
weight: 1970
url: /zh/net/aspose.threed.render/entityrenderer/
---
## EntityRenderer class

子类化此类以实现对不同种类实体的渲染。

```csharp
public class EntityRenderer
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EntityRenderer](entityrenderer/#constructor)(string) | `EntityRenderer` 的构造函数 |
| [EntityRenderer](entityrenderer/#constructor_1)(string, EntityRendererFeatures) | `EntityRenderer` 的构造函数 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Dispose](../../aspose.threed.render/entityrenderer/dispose/)() | 实体渲染器正在被释放，释放共享资源。 |
| virtual [FrameBegin](../../aspose.threed.render/entityrenderer/framebegin/)(Renderer, IRenderQueue) | 开始渲染帧 |
| virtual [FrameEnd](../../aspose.threed.render/entityrenderer/frameend/)(Renderer, IRenderQueue) | 结束渲染帧 |
| virtual [Initialize](../../aspose.threed.render/entityrenderer/initialize/)(Renderer) | 初始化实体渲染器 |
| virtual [PrepareRenderQueue](../../aspose.threed.render/entityrenderer/preparerenderqueue/)(Renderer, IRenderQueue, Node, Entity) | 为指定的节点/实体对准备渲染命令。 |
| virtual [RenderEntity](../../aspose.threed.render/entityrenderer/renderentity/)(Renderer, ICommandList, Node, object, int) | 推送到 [`IRenderQueue`](../irenderqueue/) 的每个渲染任务都将拥有相应的 RenderEntity 调用来执行具体的渲染工作。 |
| virtual [ResetSceneCache](../../aspose.threed.render/entityrenderer/resetscenecache/)() | 场景已更改或被移除，需要在此处释放场景级别的渲染资源 |

### 另请参见

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


