---
title: "Scene.FromStream"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Scene. تفتح المشهد من الدفق المعطى باستخدام تنسيق الملف المحدد"
type: docs
weight: 30
url: /ar/net/aspose.threed/scene/fromstream/
---
## FromStream(Stream, FileFormat, CancellationToken) {#fromstream}

يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد.

```csharp
public static Scene FromStream(Stream stream, FileFormat format, 
    CancellationToken cancellationToken = default)
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

الكود التالي يوضح كيفية إنشاء مشهد من تدفق.

```csharp
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream);
}
```

### انظر أيضًا

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, LoadOptions, CancellationToken) {#fromstream_1}

يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد.

```csharp
public static Scene FromStream(Stream stream, LoadOptions options, 
    CancellationToken cancellationToken = default)
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

الكود التالي يوضح كيفية إنشاء مشهد من تدفق مع خيارات التحميل.

```csharp
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, opts);
}
```

### انظر أيضًا

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, CancellationToken) {#fromstream_2}

يفتح المشهد من الدفق المحدد

```csharp
public static Scene FromStream(Stream stream, CancellationToken cancellationToken = default)
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

الكود التالي يوضح كيفية إنشاء مشهد من تدفق مع مصدر رمز إلغاء.

```csharp
var cts = new CancellationTokenSource();
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, cts.Token);
}
```

### انظر أيضًا

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


