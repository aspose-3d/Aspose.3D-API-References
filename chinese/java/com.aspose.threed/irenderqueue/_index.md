---
title: "IRenderQueue"
second_title: "Aspose.3D for Java API 参考"
description: "实体渲染器使用此队列来管理渲染任务。"
type: docs
weight: 248
url: /zh/java/com.aspose.threed/irenderqueue/
---
```
public interface IRenderQueue
```

实体渲染器使用此队列来管理渲染任务。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)](#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-) | 将渲染任务添加到渲染队列。 |
### add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity) {#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-}
```
public abstract void add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)
```


将渲染任务添加到渲染队列。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| groupId | [RenderQueueGroupId](../../com.aspose.threed/renderqueuegroupid) | 渲染任务将在队列的哪个组中 |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) | 用于此渲染任务的管线实例 |
| renderableResource | java.lang.Object | 将发送到 [EntityRenderer](../../com.aspose.threed/entityrenderer) 的自定义对象 |
| subEntity | int | 子实体的索引，当实体由多个子可渲染组件组成时很有用。 |

