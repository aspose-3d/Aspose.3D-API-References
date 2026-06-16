---
title: "Watermark.EncodeWatermark"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Watermark. تشفير نص في علامة مائية عمياء على الشبكة"
type: docs
weight: 20
url: /ar/net/aspose.threed.utilities/watermark/encodewatermark/
---
## EncodeWatermark(Mesh, string) {#encodewatermark}

تشفير نص في العلامة المائية العمياء للشبكة.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | Mesh | شبكة لتشفير علامة مائية عمياء |
| text | سلسلة | النص لتشفيره إلى الشبكة |

### قيمة الإرجاع

مثيل شبكة جديد مع علامة مائية عمياء مشفرة

## ملاحظات

كلا من `EncodeWatermark` و[`DecodeWatermark`](../decodewatermark/) سيقومان بالتحقق من الترخيص. استخدام النسخة التجريبية سيؤدي إلى رمي استثناء، يمكنك استخدام [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) لكتم الاستثناء، لكن ذلك لن يرفع القيد هنا. يلزم وجود ترخيص صالح لاستخدام هذه الميزات دون أي قيود.

## أمثلة

الكود التالي يوضح كيفية تشفير علامة مائية عمياء في شبكة وحفظها إلى ملف ply

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello");
new Scene(encodedMesh).Save("test.ply");
```

### انظر أيضًا

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string) {#encodewatermark_1}

تشفير نص في العلامة المائية العمياء للشبكة.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | Mesh | شبكة لتشفير علامة مائية عمياء |
| text | سلسلة | النص لتشفيره إلى الشبكة |
| password | سلسلة | كلمة المرور لحماية العلامة المائية، وهي اختيارية |

### قيمة الإرجاع

مثيل شبكة جديد مع علامة مائية عمياء مشفرة

## ملاحظات

كلا من `EncodeWatermark` و[`DecodeWatermark`](../decodewatermark/) سيقومان بالتحقق من الترخيص. استخدام النسخة التجريبية سيؤدي إلى رمي استثناء، يمكنك استخدام [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) لكتم الاستثناء، لكن ذلك لن يرفع القيد هنا. يلزم وجود ترخيص صالح لاستخدام هذه الميزات دون أي قيود.

## أمثلة

الكود التالي يوضح كيفية تشفير علامة مائية عمياء في شبكة وحفظها إلى ملف ply

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### انظر أيضًا

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string, bool) {#encodewatermark_2}

تشفير نص في العلامة المائية العمياء للشبكة.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password, bool permanent)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | Mesh | شبكة لتشفير علامة مائية عمياء |
| text | سلسلة | النص لتشفيره إلى الشبكة |
| password | سلسلة | كلمة المرور لحماية العلامة المائية، وهي اختيارية |
| دائم | Boolean | العلامة المائية الدائمة لن يتم استبدالها أو إزالتها. |

### قيمة الإرجاع

مثيل شبكة جديد مع علامة مائية عمياء مشفرة

## ملاحظات

كلا من `EncodeWatermark` و[`DecodeWatermark`](../decodewatermark/) سيقومان بالتحقق من الترخيص. استخدام النسخة التجريبية سيؤدي إلى رمي استثناء، يمكنك استخدام [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) لكتم الاستثناء، لكن ذلك لن يرفع القيد هنا. يلزم وجود ترخيص صالح لاستخدام هذه الميزات دون أي قيود.

## أمثلة

الكود التالي يوضح كيفية تشفير علامة مائية عمياء في شبكة وحفظها إلى ملف ply

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### انظر أيضًا

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


