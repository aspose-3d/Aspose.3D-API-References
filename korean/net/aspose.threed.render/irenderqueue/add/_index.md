---
title: Add
second_title: .NET API 참조용 Aspose.3D
description: 렌더링 대기열에 렌더링 작업을 추가합니다.
type: docs
weight: 10
url: /ko/net/aspose.threed.render/irenderqueue/add/
---
## IRenderQueue.Add method

렌더링 대기열에 렌더링 작업을 추가합니다.

```csharp
public void Add(RenderQueueGroupId groupId, IPipeline pipeline, object renderableResource, 
    int subEntity)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| groupId | RenderQueueGroupId | 렌더링 작업이 있을 대기열 그룹 |
| pipeline | IPipeline | 이 렌더링 작업에 사용되는 파이프라인 인스턴스 |
| renderableResource | Object | 보낼 사용자 지정 개체[`RenderEntity`](../../entityrenderer/renderentity/) |
| subEntity | Int32 | 엔티티가 둘 이상의 렌더링 가능한 하위 구성요소로 구성되어 있을 때 유용한 하위 엔티티의 인덱스입니다. |

### 또한보십시오

* enum [RenderQueueGroupId](../../renderqueuegroupid/)
* interface [IPipeline](../../ipipeline/)
* interface [IRenderQueue](../)
* 네임스페이스 [Aspose.ThreeD.Render](../../irenderqueue/)
* 집회 [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
