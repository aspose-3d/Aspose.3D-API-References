---
title: "GltfSaveOptions"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

خيارات الحفظ لتنسيق glTF.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(contentType) | منشئ GltfSaveOptions |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(format) | منشئ GltfSaveOptions |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| forma | FileFormat | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| الاسم | الوصف |
| --- | --- |
| getPrettyPrint() | محتوى JSON لملف GLTF مُنسق للمسافات لسهولة القراءة البشرية، القيمة الافتراضية هي false |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| الاسم | الوصف |
| --- | --- |
| setPrettyPrint(value) | محتوى JSON لملف GLTF مُنسق للمسافات لسهولة القراءة البشرية، القيمة الافتراضية هي false |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| الاسم | الوصف |
| --- | --- |
| getFallbackNormal() | عند اكتشاف مُصدّر GLTF2 لِعَدَم صِحة المتجه العادي، سيتم استخدام هذا بدلاً من قيمته الأصلية لتجاوز التحقق. القيمة الافتراضية هي (0, 1, 0) |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| الاسم | الوصف |
| --- | --- |
| getEmbedAssets() | تضمين جميع الأصول الخارجية كـ base64 في ملف واحد بوضع ASCII، القيمة الافتراضية هي false. |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| الاسم | الوصف |
| --- | --- |
| setEmbedAssets(value) | تضمين جميع الأصول الخارجية كـ base64 في ملف واحد بوضع ASCII، القيمة الافتراضية هي false. |

 **Result:**



---


### getImageFormat{#getImageFormat}

| الاسم | الوصف |
| --- | --- |
| getImageFormat() | يدعم تنسيق glTF القياسي فقط PNG/JPG كتنسيق للملمس، سيوجه هذا الخيار كيفية تحويل Aspose.3D للصور غير القياسية إلى تنسيق مدعوم أثناء التصدير. القيمة الافتراضية هي GltfEmbeddedImageFormat.PNG قيمة الخاصية هي ثابت عدد صحيح من GltfEmbeddedImageFormat. |

 **Result:**



---


### setImageFormat{#setImageFormat}

| الاسم | الوصف |
| --- | --- |
| setImageFormat(value) | يدعم تنسيق glTF القياسي فقط PNG/JPG كتنسيق للملمس، سيوجه هذا الخيار كيفية تحويل Aspose.3D للصور غير القياسية إلى تنسيق مدعوم أثناء التصدير. القيمة الافتراضية هي GltfEmbeddedImageFormat.PNG قيمة الخاصية هي ثابت عدد صحيح من GltfEmbeddedImageFormat. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| الاسم | الوصف |
| --- | --- |
| getMaterialConverter() | محول مخصص لتحويل مادة الهندسة إلى مادة PBR. إذا لم يتم تعيينه، سيقوم مُصدّر glTF 2.0 تلقائيًا بتحويل المادة القياسية إلى مادة PBR. القيمة الافتراضية هي null تُستخدم هذه الخاصية عند تصدير مشهد إلى ملف glTF 2.0. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| الاسم | الوصف |
| --- | --- |
| setMaterialConverter(value) | محول مخصص لتحويل مادة الهندسة إلى مادة PBR. إذا لم يتم تعيينه، سيقوم مُصدّر glTF 2.0 تلقائيًا بتحويل المادة القياسية إلى مادة PBR. القيمة الافتراضية هي null تُستخدم هذه الخاصية عند تصدير مشهد إلى ملف glTF 2.0. |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| الاسم | الوصف |
| --- | --- |
| getUseCommonMaterials() | تسلسل المواد باستخدام امتدادات مادة KHR المشتركة، القيمة الافتراضية هي false. ضبط هذا إلى false سيتسبب في أن يقوم Aspose.3D بتصدير مجموعة من تظليل القمة/الجزء إذا #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| الاسم | الوصف |
| --- | --- |
| setUseCommonMaterials(value) | تسلسل المواد باستخدام امتدادات مادة KHR المشتركة، القيمة الافتراضية هي false. ضبط هذا إلى false سيتسبب في أن يقوم Aspose.3D بتصدير مجموعة من تظليل القمة/الجزء إذا #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| الاسم | الوصف |
| --- | --- |
| getExternalDracoEncoder() | استخدام مُشفّر دراكو الخارجي لتسريع سرعة ضغط دراكو. سيقوم Aspose.3D بإنشاء عملية فرعية جديدة لتشفير الشبكة إلى تنسيق دراكو، استخدمه على مسؤوليتك الخاصة. |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| الاسم | الوصف |
| --- | --- |
| setExternalDracoEncoder(value) | استخدام مُشفّر دراكو الخارجي لتسريع سرعة ضغط دراكو. سيقوم Aspose.3D بإنشاء عملية فرعية جديدة لتشفير الشبكة إلى تنسيق دراكو، استخدمه على مسؤوليتك الخاصة. |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| الاسم | الوصف |
| --- | --- |
| getFlipTexCoordV() | قلب مكوّن إحداثيات الملمس v(t)، القيمة الافتراضية هي true. |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| الاسم | الوصف |
| --- | --- |
| setFlipTexCoordV(value) | قلب مكوّن إحداثيات الملمس v(t)، القيمة الافتراضية هي true. |

 **Result:**



