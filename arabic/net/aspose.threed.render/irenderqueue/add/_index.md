---
title: "IRenderQueue.Add"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة IRenderQueue. أضف مهمة العرض إلى طابور العرض"
type: docs
weight: 10
url: /ar/net/aspose.threed.render/irenderqueue/add/
---
## IRenderQueue.Add method

أضف مهمة العرض إلى طابور العرض.

```csharp
public void Add(RenderQueueGroupId groupId, IPipeline pipeline, object renderableResource, 
    int subEntity)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| groupId | RenderQueueGroupId | المجموعة التي ستنتمي إليها مهمة العرض في الطابور |
| خط الأنابيب | IPipeline | مثيل خط الأنابيب المستخدم لهذه مهمة العرض |
| renderableResource | Object | كائن مخصص سيتم إرساله إلى [`RenderEntity`](../../entityrenderer/renderentity/) |
| subEntity | Int32 | فهرس الكيانات الفرعية، مفيد عندما يتكون الكيان من أكثر من مكوّن عرض فرعي واحد. |

### انظر أيضًا

* enum [RenderQueueGroupId](../../renderqueuegroupid/)
* interface [IPipeline](../../ipipeline/)
* interface [IRenderQueue](../)
* namespace [Aspose.ThreeD.Render](../../irenderqueue/)
* assembly [Aspose.3D](../../../)


