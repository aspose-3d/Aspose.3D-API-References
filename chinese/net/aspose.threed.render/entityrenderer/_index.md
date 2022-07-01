---
title: EntityRenderer
second_title: Aspose.3D for .NET API 参考
description: 子类这个以实现不同类型实体的渲染
type: docs
weight: 1770
url: /zh/net/aspose.threed.render/entityrenderer/
---
## EntityRenderer class

子类这个以实现不同类型实体的渲染。

```csharp
public class EntityRenderer
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EntityRenderer](entityrenderer#constructor)(string) | 的构造函数 [`EntityRenderer`](../entityrenderer) |
| [EntityRenderer](entityrenderer#constructor_1)(string, EntityRendererFeatures) | 的构造函数 [`EntityRenderer`](../entityrenderer) |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [Dispose](../../aspose.threed.render/entityrenderer/dispose)() | 实体渲染器正在被释放，释放共享资源。 |
| virtual [FrameBegin](../../aspose.threed.render/entityrenderer/framebegin)(Renderer, IRenderQueue) | 开始渲染一帧 |
| virtual [FrameEnd](../../aspose.threed.render/entityrenderer/frameend)(Renderer, IRenderQueue) | 结束渲染一帧 |
| virtual [Initialize](../../aspose.threed.render/entityrenderer/initialize)(Renderer) | 初始化实体渲染器 |
| virtual [PrepareRenderQueue](../../aspose.threed.render/entityrenderer/preparerenderqueue)(Renderer, IRenderQueue, Node, Entity) | 为指定的节点/实体对准备渲染命令。 |
| virtual [RenderEntity](../../aspose.threed.render/entityrenderer/renderentity)(Renderer, ICommandList, Node, object, int) | 每个推送到[`IRenderQueue`](../irenderqueue)的渲染任务都会有一个对应的 RenderEntity 调用 执行具体的渲染工作。 |
| virtual [ResetSceneCache](../../aspose.threed.render/entityrenderer/resetscenecache)() | 场景已更改或移除，需要在此 |

### 也可以看看

* 命名空间 [Aspose.ThreeD.Render](../../aspose.threed.render)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->