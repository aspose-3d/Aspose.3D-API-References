---
title: "Scene.FromStream"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة Scene. يفتح المشهد من الدفق المعطى باستخدام تنسيق الملف المحدد"
type: docs
weight: 30
url: /ar/net/aspose.threed/scene/fromstream/
---
## FromStream(Stream, FileFormat, CancellationToken) {#fromstream}

يفتح المشهد من الدفق المعطى باستخدام تنسيق الملف المحدد.

```csharp
public static Scene FromStream(Stream stream, FileFormat format, 
    CancellationToken cancellationToken = default)
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

الكود التالي يوضح كيفية إنشاء مشهد من تدفق

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

يفتح المشهد من التدفق المعطى باستخدام تكوين الإدخال/الإخراج المحدد.

```csharp
public static Scene FromStream(Stream stream, LoadOptions options, 
    CancellationToken cancellationToken = default)
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

الكود التالي يوضح كيفية إنشاء مشهد من تدفق مع خيارات التحميل

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

يفتح المشهد من التدفق المعطى

```csharp
public static Scene FromStream(Stream stream, CancellationToken cancellationToken = default)
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

الكود التالي يوضح كيفية إنشاء مشهد من تدفق مع مصدر رمز الإلغاء

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


