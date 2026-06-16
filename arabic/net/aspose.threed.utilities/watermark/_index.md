---
title: "الفئة Watermark"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Utilities.Watermark. أداة لتشفير/فك تشفير العلامة المائية العمياء إلى/من شبكة"
type: docs
weight: 2950
url: /ar/net/aspose.threed.utilities/watermark/
---
## Watermark class

أداة لتشفير/فك تشفير العلامة المائية العمياء إلى/من شبكة.

```csharp
public class Watermark
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark)(Mesh) | فك تشفير العلامة المائية من شبكة |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark_1)(Mesh, string) | فك تشفير العلامة المائية من شبكة |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark)(Mesh, string) | تشفير نص في العلامة المائية العمياء للشبكة. |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_1)(Mesh, string, string) | تشفير نص في العلامة المائية العمياء للشبكة. |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_2)(Mesh, string, string, bool) | تشفير نص في العلامة المائية العمياء للشبكة. |

## ملاحظات

كلا من [`EncodeWatermark`](./encodewatermark/) و[`DecodeWatermark`](./decodewatermark/) سيقومان بالتحقق من الترخيص. استخدام النسخة التجريبية سيؤدي إلى استثناء، يمكنك استخدام [`SuppressTrialException`](../../aspose.threed/trialexception/suppresstrialexception/) لكتم الاستثناء، لكن ذلك لن يزيل القيد هنا. يلزم وجود ترخيص صالح لاستخدام هذه الميزات دون أي قيود.

## أمثلة

الكود التالي يوضح كيفية تشفير علامة مائية عمياء في شبكة وفك تشفيرها.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", null);
var watermark = Watermark.DecodeWatermark(encodedMesh, null);
```

### انظر أيضًا

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


