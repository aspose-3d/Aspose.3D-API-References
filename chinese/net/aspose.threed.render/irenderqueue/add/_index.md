---
title: "IRenderQueue.Add"
second_title: "Aspose.3D for .NET API 参考"
description: "IRenderQueue 方法。将渲染任务添加到渲染队列"
type: docs
weight: 10
url: /zh/net/aspose.threed.render/irenderqueue/add/
---
## IRenderQueue.Add method

将渲染任务添加到渲染队列。

```csharp
public void Add(RenderQueueGroupId groupId, IPipeline pipeline, object renderableResource, 
    int subEntity)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| groupId | RenderQueueGroupId | 渲染任务将在队列的哪个组中 |
| pipeline | IPipeline | 用于此渲染任务的管线实例 |
| renderableResource | Object | 将发送给 [`RenderEntity`](../../entityrenderer/renderentity/) 的自定义对象 |
| 子实体 | Int32 | 子实体的索引，当实体由多个子可渲染组件组成时很有用。 |

### 另请参见

* enum [RenderQueueGroupId](../../renderqueuegroupid/)
* interface [IPipeline](../../ipipeline/)
* interface [IRenderQueue](../)
* namespace [Aspose.ThreeD.Render](../../irenderqueue/)
* assembly [Aspose.3D](../../../)


