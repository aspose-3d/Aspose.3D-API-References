---
title: "EntityRenderer.RenderEntity"
second_title: "Aspose.3D for .NET API 参考"
description: "EntityRenderer 方法。每个推送到 IRenderQueue 的渲染任务都会有相应的 RenderEntity 调用来执行具体的渲染工作"
type: docs
weight: 70
url: /zh/net/aspose.threed.render/entityrenderer/renderentity/
---
## EntityRenderer.RenderEntity method

每个推送到 [`IRenderQueue`](../../irenderqueue/) 的渲染任务都会有相应的 RenderEntity 调用来执行具体的渲染工作。

```csharp
public virtual void RenderEntity(Renderer renderer, ICommandList commandList, Node node, 
    object renderableResource, int subEntity)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 渲染器 | 渲染器 | 渲染器 |
| commandList | ICommandList | 用于记录渲染命令的 commandList |
| 节点 | 节点 | 将传递给待渲染实体的 PrepareRenderQueue 的相同节点 |
| renderableResource | 对象 | 在 PrepareRenderQueue 期间传递给 IRenderQueue 的自定义对象 |
| 子实体 | Int32 | 传递给 IRenderQueue 的子实体的索引 |

### 另请参见

* class [Renderer](../../renderer/)
* interface [ICommandList](../../icommandlist/)
* class [Node](../../../aspose.threed/node/)
* class [EntityRenderer](../)
* namespace [Aspose.ThreeD.Render](../../entityrenderer/)
* assembly [Aspose.3D](../../../)


