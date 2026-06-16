---
title: "EntityRenderer.RenderEntity"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة EntityRenderer. كل مهمة تصيير تُدفع إلى IRenderQueue سيكون لها استدعاء RenderEntity المقابل لتنفيذ مهمة التصيير الفعلية"
type: docs
weight: 70
url: /ar/net/aspose.threed.render/entityrenderer/renderentity/
---
## EntityRenderer.RenderEntity method

كل مهمة تصيير تُدفع إلى [`IRenderQueue`](../../irenderqueue/) سيكون لها استدعاء RenderEntity المقابل لتنفيذ مهمة التصيير الفعلية.

```csharp
public virtual void RenderEntity(Renderer renderer, ICommandList commandList, Node node, 
    object renderableResource, int subEntity)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المُصَدِّر | المُصَدِّر | المُعالج |
| قائمة الأوامر | ICommandList | قائمة الأوامر المستخدمة لتسجيل أوامر التصيير |
| عقدة | عقدة | نفس العقدة التي تم تمريرها إلى PrepareRenderQueue للكيان الذي سيتم تصييره |
| المورد القابل للتصيير | كائن | الكائن المخصص الذي تم تمريره إلى IRenderQueue أثناء PrepareRenderQueue |
| subEntity | Int32 | فهرس الكيان الفرعي الذي تم تمريره إلى IRenderQueue |

### انظر أيضًا

* class [Renderer](../../renderer/)
* interface [ICommandList](../../icommandlist/)
* class [Node](../../../aspose.threed/node/)
* class [EntityRenderer](../)
* namespace [Aspose.ThreeD.Render](../../entityrenderer/)
* assembly [Aspose.3D](../../../)


