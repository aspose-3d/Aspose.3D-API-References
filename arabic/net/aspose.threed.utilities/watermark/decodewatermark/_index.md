---
title: "Watermark.DecodeWatermark"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Watermark. فك تشفير العلامة المائية من شبكة"
type: docs
weight: 10
url: /ar/net/aspose.threed.utilities/watermark/decodewatermark/
---
## DecodeWatermark(Mesh) {#decodewatermark}

فك تشفير العلامة المائية من شبكة

```csharp
public static string DecodeWatermark(Mesh input)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | Mesh | الشبكة لاستخراج العلامة المائية |

### قيمة الإرجاع

علامة مائية عمياء أو null إذا لم يتم فك تشفير أي علامة مائية.

### استثناءات

| استثناء | شرط |
| --- | --- |
| UnauthorizedAccessException | الشبكة محمية بكلمة مرور، وكلمة المرور المقدمة غير صحيحة. |

## ملاحظات

كلا من [`EncodeWatermark`](../encodewatermark/) و `DecodeWatermark` سيقومان بالتحقق من الترخيص. الاستخدام التجريبي سيؤدي إلى رمي استثناء، يمكنك استخدام [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) لكتم الاستثناء، ولكن ذلك لن يرفع القيد هنا. يلزم وجود ترخيص صالح لاستخدام هذه الميزات دون أي قيود.

## أمثلة

الكود التالي يوضح كيفية فك تشفير علامة مائية عمياء من شبكة محفوظة في ملف ثلاثي الأبعاد

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh);
```

### انظر أيضًا

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## DecodeWatermark(Mesh, string) {#decodewatermark_1}

فك تشفير العلامة المائية من شبكة

```csharp
public static string DecodeWatermark(Mesh input, string password)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | Mesh | الشبكة لاستخراج العلامة المائية |
| password | سلسلة | كلمة المرور لفك تشفير العلامة المائية |

### قيمة الإرجاع

علامة مائية عمياء أو null إذا لم يتم فك تشفير أي علامة مائية.

### استثناءات

| استثناء | شرط |
| --- | --- |
| UnauthorizedAccessException | الشبكة محمية بكلمة مرور، وكلمة المرور المقدمة غير صحيحة. |

## أمثلة

الكود التالي يوضح كيفية فك تشفير علامة مائية عمياء من شبكة محفوظة في ملف ثلاثي الأبعاد

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh, "password");
```

### انظر أيضًا

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


