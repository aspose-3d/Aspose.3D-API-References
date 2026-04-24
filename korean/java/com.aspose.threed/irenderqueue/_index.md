---
title: IRenderQueue
second_title: Aspose.3D for Java API 레퍼런스
description: 엔티티 렌더러는 이 큐를 사용하여 렌더 작업을 관리합니다.
type: docs
weight: 248
url: /ko/java/com.aspose.threed/irenderqueue/
---
```
public interface IRenderQueue
```

엔티티 렌더러는 이 큐를 사용하여 렌더 작업을 관리합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)](#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-) | 렌더 작업을 렌더 큐에 추가합니다. |
### add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity) {#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-}
```
public abstract void add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)
```


렌더 작업을 렌더 큐에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| groupId | [RenderQueueGroupId](../../com.aspose.threed/renderqueuegroupid) | 렌더 작업이 속할 큐의 그룹 |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) | 이 렌더 작업에 사용되는 파이프라인 인스턴스 |
| renderableResource | java.lang.Object | 다음으로 전송될 사용자 정의 객체: [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| subEntity | int | 하위 엔티티의 인덱스, 엔티티가 하나 이상의 하위 렌더링 가능한 구성 요소로 구성될 때 유용합니다. |

