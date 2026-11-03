---
title: "Scene.Save"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة Scene. تحفظ المشهد إلى تدفق باستخدام تنسيق الملف المحدد"
type: docs
weight: 160
url: /ar/net/aspose.threed/scene/save/
---
## Save(Stream, FileFormat) {#save}

يحفظ المشهد إلى تدفق باستخدام تنسيق الملف المحدد.

```csharp
public void Save(Stream stream, FileFormat format)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| تنسيق | FileFormat | التنسيق. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ExportException](../../exportexception/) | يُرمى عندما يفشل تصدير المشهد إلى التنسيق الثلاثي الأبعاد المحدد |

## أمثلة

الكود التالي يوضح كيفية حفظ المشهد

```csharp
Scene scene = Scene.FromFile("input.fbx");
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ);
}
```

### انظر أيضًا

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, FileFormat, CancellationToken) {#save_1}

يحفظ المشهد إلى تدفق باستخدام تنسيق الملف المحدد.

```csharp
public void Save(Stream stream, FileFormat format, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| تنسيق | FileFormat | التنسيق. |
| cancellationToken | CancellationToken | رمز الإلغاء لمهمة الحفظ |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ExportException](../../exportexception/) | يُرمى عندما يفشل تصدير المشهد إلى التنسيق الثلاثي الأبعاد المحدد |

## أمثلة

الكود التالي يوضح كيفية حفظ المشهد

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ, cts.Token);
}
```

### انظر أيضًا

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions) {#save_2}

يحفظ المشهد إلى تدفق باستخدام تنسيق الملف المحدد.

```csharp
public void Save(Stream stream, SaveOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| الخيارات | SaveOptions | تكوين أكثر تفصيلاً لحفظ التدفق. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ExportException](../../exportexception/) | يُرمى عندما يفشل تصدير المشهد إلى التنسيق الثلاثي الأبعاد المحدد |

## أمثلة

الكود التالي يوضح كيفية حفظ المشهد

```csharp
Scene scene = Scene.FromFile("input.fbx");
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### انظر أيضًا

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions, CancellationToken) {#save_3}

يحفظ المشهد إلى تدفق باستخدام تنسيق الملف المحدد.

```csharp
public void Save(Stream stream, SaveOptions options, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| الخيارات | SaveOptions | تكوين أكثر تفصيلاً لحفظ التدفق. |
| cancellationToken | CancellationToken | رمز الإلغاء لمهمة الحفظ |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ExportException](../../exportexception/) | يُرمى عندما يفشل تصدير المشهد إلى التنسيق الثلاثي الأبعاد المحدد |

## أمثلة

الكود التالي يوضح كيفية حفظ المشهد

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt, cts.Token);
}
```

### انظر أيضًا

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string) {#save_4}

يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد.

```csharp
public void Save(string fileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ExportException](../../exportexception/) | يُرمى عندما يفشل تصدير المشهد إلى التنسيق الثلاثي الأبعاد المحدد |

## أمثلة

الكود التالي يوضح كيفية حفظ المشهد

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz");
```

### انظر أيضًا

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat) {#save_5}

يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد.

```csharp
public void Save(string fileName, FileFormat format)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |
| تنسيق | FileFormat | التنسيق. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ExportException](../../exportexception/) | يُرمى عندما يفشل تصدير المشهد إلى التنسيق الثلاثي الأبعاد المحدد |

## أمثلة

الكود التالي يوضح كيفية حفظ المشهد

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ);
```

### انظر أيضًا

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat, CancellationToken) {#save_6}

يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد.

```csharp
public void Save(string fileName, FileFormat format, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |
| تنسيق | FileFormat | التنسيق. |
| cancellationToken | CancellationToken | رمز الإلغاء لمهمة الحفظ |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ExportException](../../exportexception/) | يُرمى عندما يفشل تصدير المشهد إلى التنسيق الثلاثي الأبعاد المحدد |

## أمثلة

الكود التالي يوضح كيفية حفظ المشهد

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ, cts.Token);
```

### انظر أيضًا

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions) {#save_7}

يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد.

```csharp
public void Save(string fileName, SaveOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |
| الخيارات | SaveOptions | تكوين أكثر تفصيلاً لحفظ التدفق. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ExportException](../../exportexception/) | يُرمى عندما يفشل تصدير المشهد إلى التنسيق الثلاثي الأبعاد المحدد |

## أمثلة

الكود التالي يوضح كيفية حفظ المشهد

```csharp
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts);
```

### انظر أيضًا

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions, CancellationToken) {#save_8}

يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد.

```csharp
public void Save(string fileName, SaveOptions options, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |
| الخيارات | SaveOptions | تكوين أكثر تفصيلاً لحفظ التدفق. |
| cancellationToken | CancellationToken | رمز الإلغاء لمهمة الحفظ |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ExportException](../../exportexception/) | يُرمى عندما يفشل تصدير المشهد إلى التنسيق الثلاثي الأبعاد المحدد |

## أمثلة

الكود التالي يوضح كيفية حفظ المشهد

```csharp
var cts = new CancellationTokenSource();
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts, cts.Token);
```

### انظر أيضًا

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


