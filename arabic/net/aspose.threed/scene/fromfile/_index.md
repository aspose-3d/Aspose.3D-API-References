---
title: "Scene.FromFile"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Scene. تفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد"
type: docs
weight: 20
url: /ar/net/aspose.threed/scene/fromfile/
---
## FromFile(string, FileFormat, CancellationToken) {#fromfile_1}

يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد.

```csharp
public static Scene FromFile(string fileName, FileFormat format, 
    CancellationToken cancellationToken = default)
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

الكود التالي يوضح كيفية إنشاء مشهد من ملف

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", FileFormat.FBX7400ASCII, cts.Token);
```

### انظر أيضًا

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, LoadOptions, CancellationToken) {#fromfile_2}

يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد.

```csharp
public static Scene FromFile(string fileName, LoadOptions options, 
    CancellationToken cancellationToken = default)
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

الكود التالي يوضح كيفية إنشاء مشهد من ملف

```csharp
var cts = new CancellationTokenSource();
var opt = new FbxLoadOptions();
opt.LookupPaths.Add("textures");
Scene scene = Scene.FromFile("input.fbx", opt, cts.Token);
```

### انظر أيضًا

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string) {#fromfile}

يفتح المشهد من المسار المحدد

```csharp
public static Scene FromFile(string fileName)
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

الكود التالي يوضح كيفية إنشاء مشهد من ملف

```csharp
Scene scene = Scene.FromFile("input.fbx");
```

### انظر أيضًا

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, CancellationToken) {#fromfile_3}

يفتح المشهد من المسار المحدد

```csharp
public static Scene FromFile(string fileName, CancellationToken cancellationToken)
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

الكود التالي يوضح كيفية إنشاء مشهد من ملف

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", cts.Token);
```

### انظر أيضًا

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


