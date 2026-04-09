---
title: Class FileFormat
second_title: مرجع API Aspose.3D لـ .NET
description: Aspose.ThreeD.FileFormat class. File format definition
type: docs
weight: 1060
url: /ar/net/aspose.threed/fileformat/
---
## FileFormat class

تعريف تنسيق الملف

```csharp
public class FileFormat
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | يعرف ما إذا كان Aspose.3D يدعم تصدير المشهد إلى تنسيق الملف الحالي. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | يعرف ما إذا كان Aspose.3D يدعم استيراد المشهد من تنسيق الملف الحالي. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | يحصل على نوع محتوى تنسيق الملف |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | يحصل على اسم الامتداد لهذا النوع. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | يحصل على أسماء الامتدادات لهذا النوع. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | يحصل على نوع تنسيق الملف |
| [Version](../../aspose.threed/fileformat/version/) { get; } | يحصل على إصدار تنسيق الملف |
| static [Formats](../../aspose.threed/fileformat/formats/) { get; } | الوصول إلى جميع التنسيقات المدعومة |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Detect](../../aspose.threed/fileformat/detect/#detect_1)(string) | اكتشاف تنسيق الملف من اسم الملف، يجب أن يكون الملف قابلاً للقراءة حتى يتمكن Aspose.3D من اكتشاف تنسيق الملف عبر رأس الملف. |
| static [Detect](../../aspose.threed/fileformat/detect/#detect)(Stream, string) | اكتشاف تنسيق الملف من تدفق البيانات، اسم الملف اختياري لتخمين الأنواع التي لا تحتوي على رأس سحري. |
| static [GetFormatByExtension](../../aspose.threed/fileformat/getformatbyextension/)(string) | يحصل على تنسيق الملف المفضل من اسم امتداد الملف. يجب أن يبدأ اسم الامتداد بنقطة ('.'). |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | إنشاء خيارات تحميل افتراضية لهذا التنسيق |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | إنشاء خيارات حفظ افتراضية لهذا التنسيق |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | تحويل التنسيقات إلى سلسلة |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [AMF](../../aspose.threed/fileformat/amf/) | تنسيق ملف التصنيع الإضافي |
| static readonly [ASE](../../aspose.threed/fileformat/ase/) | تنسيق مُصدِّر المشهد ASCII لبرنامج 3D Studio Max. |
| static readonly [Aspose3DWeb](../../aspose.threed/fileformat/aspose3dweb/) | Aspose.3D Web format. |
| static readonly [Blender](../../aspose.threed/fileformat/blender/) | Blender's 3D file format |
| static readonly [Collada](../../aspose.threed/fileformat/collada/) | تنسيق ملف Collada |
| static readonly [Discreet3DS](../../aspose.threed/fileformat/discreet3ds/) | تنسيق ملف 3D Studio |
| static readonly [DXF](../../aspose.threed/fileformat/dxf/) | AutoCAD DXF |
| static readonly [FBX6100ASCII](../../aspose.threed/fileformat/fbx6100ascii/) | تنسيق ملف ASCII FBX، بالإصدار 6.1.0 |
| static readonly [FBX6100Binary](../../aspose.threed/fileformat/fbx6100binary/) | تنسيق ملف Binary FBX، بالإصدار 6.1.0 |
| static readonly [FBX7200ASCII](../../aspose.threed/fileformat/fbx7200ascii/) | تنسيق ملف ASCII FBX، بالإصدار 7.2.0 |
| static readonly [FBX7200Binary](../../aspose.threed/fileformat/fbx7200binary/) | تنسيق ملف Binary FBX، بالإصدار 7.2.0 |
| static readonly [FBX7300ASCII](../../aspose.threed/fileformat/fbx7300ascii/) | تنسيق ملف ASCII FBX، بالإصدار 7.3.0 |
| static readonly [FBX7300Binary](../../aspose.threed/fileformat/fbx7300binary/) | تنسيق ملف Binary FBX، بالإصدار 7.3.0 |
| static readonly [FBX7400ASCII](../../aspose.threed/fileformat/fbx7400ascii/) | تنسيق ملف ASCII FBX، بالإصدار 7.4.0 |
| static readonly [FBX7400Binary](../../aspose.threed/fileformat/fbx7400binary/) | تنسيق ملف Binary FBX، بالإصدار 7.4.0 |
| static readonly [FBX7500ASCII](../../aspose.threed/fileformat/fbx7500ascii/) | تنسيق ملف FBX ASCII، بالإصدار 7.5.0 |
| static readonly [FBX7500Binary](../../aspose.threed/fileformat/fbx7500binary/) | تنسيق ملف FBX الثنائي، بالإصدار 7.5.0 |
| static readonly [FBX7600ASCII](../../aspose.threed/fileformat/fbx7600ascii/) | تنسيق ملف FBX ASCII، بالإصدار 7.6.0 |
| static readonly [FBX7600Binary](../../aspose.threed/fileformat/fbx7600binary/) | تنسيق ملف FBX الثنائي، بالإصدار 7.6.0 |
| static readonly [FBX7700ASCII](../../aspose.threed/fileformat/fbx7700ascii/) | تنسيق ملف FBX ASCII، بالإصدار 7.7.0 |
| static readonly [FBX7700Binary](../../aspose.threed/fileformat/fbx7700binary/) | تنسيق ملف FBX الثنائي، بالإصدار 7.7.0 |
| static readonly [GLTF](../../aspose.threed/fileformat/gltf/) | glTF لمجموعة Khronos |
| static readonly [GLTF2](../../aspose.threed/fileformat/gltf2/) | glTF لمجموعة Khronos الإصدار 2.0 |
| static readonly [GLTF2_Binary](../../aspose.threed/fileformat/gltf2_binary/) | glTF لمجموعة Khronos الإصدار 2.0 |
| static readonly [GLTF_Binary](../../aspose.threed/fileformat/gltf_binary/) | glTF لمجموعة Khronos بصيغة ثنائية |
| static readonly [HTML5](../../aspose.threed/fileformat/html5/) | ملف HTML5 |
| static readonly [IFC](../../aspose.threed/fileformat/ifc/) | نموذج بيانات ISO 16739-1 لفئات الأساس الصناعي. |
| static readonly [MayaASCII](../../aspose.threed/fileformat/mayaascii/) | Autodesk Maya بصيغة ASCII |
| static readonly [MayaBinary](../../aspose.threed/fileformat/mayabinary/) | Autodesk Maya بصيغة ثنائية |
| static readonly [Pcd](../../aspose.threed/fileformat/pcd/) | ملف بيانات سحابة النقاط PCL بنمط ASCII |
| static readonly [PcdBinary](../../aspose.threed/fileformat/pcdbinary/) | ملف بيانات سحابة النقاط PCL بنمط ثنائي |
| static readonly [SiemensJT8](../../aspose.threed/fileformat/siemensjt8/) | ملف Siemens JT الإصدار 8 |
| static readonly [SiemensJT9](../../aspose.threed/fileformat/siemensjt9/) | ملف Siemens JT الإصدار 9 |
| static readonly [STLASCII](../../aspose.threed/fileformat/stlascii/) | تنسيق ملف STL ASCII |
| static readonly [STLBinary](../../aspose.threed/fileformat/stlbinary/) | تنسيق ملف STL الثنائي |
| static readonly [Universal3D](../../aspose.threed/fileformat/universal3d/) | تنسيق ملف Universal3D |
| static readonly [USD](../../aspose.threed/fileformat/usd/) | وصف المشهد الشامل |
| static readonly [USDA](../../aspose.threed/fileformat/usda/) | وصف المشهد الشامل بتنسيق ASCII. |
| static readonly [USDZ](../../aspose.threed/fileformat/usdz/) | وصف المشهد الشامل المضغوط |
| static readonly [VRML](../../aspose.threed/fileformat/vrml/) | لغة نمذجة الواقع الافتراضي |
| static readonly [WavefrontOBJ](../../aspose.threed/fileformat/wavefrontobj/) | تنسيق ملف Obj الخاص بـ Wavefront |
| static readonly [XBinary](../../aspose.threed/fileformat/xbinary/) | ملف DirectX X بتنسيق ثنائي |
| static readonly [XText](../../aspose.threed/fileformat/xtext/) | ملف DirectX X بتنسيق ثنائي |
| static readonly [Xyz](../../aspose.threed/fileformat/xyz/) | ملف سحابة نقاط Xyz |
| static readonly [Zip](../../aspose.threed/fileformat/zip/) | أرشيف Zip يحتوي على تنسيقات ملفات ثلاثية الأبعاد أخرى. |
| static readonly [Draco](../../aspose.threed/fileformat/draco/) | Google Draco Mesh |
| static readonly [Microsoft3MF](../../aspose.threed/fileformat/microsoft3mf/) | تنسيق Microsoft 3D Manufacturing |
| static readonly [PDF](../../aspose.threed/fileformat/pdf/) | تنسيق المستند القابل للنقل من Adobe |
| static readonly [PLY](../../aspose.threed/fileformat/ply/) | تنسيق ملف المضلع أو تنسيق مثلثات ستانفورد |
| static readonly [RvmBinary](../../aspose.threed/fileformat/rvmbinary/) | نموذج نظام إدارة تصميم المصانع AVEVA بصيغة ثنائية |
| static readonly [RvmText](../../aspose.threed/fileformat/rvmtext/) | نموذج نظام إدارة تصميم المصانع AVEVA بصيغة نصية |

### انظر أيضًا

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


