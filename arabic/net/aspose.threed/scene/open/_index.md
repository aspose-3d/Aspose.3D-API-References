---
title: "Scene.Open"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة Scene. يفتح المشهد من الدفق المعطى باستخدام تنسيق الملف المحدد"
type: docs
weight: 140
url: /ar/net/aspose.threed/scene/open/
---
## Open(Stream, FileFormat, CancellationToken) {#open_1}

يفتح المشهد من الدفق المعطى باستخدام تنسيق الملف المحدد.

```csharp
public void Open(Stream stream, FileFormat format, CancellationToken cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| تنسيق | FileFormat | تنسيق الملف. |
| cancellationToken | CancellationToken | رمز الإلغاء لمهمة التحميل |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ImportException](../../importexception/) | يُرمى عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من تدفق

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, FileFormat.GLTF2);
}
```

### انظر أيضًا

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, LoadOptions, CancellationToken) {#open_2}

يفتح المشهد من التدفق المعطى باستخدام تكوين الإدخال/الإخراج المحدد.

```csharp
public void Open(Stream stream, LoadOptions options, CancellationToken cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| الخيارات | LoadOptions | تكوين أكثر تفصيلاً لفتح التدفق. |
| cancellationToken | CancellationToken | رمز الإلغاء لمهمة التحميل |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ImportException](../../importexception/) | يُرمى عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من تدفق مع خيارات تحميل إضافية

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    var opt = new FbxLoadOptions();
    opt.LookupPaths.Add("textures");
    scene.Open(stream, opt);
}
```

### انظر أيضًا

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream) {#open}

يفتح المشهد من التدفق المعطى

```csharp
public void Open(Stream stream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ImportException](../../importexception/) | يُرمى عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من تدفق

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream);
}
```

### انظر أيضًا

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, CancellationToken) {#open_3}

يفتح المشهد من التدفق المعطى

```csharp
public void Open(Stream stream, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| cancellationToken | CancellationToken | رمز الإلغاء لمهمة التحميل |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ImportException](../../importexception/) | يُرمى عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من تدفق مع رمز إلغاء

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, cts.Token);
}
```

### انظر أيضًا

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, FileFormat, CancellationToken) {#open_5}

يفتح المشهد من المسار المعطى باستخدام تنسيق الملف المحدد.

```csharp
public void Open(string fileName, FileFormat format, CancellationToken cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |
| تنسيق | FileFormat | تنسيق الملف. |
| cancellationToken | CancellationToken | رمز الإلغاء لمهمة التحميل |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ImportException](../../importexception/) | يُرمى عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من اسم ملف مع رمز إلغاء

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
scene.Open("input.fbx", FileFormat.FBX7400ASCII, cts.Token);

```

### انظر أيضًا

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions) {#open_6}

يفتح المشهد من المسار المعطى باستخدام تنسيق الملف المحدد.

```csharp
public void Open(string fileName, LoadOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |
| الخيارات | LoadOptions | تكوين أكثر تفصيلاً لفتح التدفق. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ImportException](../../importexception/) | يُرمى عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من اسم ملف مع خيارات تحميل إضافية

```csharp
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts);
```

### انظر أيضًا

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions, CancellationToken) {#open_7}

يفتح المشهد من المسار المعطى باستخدام تنسيق الملف المحدد.

```csharp
public void Open(string fileName, LoadOptions options, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |
| الخيارات | LoadOptions | تكوين أكثر تفصيلاً لفتح التدفق. |
| cancellationToken | CancellationToken | رمز الإلغاء لمهمة التحميل |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ImportException](../../importexception/) | يُرمى عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من اسم ملف مع خيارات تحميل إضافية ورمز إلغاء

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts, cts.Token);
```

### انظر أيضًا

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string) {#open_4}

يفتح المشهد من المسار المعطى

```csharp
public void Open(string fileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ImportException](../../importexception/) | يُرمى عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من اسم ملف

```csharp
Scene scene = new Scene();
scene.Open("input.fbx");
```

### انظر أيضًا

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, CancellationToken) {#open_8}

يفتح المشهد من المسار المعطى

```csharp
public void Open(string fileName, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |
| cancellationToken | CancellationToken | رمز الإلغاء لمهمة التحميل |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في قراءة الإدخال |
| [ImportException](../../importexception/) | يُرمى عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من اسم ملف ومصدر رمز إلغاء

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
scene.Open("input.fbx", cts.Token);
```

### انظر أيضًا

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


