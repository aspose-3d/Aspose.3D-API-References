---
title: "تعداد StencilAction"
second_title: "مرجع Aspose.3D for .NET API"
description: "تعداد Aspose.ThreeD.Render.StencilAction. إجراءات اختبار الستينسل"
type: docs
weight: 2430
url: /ar/net/aspose.threed.render/stencilaction/
---
## StencilAction enumeration

إجراءات اختبار القالب

```csharp
public enum StencilAction
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Keep | `0` | احتفظ بالقيمة الحالية |
| Zero | `1` | يضبط قيمة مخزن الستينسل إلى 0 |
| Replace | `2` | يضبط مخزن الستينسل إلى المرجع حيث تم تعريفه في [`StencilReference`](../renderstate/stencilreference/) |
| Increment | `3` | يزيد قيمة مخزن الستينسل الحالية، يحدها إلى القيمة القصوى. |
| IncrementWrap | `4` | يزيد قيمة مخزن الستينسل الحالية ويعيدها إلى الصفر عندما تصل إلى القيمة القصوى. |
| Decrement | `5` | يزيد قيمة مخزن الستينسل الحالية، يحدها إلى 0. |
| DecrementWrap | `6` | يقلل قيمة مخزن الستينسل الحالية ويعيدها إلى القيمة القصوى عندما تصل إلى الصفر. |
| Invert | `7` | يعكس القيمة الحالية لمخزن الستينسل على مستوى البت. |

### انظر أيضًا

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