---


### getBufferFile{#getBufferFile}

| الاسم | الوصف |
| --- | --- |
| getBufferFile() | اسم الملف لملف المخزن المؤقت الخارجي المستخدم لتخزين البيانات الثنائية. إذا لم يتم تحديد هذا الملف، سيقوم Aspose.3D بإنشاء اسم لك. يتم تجاهل هذا عند تصدير glTF في الوضع الثنائي. |

 **Result:**



---


### setBufferFile{#setBufferFile}

| الاسم | الوصف |
| --- | --- |
| setBufferFile(value) | اسم الملف لملف المخزن المؤقت الخارجي المستخدم لتخزين البيانات الثنائية. إذا لم يتم تحديد هذا الملف، سيقوم Aspose.3D بإنشاء اسم لك. يتم تجاهل هذا عند تصدير glTF في الوضع الثنائي. |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| الاسم | الوصف |
| --- | --- |
| getSaveExtras() | حفظ الخصائص الديناميكية لكائن المشهد في حقول 'extra' في ملف glTF المُولد. هذا مفيد لتوفير بيانات خاصة بالتطبيق. القيمة الافتراضية هي false. |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| الاسم | الوصف |
| --- | --- |
| setSaveExtras(value) | حفظ الخصائص الديناميكية لكائن المشهد في حقول 'extra' في ملف glTF المُولد. هذا مفيد لتوفير بيانات خاصة بالتطبيق. القيمة الافتراضية هي false. |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| الاسم | الوصف |
| --- | --- |
| getApplyUnitScale() | تطبيق AssetInfo.UnitScaleFactor على الشبكة. القيمة الافتراضية هي false. |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| الاسم | الوصف |
| --- | --- |
| setApplyUnitScale(value) | تطبيق AssetInfo.UnitScaleFactor على الشبكة. القيمة الافتراضية هي false. |

 **Result:**



---


### getDracoCompression{#getDracoCompression}

| الاسم | الوصف |
| --- | --- |
| getDracoCompression() | يحصل أو يضبط ما إذا كان يجب تمكين ضغط دراكو |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| الاسم | الوصف |
| --- | --- |
| setDracoCompression(value) | يحصل أو يضبط ما إذا كان يجب تمكين ضغط دراكو |

 **Result:**



---


### getExportTextures{#getExportTextures}

| الاسم | الوصف |
| --- | --- |
| getExportTextures() | حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| الاسم | الوصف |
| --- | --- |
| setExportTextures(value) | حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| الاسم | الوصف |
| --- | --- |
| getFileFormat() | يسترجع تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |

 **Result:**



---


### getEncoding{#getEncoding}

| الاسم | الوصف |
| --- | --- |
| getEncoding() | يسترجع أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يُستخدم. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| الاسم | الوصف |
| --- | --- |
| getFileSystem() | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| الاسم | الوصف |
| --- | --- |
| setFileSystem(value) | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| الاسم | الوصف |
| --- | --- |
| getLookupPaths() | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، مسارات البحث تسمح لـ Aspose.3D بالبحث عن الملف الخارجي لتحميله. |

 **Result:**



---


### getFileName{#getFileName}

| الاسم | الوصف |
| --- | --- |
| getFileName() | اسم ملف المشهد المستورد/المصدر. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| الاسم | الوصف |
| --- | --- |
| setFileName(value) | اسم ملف المشهد المستورد/المصدر. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |

 **Result:**



---



