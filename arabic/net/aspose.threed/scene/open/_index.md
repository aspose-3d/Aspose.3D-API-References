---
title: "Scene.Open"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Scene. تفتح المشهد من الدفق المعطى باستخدام تنسيق الملف المحدد"
type: docs
weight: 140
url: /ar/net/aspose.threed/scene/open/
---
## Open(Stream, FileFormat, CancellationToken) {#open_1}

يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد.

```csharp
public void Open(Stream stream, FileFormat format, CancellationToken cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| تنسيق | FileFormat | تنسيق الملف. |
| cancellationToken | CancellationToken | رمز إلغاء لمهمة التحميل |

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يتم إلقاؤه عندما يفشل قراءة الإدخال |
| [ImportException](../../importexception/) | يتم إلقاؤه عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من الدفق

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

يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد.

```csharp
public void Open(Stream stream, LoadOptions options, CancellationToken cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| خيارات | LoadOptions | إعدادات أكثر تفصيلاً لفتح الدفق. |
| cancellationToken | CancellationToken | رمز إلغاء لمهمة التحميل |

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يتم إلقاؤه عندما يفشل قراءة الإدخال |
| [ImportException](../../importexception/) | يتم إلقاؤه عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من الدفق مع خيارات تحميل إضافية

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

يفتح المشهد من الدفق المحدد

```csharp
public void Open(Stream stream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يتم إلقاؤه عندما يفشل قراءة الإدخال |
| [ImportException](../../importexception/) | يتم إلقاؤه عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من الدفق

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

يفتح المشهد من الدفق المحدد

```csharp
public void Open(Stream stream, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| cancellationToken | CancellationToken | رمز إلغاء لمهمة التحميل |

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يتم إلقاؤه عندما يفشل قراءة الإدخال |
| [ImportException](../../importexception/) | يتم إلقاؤه عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من الدفق مع رمز إلغاء

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

يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد.

```csharp
public void Open(string fileName, FileFormat format, CancellationToken cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | سلسلة | اسم الملف. |
| تنسيق | FileFormat | تنسيق الملف. |
| cancellationToken | CancellationToken | رمز إلغاء لمهمة التحميل |

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يتم إلقاؤه عندما يفشل قراءة الإدخال |
| [ImportException](../../importexception/) | يتم إلقاؤه عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من اسم الملف باستخدام رمز إلغاء.

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

يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد.

```csharp
public void Open(string fileName, LoadOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | سلسلة | اسم الملف. |
| خيارات | LoadOptions | إعدادات أكثر تفصيلاً لفتح الدفق. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يتم إلقاؤه عندما يفشل قراءة الإدخال |
| [ImportException](../../importexception/) | يتم إلقاؤه عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من اسم الملف مع خيارات تحميل إضافية.

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

يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد.

```csharp
public void Open(string fileName, LoadOptions options, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | سلسلة | اسم الملف. |
| خيارات | LoadOptions | إعدادات أكثر تفصيلاً لفتح الدفق. |
| cancellationToken | CancellationToken | رمز إلغاء لمهمة التحميل |

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يتم إلقاؤه عندما يفشل قراءة الإدخال |
| [ImportException](../../importexception/) | يتم إلقاؤه عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من اسم الملف مع خيارات تحميل إضافية ورمز إلغاء.

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

يفتح المشهد من المسار المحدد

```csharp
public void Open(string fileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | سلسلة | اسم الملف. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يتم إلقاؤه عندما يفشل قراءة الإدخال |
| [ImportException](../../importexception/) | يتم إلقاؤه عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من اسم الملف.

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

يفتح المشهد من المسار المحدد

```csharp
public void Open(string fileName, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | سلسلة | اسم الملف. |
| cancellationToken | CancellationToken | رمز إلغاء لمهمة التحميل |

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يتم إلقاؤه عندما يفشل قراءة الإدخال |
| [ImportException](../../importexception/) | يتم إلقاؤه عندما لا يكون الإدخال بتنسيق ثلاثي الأبعاد صالح |

## أمثلة

الكود التالي يوضح كيفية فتح مشهد من اسم الملف ومصدر رمز إلغاء.

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
scene.Open("input.fbx", cts.Token);
```

### انظر أيضًا

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


