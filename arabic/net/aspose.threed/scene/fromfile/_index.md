---
title: "Scene.FromFile"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة Scene. تفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد"
type: docs
weight: 20
url: /ar/net/aspose.threed/scene/fromfile/
---
## FromFile(string, FileFormat, CancellationToken) {#fromfile_1}

يفتح المشهد من المسار المعطى باستخدام تنسيق الملف المحدد.

```csharp
public static Scene FromFile(string fileName, FileFormat format, 
    CancellationToken cancellationToken = default)
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

يفتح المشهد من المسار المعطى باستخدام تنسيق الملف المحدد.

```csharp
public static Scene FromFile(string fileName, LoadOptions options, 
    CancellationToken cancellationToken = default)
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

يفتح المشهد من المسار المعطى

```csharp
public static Scene FromFile(string fileName)
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

يفتح المشهد من المسار المعطى

```csharp
public static Scene FromFile(string fileName, CancellationToken cancellationToken)
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

الكود التالي يوضح كيفية إنشاء مشهد من ملف

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", cts.Token);
```

### انظر أيضًا

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


