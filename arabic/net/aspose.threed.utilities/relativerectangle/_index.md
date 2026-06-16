---
title: "هيكل RelativeRectangle"
second_title: "مرجع Aspose.3D for .NET API"
description: "هيكل Aspose.ThreeD.Utilities.RelativeRectangle. المستطيل النسبي الصيغة بين المكوّن النسبي والقيمة المطلقة هي Scale  Reference Width  offset لذا إذا أردنا تمثيله كقيمة مطلقة نترك جميع حقول المقياس صفرًا ونستخدم حقول الإزاحة بدلاً من ذلك"
type: docs
weight: 2830
url: /ar/net/aspose.threed.utilities/relativerectangle/
---
## RelativeRectangle structure

مستطيل نسبي الصيغة بين المكوّن النسبي والقيمة المطلقة هي: المقياس * (العرض المرجعي) + الإزاحة. لذا إذا أردنا تمثيل قيمة مطلقة، اجعل جميع حقول المقياس صفرًا، واستخدم حقول الإزاحة بدلاً من ذلك.

```csharp
public struct RelativeRectangle
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [RelativeRectangle](relativerectangle/)(int, int, int, int) | إنشاء `RelativeRectangle` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [OffsetHeight](../../aspose.threed.utilities/relativerectangle/offsetheight/) { get; set; } | يحصل أو يضبط الإزاحة للارتفاع |
| [OffsetWidth](../../aspose.threed.utilities/relativerectangle/offsetwidth/) { get; set; } | يحصل أو يضبط الإزاحة للعرض |
| [OffsetX](../../aspose.threed.utilities/relativerectangle/offsetx/) { get; set; } | يحصل أو يضبط الإزاحة للإحداثي X |
| [OffsetY](../../aspose.threed.utilities/relativerectangle/offsety/) { get; set; } | يحصل أو يضبط الإزاحة للإحداثي Y |
| [ScaleHeight](../../aspose.threed.utilities/relativerectangle/scaleheight/) { get; set; } | الارتفاع النسبي |
| [ScaleWidth](../../aspose.threed.utilities/relativerectangle/scalewidth/) { get; set; } | العرض النسبي |
| [ScaleX](../../aspose.threed.utilities/relativerectangle/scalex/) { get; set; } | الإحداثي X النسبي |
| [ScaleY](../../aspose.threed.utilities/relativerectangle/scaley/) { get; set; } | الإحداثي Y النسبي |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromScale](../../aspose.threed.utilities/relativerectangle/fromscale/)(float, float, float, float) | إنشاء `RelativeRectangle` مع جميع حقول الإزاحة صفرًا وحقول المقياس من المعلمات المعطاة. |
| [ToAbsolute](../../aspose.threed.utilities/relativerectangle/toabsolute/)(int, int, int, int) | تحويل المستطيل النسبي إلى مستطيل مطلق |
| override [ToString](../../aspose.threed.utilities/relativerectangle/tostring/)() | يحوّل قيمة هذا الكائن إلى سلسلة. |

### انظر أيضًا

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


