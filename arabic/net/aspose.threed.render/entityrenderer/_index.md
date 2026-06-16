---
title: "فئة EntityRenderer"
second_title: "مرجع Aspose.3D for .NET API"
description: "فئة Aspose.ThreeD.Render.EntityRenderer. قم بإنشاء فئة فرعية من هذه لتنفيذ العرض لأنواع مختلفة من الكيانات."
type: docs
weight: 1970
url: /ar/net/aspose.threed.render/entityrenderer/
---
## EntityRenderer class

قم بإنشاء فئة فرعية من هذه لتنفيذ العرض لأنواع مختلفة من الكيانات.

```csharp
public class EntityRenderer
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [EntityRenderer](entityrenderer/#constructor)(string) | منشئ `EntityRenderer` |
| [EntityRenderer](entityrenderer/#constructor_1)(string, EntityRendererFeatures) | منشئ `EntityRenderer` |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Dispose](../../aspose.threed.render/entityrenderer/dispose/)() | يتم التخلص من عارض الكيان، أطلق الموارد المشتركة. |
| virtual [FrameBegin](../../aspose.threed.render/entityrenderer/framebegin/)(Renderer, IRenderQueue) | ابدأ عرض إطار |
| virtual [FrameEnd](../../aspose.threed.render/entityrenderer/frameend/)(Renderer, IRenderQueue) | ينتهي عرض الإطار |
| virtual [Initialize](../../aspose.threed.render/entityrenderer/initialize/)(Renderer) | تهيئة عارض الكيان |
| virtual [PrepareRenderQueue](../../aspose.threed.render/entityrenderer/preparerenderqueue/)(Renderer, IRenderQueue, Node, Entity) | حضّر أوامر العرض للزوج المحدد من العقدة/الكيان. |
| virtual [RenderEntity](../../aspose.threed.render/entityrenderer/renderentity/)(Renderer, ICommandList, Node, object, int) | كل مهمة عرض تُدفع إلى [`IRenderQueue`](../irenderqueue/) ستحصل على استدعاء RenderEntity المقابل لتنفيذ مهمة العرض الفعلية. |
| virtual [ResetSceneCache](../../aspose.threed.render/entityrenderer/resetscenecache/)() | المشهد تغير أو أزيل، يلزم التخلص من موارد العرض على مستوى المشهد في هذا. |

### انظر أيضًا

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


