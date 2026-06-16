---
title: "فئة Renderer"
second_title: "مرجع Aspose.3D for .NET API"
description: "فئة Aspose.ThreeD.Render.Renderer. السياق حول المُصنِّف"
type: docs
weight: 2340
url: /ar/net/aspose.threed.render/renderer/
---
## Renderer class

السياق المتعلق بالعارض.

```csharp
public abstract class Renderer : IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AssetDirectories](../../aspose.threed.render/renderer/assetdirectories/) { get; } | الدلائل التي تخزن الأصول الخارجية |
| [EnableShadows](../../aspose.threed.render/renderer/enableshadows/) { get; set; } | يحصل أو يضبط ما إذا كان يجب تمكين الظلال. |
| [FallbackEntityRenderer](../../aspose.threed.render/renderer/fallbackentityrenderer/) { get; set; } | يحصل أو يضبط مُصنِّف الكيان الاحتياطي عندما لا يكون للكيان مُصنِّف خاص معرف. |
| virtual [Frustum](../../aspose.threed.render/renderer/frustum/) { get; set; } | يحصل أو يضبط المخروط الذي يُستخدم لتوفير مصفوفة العرض. |
| virtual [Material](../../aspose.threed.render/renderer/material/) { get; set; } | يحصل أو يضبط المادة التي تُستخدم لتوفير معلومات المادة المستخدمة بواسطة المُظللات. |
| [Node](../../aspose.threed.render/renderer/node/) { get; set; } | يحصل أو يضبط مثيل [`Node`](./node/) المستخدم لتوفير مصفوفة التحويل العالمية. |
| [PostProcessings](../../aspose.threed.render/renderer/postprocessings/) { get; } | سلسلة المعالجة اللاحقة النشطة |
| [PresetShaders](../../aspose.threed.render/renderer/presetshaders/) { get; set; } | يحصل أو يضبط مجموعة المُظلِّر المحددة مسبقًا |
| abstract [RenderFactory](../../aspose.threed.render/renderer/renderfactory/) { get; } | يحصل على المصنع لبناء الكائنات المتعلقة بالعرض. |
| [RenderStage](../../aspose.threed.render/renderer/renderstage/) { get; } | يحصل على مرحلة العرض الحالية. |
| [RenderTarget](../../aspose.threed.render/renderer/rendertarget/) { get; } | حدد هدف العرض الذي ستُجرى عليه عمليات العرض التالية. |
| [Shader](../../aspose.threed.render/renderer/shader/) { get; set; } | يحصل أو يضبط مثيل المُظلِّل المستخدم لتصوير الهندسة. |
| [ShaderSet](../../aspose.threed.render/renderer/shaderset/) { get; set; } | يحصل أو يضبط مجموعة المُظلِّلات التي تُستخدم لتصوير المشهد |
| [Variables](../../aspose.threed.render/renderer/variables/) { get; } | الوصول إلى المتغيّرات الداخلية المستخدمة في العرض |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateRenderer](../../aspose.threed.render/renderer/createrenderer/)() | ينشئ `Renderer` جديدًا باستخدام ملف تعريف افتراضي. |
| virtual [ClearCache](../../aspose.threed.render/renderer/clearcache/)() | امسح الذاكرة المؤقتة يدويًا. سيقوم Aspose.3D بتخزين بعض الكائنات مثل المواد/الهياكل في أنواع داخلية متوافقة مع خط أنابيب العرض. يجب استدعاؤها يدويًا عندما يطرأ تغييرات كبيرة على المشهد. |
| [Dispose](../../aspose.threed.render/renderer/dispose/)() | تخلص من `Renderer` وجميع الموارد المرتبطة. |
| abstract [Execute](../../aspose.threed.render/renderer/execute/)(PostProcessing, IRenderTarget) | نفّذ معالجة لاحقة على هدف العرض المحدد. |
| [GetPostProcessing](../../aspose.threed.render/renderer/getpostprocessing/)(string) | يحصل على معالج لاحق مدمج يدعمه المُصنِّف. |
| virtual [RegisterEntityRenderer](../../aspose.threed.render/renderer/registerentityrenderer/)(EntityRenderer) | سجّل مُصنِّف الكيان للكيان المحدد. |
| virtual [Render](../../aspose.threed.render/renderer/render/)(IRenderTarget) | اعرض الهدف المحدد. |

### انظر أيضًا

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


