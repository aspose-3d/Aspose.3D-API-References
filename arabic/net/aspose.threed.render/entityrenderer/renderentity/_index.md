---
title: RenderEntity
second_title: Aspose.3D لمرجع .NET API
description: يتم دفع كل مهمة تصيير إلى ملفIRenderQueueaspose.threed.render/irenderqueue سيكون له استدعاء RenderEntity مطابق لأداء مهمة التقديم الملموسة.
type: docs
weight: 70
url: /ar/net/aspose.threed.render/entityrenderer/renderentity/
---
## EntityRenderer.RenderEntity method

يتم دفع كل مهمة تصيير إلى ملف[`IRenderQueue`](../../irenderqueue) سيكون له استدعاء RenderEntity مطابق لأداء مهمة التقديم الملموسة.

```csharp
public virtual void RenderEntity(Renderer renderer, ICommandList commandList, Node node, 
    object renderableResource, int subEntity)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| renderer | Renderer | العارض |
| commandList | ICommandList | يتم استخدام قائمة الأوامر لتسجيل أوامر العرض |
| node | Node | نفس العقدة التي تم تمريرها إلى PrepareRenderQueue للكيان الذي سيتم عرضه |
| renderableResource | Object | الكائن المخصص الذي تم تمريره إلى IRenderQueue أثناء PrepareRenderQueue |
| subEntity | Int32 | فهرس الكيان الفرعي الذي تم تمريره إلى IRenderQueue |

### أنظر أيضا

* class [Renderer](../../renderer)
* interface [ICommandList](../../icommandlist)
* class [Node](../../../aspose.threed/node)
* class [EntityRenderer](../../entityrenderer)
* مساحة الاسم [Aspose.ThreeD.Render](../../entityrenderer)
* المجسم [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
