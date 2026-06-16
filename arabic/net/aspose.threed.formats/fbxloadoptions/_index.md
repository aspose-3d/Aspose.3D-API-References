---
title: "الفئة FbxLoadOptions"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Formats.FbxLoadOptions class. خيارات التحميل لتنسيق Fbx"
type: docs
weight: 1170
url: /ar/net/aspose.threed.formats/fbxloadoptions/
---
## FbxLoadOptions class

خيارات التحميل لتنسيق Fbx.

```csharp
public class FbxLoadOptions : LoadOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [FbxLoadOptions](fbxloadoptions/#constructor)() | منشئ `FbxLoadOptions` |
| [FbxLoadOptions](fbxloadoptions/#constructor_1)(FileFormat) | منشئ `FbxLoadOptions` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CompatibleMode](../../aspose.threed.formats/fbxloadoptions/compatiblemode/) { get; set; } | يحصل أو يضبط ما إذا كان يجب تمكين وضع التوافق. سيحاول وضع التوافق دعم تعريفات FBX غير القياسية مثل مواد PBR التي يصدرها Blender. القيمة الافتراضية هي false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم ملف المشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |
| [KeepBuiltinGlobalSettings](../../aspose.threed.formats/fbxloadoptions/keepbuiltinglobalsettings/) { get; set; } | يحصل أو يضبط ما إذا كان يجب الاحتفاظ بالخصائص المدمجة في GlobalSettings التي لها استبدال خاصية أصلي في [`AssetInfo`](../../aspose.threed/assetinfo/). اضبط هذا على true إذا كنت تريد الخصائص الكاملة في GlobalSettings. القيمة الافتراضية هي false |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملف خارجي، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. |

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


