---
title: "FileFormat"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

تعريف تنسيق الملف  @hideconstructor


## الخصائص

| الاسم | الوصف |
| --- | --- |
| MAYA_BINARY | أوتوديسك مايا بصيغة ثنائية |
| STL_BINARY | صيغة ملف STL ثنائية |
| STLASCII | صيغة ملف STL بنص ASCII |
| COLLADA | صيغة ملف Collada |
| GLTF | glTF الخاص بمجموعة Khronos |
| GLTF_BINARY | glTF الخاص بمجموعة Khronos بصيغة ثنائية |
| PDF | صيغة المستند القابل للنقل من Adobe |
| DXF | AutoCAD DXF |
| PLY | صيغة ملف المضلع أو صيغة مثلث ستانفورد |
| X_BINARY | ملف DirectX X بصيغة ثنائية |
| X_TEXT | ملف DirectX X بصيغة ثنائية |
| DRACO | شبكة Draco من Google |
| RVM_TEXT | نموذج نظام إدارة تصميم محطة AVEVA بصيغة نصية |
| RVM_BINARY | نموذج نظام إدارة تصميم محطة AVEVA بصيغة ثنائية |
| ASE | تنسيق مُصدّر المشهد ASCII لبرنامج 3D Studio Max. |
| IFC | نموذج بيانات فئات الأساس الصناعي ISO 16739-1. |
| AMF | تنسيق ملف التصنيع الإضافي |
| VRML | لغة نمذجة الواقع الافتراضي |
| ZIP | أرشيف Zip يحتوي على تنسيقات ملفات 3d أخرى. |
| USD | وصف المشهد الشامل |
| USDZ | وصف المشهد الشامل المضغوط |
| XYZ | ملف سحابة نقاط Xyz |
| PCD | ملف بيانات سحابة النقاط PCL في وضع ASCII |
| PCD_BINARY | ملف بيانات سحابة النقاط PCL في وضع ثنائي |

## الطرق

### getVersion{#getVersion}

| الاسم | الوصف |
| --- | --- |
| getVersion() | يحصل على إصدار تنسيق الملف |

 **Result:**



---


### getExtension{#getExtension}

| الاسم | الوصف |
| --- | --- |
| getExtension() | يحصل على اسم الامتداد لهذا النوع. |

 **Result:**



---


### getExtensions{#getExtensions}

| الاسم | الوصف |
| --- | --- |
| getExtensions() | يحصل على أسماء الامتداد لهذا النوع. |

 **Result:**



---


### getContentType{#getContentType}

| الاسم | الوصف |
| --- | --- |
| getContentType() | يحصل على نوع محتوى تنسيق الملف. قيمة الخاصية هي ثابت عدد صحيح FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| الاسم | الوصف |
| --- | --- |
| getFileFormatType() | يحصل على نوع تنسيق الملف |

 **Result:**



---


### getFormatByExtension{#getFormatByExtension}

| الاسم | الوصف |
| --- | --- |
| getFormatByExtension(extensionName) | يحصل على تنسيق الملف المفضل من اسم امتداد الملف. يجب أن يبدأ اسم الامتداد بنقطة ('.'). |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| extensionNam | String | null |

 **Result:**
FileFormat


---


### detect{#detect}

| الاسم | الوصف |
| --- | --- |
| detect(fileName) | اكتشف تنسيق الملف من اسم الملف، يجب أن يكون الملف قابلاً للقراءة حتى يتمكن Aspose.3D من اكتشاف تنسيق الملف عبر رأس الملف. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
FileFormat


---


### createLoadOptions{#createLoadOptions}

| الاسم | الوصف |
| --- | --- |
| createLoadOptions() | إنشاء خيارات تحميل افتراضية لهذا تنسيق الملف |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| الاسم | الوصف |
| --- | --- |
| createSaveOptions() | إنشاء خيارات حفظ افتراضية لهذا تنسيق الملف |

 **Result:**
SaveOptions


---


### toString{#toString}

| الاسم | الوصف |
| --- | --- |
| toString() | تحويل التنسيقات إلى سلسلة |

 **Result:**
String


---



