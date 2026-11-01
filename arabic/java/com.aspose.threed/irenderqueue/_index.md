---
title: "IRenderQueue"
second_title: "مرجع Aspose.3D لـ Java API"
description: "مُصوّر الكيان يستخدم هذه الطابور لإدارة مهام التصيير."
type: docs
weight: 248
url: /ar/java/com.aspose.threed/irenderqueue/
---
```
public interface IRenderQueue
```

مُصوّر الكيان يستخدم هذه الطابور لإدارة مهام التصيير.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)](#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-) | إضافة مهمة عرض إلى طابور العرض. |
### add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity) {#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-}
```
public abstract void add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)
```


إضافة مهمة عرض إلى طابور العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| groupId | [RenderQueueGroupId](../../com.aspose.threed/renderqueuegroupid) | في أي مجموعة من الطابور ستكون مهمة العرض |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) | مثيل خط الأنابيب المستخدم لهذه مهمة العرض |
| renderableResource | java.lang.Object | كائن مخصص سيتم إرساله إلى [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| الكيان الفرعي | int | فهرس الكيانات الفرعية، مفيد عندما يتكون الكيان من أكثر من مكوّن عرض فرعي. |

