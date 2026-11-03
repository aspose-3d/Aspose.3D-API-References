---
title: "Watermark.DecodeWatermark"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
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
| إدخال | شبكة | الشبكة لاستخراج العلامة المائية |

### قيمة الإرجاع

علامة مائية عمياء أو null إذا لم يتم فك تشفير أي علامة مائية.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| UnauthorizedAccessException | الشبكة محمية بكلمة مرور، وكلمة المرور المقدمة غير صحيحة. |

## ملاحظات

كلا من [`EncodeWatermark`](../encodewatermark/) و `DecodeWatermark` سيقومان بالتحقق من الترخيص. الاستخدام التجريبي سيسبب استثناءً، يمكنك استخدام [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) لكتم الاستثناء، لكنه لن يزيل القيد هنا. يلزم وجود ترخيص صالح لاستخدام هذه الميزات دون أي قيود.

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
| إدخال | شبكة | الشبكة لاستخراج العلامة المائية |
| كلمة مرور | String | كلمة المرور لفك تشفير العلامة المائية |

### قيمة الإرجاع

علامة مائية عمياء أو null إذا لم يتم فك تشفير أي علامة مائية.

### الاستثناءات

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


