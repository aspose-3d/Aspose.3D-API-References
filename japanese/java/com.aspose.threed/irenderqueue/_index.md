---
title: IRenderQueue
second_title: Aspose.3D for Java API リファレンス
description: エンティティレンダラーはこのキューを使用してレンダリングタスクを管理します。
type: docs
weight: 248
url: /ja/java/com.aspose.threed/irenderqueue/
---
```
public interface IRenderQueue
```

エンティティレンダラーはこのキューを使用してレンダリングタスクを管理します。
## Methods

| Method | 説明 |
| --- | --- |
| [add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)](#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-) | レンダーキューにレンダータスクを追加します。 |
### add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity) {#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-}
```
public abstract void add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)
```


レンダーキューにレンダータスクを追加します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| groupId | [RenderQueueGroupId](../../com.aspose.threed/renderqueuegroupid) | レンダータスクが所属するキューのグループ |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) | このレンダータスクに使用されるパイプラインインスタンス |
| renderableResource | java.lang.Object | カスタムオブジェクトは [EntityRenderer](../../com.aspose.threed/entityrenderer) に送信されます |
| subEntity | int | サブエンティティのインデックス、エンティティが複数のサブレンダラブルコンポーネントで構成されている場合に便利です。 |

