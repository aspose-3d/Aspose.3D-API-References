---
title: "الواجهة ITextureUnit"
second_title: "مرجع Aspose.3D for .NET API"
description: "الواجهة Aspose.ThreeD.Render.ITextureUnit. يمثل ITextureUnit نسيجًا في الذاكرة يتم مشاركته بين GPU وCPU ويمكن للـ shader أن ي sampled حيث أن Texture يمثل فقط مرجعًا إلى ملف خارجي. يمكن العثور على مزيد من التفاصيل في https//en.wikipedia.org/wiki/Texture_mapping_unit"
type: docs
weight: 2170
url: /ar/net/aspose.threed.render/itextureunit/
---
## ITextureUnit interface

`ITextureUnit` يمثل نسيجًا في الذاكرة يتم مشاركته بين GPU وCPU ويمكن للـ shader أن ي sampled، حيث أن [`Texture`](../../aspose.threed.shading/texture/) يمثل فقط مرجعًا إلى ملف خارجي. يمكن العثور على مزيد من التفاصيل في https://en.wikipedia.org/wiki/Texture_mapping_unit

```csharp
public interface ITextureUnit : IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Depth](../../aspose.threed.render/itextureunit/depth/) { get; } | الحصول على ارتفاع هذا النسيج، بالنسبة للنسيج غير ثلاثي الأبعاد يكون دائمًا 1. |
| [Height](../../aspose.threed.render/itextureunit/height/) { get; } | الحصول على ارتفاع هذا النسيج. |
| [Magnification](../../aspose.threed.render/itextureunit/magnification/) { get; set; } | الحصول أو تعيين وضع الفلتر للتكبير. |
| [Minification](../../aspose.threed.render/itextureunit/minification/) { get; set; } | الحصول أو تعيين وضع الفلتر للتصغير. |
| [Mipmap](../../aspose.threed.render/itextureunit/mipmap/) { get; set; } | الحصول أو تعيين وضع الفلتر للـ mipmap. |
| [Scale](../../aspose.threed.render/itextureunit/scale/) { get; set; } | الحصول أو تعيين مقياس إحداثيات UV. |
| [Scroll](../../aspose.threed.render/itextureunit/scroll/) { get; set; } | الحصول أو تعيين تمرير إحداثيات UV. |
| [Type](../../aspose.threed.render/itextureunit/type/) { get; } | الحصول على نوع وحدة النسيج هذه. |
| [UWrap](../../aspose.threed.render/itextureunit/uwrap/) { get; set; } | الحصول أو تعيين وضع الالتفاف لإحداثية U للنسيج. |
| [VWrap](../../aspose.threed.render/itextureunit/vwrap/) { get; set; } | يحصل أو يضبط وضع الالتفاف لإحداثي V للملمس. |
| [Width](../../aspose.threed.render/itextureunit/width/) { get; } | يحصل على عرض هذا الملمس. |
| [WWrap](../../aspose.threed.render/itextureunit/wwrap/) { get; set; } | يحصل أو يضبط وضع الالتفاف لإحداثي W للملمس. |

### انظر أيضًا

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


