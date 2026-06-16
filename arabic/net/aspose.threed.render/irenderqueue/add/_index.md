---
title: "IRenderQueue.Add"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة IRenderQueue. إضافة مهمة عرض إلى طابور العرض"
type: docs
weight: 10
url: /ar/net/aspose.threed.render/irenderqueue/add/
---
## IRenderQueue.Add method

أضف مهمة عرض إلى قائمة العرض.

```csharp
public void Add(RenderQueueGroupId groupId, IPipeline pipeline, object renderableResource, 
    int subEntity)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| groupId | RenderQueueGroupId | أي مجموعة من الطابور ستكون مهمة العرض فيها |
| خط الأنابيب | IPipeline | مثيل خط الأنابيب المستخدم لهذه مهمة العرض |
| renderableResource | Object | كائن مخصص سيتم إرساله إلى [`RenderEntity`](../../entityrenderer/renderentity/) |
| subEntity | Int32 | فهرس الكيانات الفرعية، مفيد عندما يتكون الكيان من أكثر من مكوّن فرعي قابل للتصوير. |

### انظر أيضًا

* enum [RenderQueueGroupId](../../renderqueuegroupid/)
* interface [IPipeline](../../ipipeline/)
* interface [IRenderQueue](../)
* namespace [Aspose.ThreeD.Render](../../irenderqueue/)
* assembly [Aspose.3D](../../../)


