---
title: "EntityRenderer.RenderEntity"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة EntityRenderer. كل مهمة عرض تُدفع إلى IRenderQueue ستحصل على استدعاء RenderEntity المقابل لتنفيذ مهمة العرض الفعلية"
type: docs
weight: 70
url: /ar/net/aspose.threed.render/entityrenderer/renderentity/
---
## EntityRenderer.RenderEntity method

كل مهمة عرض تُدفع إلى [`IRenderQueue`](../../irenderqueue/) ستحصل على استدعاء RenderEntity المقابل لتنفيذ مهمة العرض الفعلية.

```csharp
public virtual void RenderEntity(Renderer renderer, ICommandList commandList, Node node, 
    object renderableResource, int subEntity)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المُعالج | المُعالج | العارض |
| commandList | ICommandList | قائمة الأوامر commandList المستخدمة لتسجيل أوامر العرض |
| العقدة | Node | نفس العقدة التي تم تمريرها إلى PrepareRenderQueue للكيان الذي سيتم عرضه |
| renderableResource | كائن | الكائن المخصص الذي تم تمريره إلى IRenderQueue أثناء PrepareRenderQueue |
| subEntity | Int32 | فهرس الكيان الفرعي الذي تم تمريره إلى IRenderQueue |

### انظر أيضًا

* class [Renderer](../../renderer/)
* interface [ICommandList](../../icommandlist/)
* class [Node](../../../aspose.threed/node/)
* class [EntityRenderer](../)
* namespace [Aspose.ThreeD.Render](../../entityrenderer/)
* assembly [Aspose.3D](../../../)


