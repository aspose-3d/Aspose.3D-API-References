---
title: "GltfSaveOptions"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "خيارات الحفظ لتنسيق glTF."
type: docs
weight: 74
url: /ar/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

خيارات الحفظ لتنسيق glTF.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | منشئ [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | منشئ [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | تطبيق [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) على الشبكة. |
| [getBufferFile()](#getBufferFile--) | اسم ملف المخزن الخارجي المستخدم لتخزين البيانات الثنائية. |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | يُرجع ما إذا كان تمكين ضغط دراكو |
| [getEmbedAssets()](#getEmbedAssets--) | تضمين جميع الأصول الخارجية كـ base64 في ملف واحد بوضع ASCII، القيمة الافتراضية هي false. |
| [getEncoding()](#getEncoding--) | يحصل على الترميز الافتراضي للملفات النصية. |
| [getExportTextures()](#getExportTextures--) | حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | استخدام مشفر دراكو الخارجي لتسريع سرعة ضغط دراكو. |
| [getFallbackNormal()](#getFallbackNormal--) | عند اكتشاف مُصدّر GLTF2 لِعادي غير صالح، سيتم استخدام هذا بدلاً من قيمته الأصلية لتجاوز التحقق. |
| [getFileFormat()](#getFileFormat--) | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [getFileName()](#getFileName--) | اسم ملف المشهد المصدر/المستورد. |
| [getFileSystem()](#getFileSystem--) | السماح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ. |
| [getFileSystemFactory()](#getFileSystemFactory--) | يحصل على فئة المصنع لنظام الملفات. |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | قلب مكوّن إحداثي القوام v(t)، القيمة الافتراضية هي true. |
| [getImageFormat()](#getImageFormat--) | يدعم glTF القياسي فقط PNG/JPG كتنسيق للملمس، هذا الخيار سيوجه كيفية تحويل Aspose.3D للصور غير القياسية إلى تنسيق مدعوم أثناء التصدير. |
| [getLookupPaths()](#getLookupPaths--) | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالعثور على الملف الخارجي للتحميل. |
| [getMaterialConverter()](#getMaterialConverter--) | محول مخصص لتحويل مادة الشكل الهندسي إلى مادة PBR. إذا لم يتم تعيينه، سيقوم مُصدّر glTF 2.0 تلقائيًا بتحويل المادة القياسية إلى مادة PBR. |
| [getPrettyPrint()](#getPrettyPrint--) | محتوى JSON لملف GLTF مُنسق للقراءة البشرية، القيمة الافتراضية هي false |
| [getSaveExtras()](#getSaveExtras--) | احفظ الخصائص الديناميكية لكائن المشهد في حقول 'extra' في ملف glTF المُولد. |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | سلسلة المواد باستخدام امتدادات المواد المشتركة KHR، القيمة الافتراضية هي false. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | تطبيق [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) على الشبكة. |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | اسم ملف المخزن الخارجي المستخدم لتخزين البيانات الثنائية. |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | تحدد ما إذا كان يجب تمكين ضغط draco |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | تضمين جميع الأصول الخارجية كـ base64 في ملف واحد بوضع ASCII، القيمة الافتراضية هي false. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | يضبط الترميز الافتراضي للملفات النصية. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | استخدام مشفر دراكو الخارجي لتسريع سرعة ضغط دراكو. |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | عند اكتشاف مُصدّر GLTF2 لِعادي غير صالح، سيتم استخدام هذا بدلاً من قيمته الأصلية لتجاوز التحقق. |
| [setFileName(String value)](#setFileName-java.lang.String-) | اسم ملف المشهد المصدر/المستورد. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | السماح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | يضبط فئة المصنع لنظام الملفات. |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | قلب مكوّن إحداثي القوام v(t)، القيمة الافتراضية هي true. |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | يدعم glTF القياسي فقط PNG/JPG كتنسيق للملمس، هذا الخيار سيوجه كيفية تحويل Aspose.3D للصور غير القياسية إلى تنسيق مدعوم أثناء التصدير. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالعثور على الملف الخارجي للتحميل. |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | محول مخصص لتحويل مادة الشكل الهندسي إلى مادة PBR. إذا لم يتم تعيينه، سيقوم مُصدّر glTF 2.0 تلقائيًا بتحويل المادة القياسية إلى مادة PBR. |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | محتوى JSON لملف GLTF مُنسق للقراءة البشرية، القيمة الافتراضية هي false |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | احفظ الخصائص الديناميكية لكائن المشهد في حقول 'extra' في ملف glTF المُولد. |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | سلسلة المواد باستخدام امتدادات المواد المشتركة KHR، القيمة الافتراضية هي false. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


منشئ [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


منشئ [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApplyUnitScale() {#getApplyUnitScale--}
```
public boolean getApplyUnitScale()
```


تطبيق [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) على الشبكة. القيمة الافتراضية هي false.

**Returns:**
منطقي - تطبيق [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) على الشبكة. القيمة الافتراضية هي false.
### getBufferFile() {#getBufferFile--}
```
public String getBufferFile()
```


اسم الملف لملف المخزن الخارجي المستخدم لتخزين البيانات الثنائية. إذا لم يتم تحديد هذا الملف، سيقوم Aspose.3D بإنشاء اسم لك. يتم تجاهل هذا عند تصدير glTF في الوضع الثنائي.

**Returns:**
java.lang.String - اسم الملف لملف المخزن الخارجي المستخدم لتخزين البيانات الثنائية. إذا لم يتم تحديد هذا الملف، سيقوم Aspose.3D بإنشاء اسم لك. يتم تجاهل هذا عند تصدير glTF في الوضع الثنائي.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDracoCompression() {#getDracoCompression--}
```
public boolean getDracoCompression()
```


يُرجع ما إذا كان تمكين ضغط دراكو

**Returns:**
boolean - ما إذا كان يجب تمكين ضغط draco
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


تضمين جميع الأصول الخارجية كـ base64 في ملف واحد بوضع ASCII، القيمة الافتراضية هي false.

**Returns:**
boolean - تضمين جميع الأصول الخارجية كـ base64 في ملف واحد في وضع ASCII، القيمة الافتراضية هي false.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


يحصل على الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم.

**Returns:**
java.nio.charset.Charset - الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج.

**Returns:**
boolean - محاولة نسخ القوام المستخدمة في المشهد إلى دليل الإخراج.
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


استخدام مشفر دراكو الخارجي لتسريع سرعة ضغط دراكو.

**Returns:**
java.lang.String - استخدم مشفر draco الخارجي لتسريع سرعة ضغط draco. **Remarks:** Aspose.3D سيُنشئ عملية فرعية جديدة لتشفير الشبكة إلى تنسيق draco، استخدمه على مسؤوليتك الخاصة.
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


عند اكتشاف مُصدّر GLTF2 لِعادي غير صالح، سيتم استخدام هذا بدلاً من قيمته الأصلية لتجاوز التحقق. القيمة الافتراضية هي (0, 1, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


اسم الملف للمشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ.

**Returns:**
java.lang.String - اسم الملف للمشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


السماح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

ويمكنك أيضًا استخدام تنفيذك الخاص.

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
```
### getFileSystemFactory() {#getFileSystemFactory--}
```
public static FileSystemFactory getFileSystemFactory()
```


يحصل على فئة المصنع لنظام الملفات. المصنع الافتراضي سيُنشئ com.aspose.threed.LocalFileSystem والذي لا يناسب بيئة الخادم.

**Returns:**
[FileSystemFactory](../../com.aspose.threed/filesystemfactory) - the factory class for FileSystem. The default factory will create com.aspose.threed.LocalFileSystem which is not suitable for server environment. **Example:** The default FileSystem in SaveOptions/LoadOptions is directory-based file system, You can override the default implementation by specify it through IOConfig.FileSystemFactory:

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
```
### getFlipTexCoordV() {#getFlipTexCoordV--}
```
public boolean getFlipTexCoordV()
```


قلب مكوّن إحداثي القوام v(t)، القيمة الافتراضية هي true.

**Returns:**
boolean - عكس مكوّن إحداثيات القوام v(t)، القيمة الافتراضية هي true.
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


يدعم glTF القياسي فقط PNG/JPG كتنسيق للملمس، هذا الخيار سيوجه كيفية تحويل Aspose.3D للصور غير القياسية إلى تنسيق مدعوم أثناء التصدير. القيمة الافتراضية هي [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالعثور على الملف الخارجي للتحميل.

**Returns:**
java.util.ArrayList<java.lang.String> - بعض الملفات مثل OBJ تعتمد على ملفات خارجية، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. **Example:** يوضح الكود التالي كيفية تحديد مسارات البحث عن القوام يدويًا، حتى يتمكن المستورد من العثور عليها

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
```
### getMaterialConverter() {#getMaterialConverter--}
```
public MaterialConverter getMaterialConverter()
```


محول مخصص لتحويل مادة الشكل الهندسي إلى مادة PBR. إذا لم يتم تعيينه، سيقوم مُصدّر glTF 2.0 تلقائيًا بتحويل المادة القياسية إلى مادة PBR. القيمة الافتراضية هي null. تُستخدم هذه الخاصية عند تصدير مشهد إلى ملف glTF 2.0.

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


محتوى JSON لملف GLTF مُنسق للقراءة البشرية، القيمة الافتراضية هي false

**Returns:**
boolean - محتوى JSON لملف GLTF مُنسق للقراءة البشرية، القيمة الافتراضية هي false
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


احفظ الخصائص الديناميكية لكائن المشهد في حقول 'extra' في ملف glTF المُولد. هذا مفيد لتوفير بيانات خاصة بالتطبيق. القيمة الافتراضية هي false.

**Returns:**
boolean - احفظ الخصائص الديناميكية لكائن المشهد في حقول 'extra' في ملف GLTF المُولد. هذا مفيد لتوفير بيانات خاصة بالتطبيق. القيمة الافتراضية هي false.
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


سلسلة المواد باستخدام امتدادات المواد المشتركة KHR، القيمة الافتراضية هي false. ضبط هذا على false سيتسبب في تصدير Aspose.3D لمجموعة من تظليل القمة/الجزء إذا كان [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Returns:**
boolean - سلسلة المواد باستخدام امتدادات المواد المشتركة KHR، القيمة الافتراضية هي false. ضبط هذا على false سيتسبب في تصدير Aspose.3D لمجموعة من تظليل القمة/الجزء إذا كان [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) **Remarks:** هذه الخاصية تعمل فقط مع glTF 1.0
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setApplyUnitScale(boolean value) {#setApplyUnitScale-boolean-}
```
public void setApplyUnitScale(boolean value)
```


تطبيق [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) على الشبكة. القيمة الافتراضية هي false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


اسم الملف لملف المخزن الخارجي المستخدم لتخزين البيانات الثنائية. إذا لم يتم تحديد هذا الملف، سيقوم Aspose.3D بإنشاء اسم لك. يتم تجاهل هذا عند تصدير glTF في الوضع الثنائي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


تحدد ما إذا كان يجب تمكين ضغط draco

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


تضمين جميع الأصول الخارجية كـ base64 في ملف واحد بوضع ASCII، القيمة الافتراضية هي false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدّر سيقرر أي ترميز يستخدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.nio.charset.Charset | القيمة الجديدة |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


استخدام مشفر دراكو الخارجي لتسريع سرعة ضغط دراكو.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | قيمة جديدة **Remarks:** سيقوم Aspose.3D بإنشاء عملية فرعية جديدة لتشفير الشبكة إلى تنسيق draco، استخدمها على مسؤوليتك الخاصة. |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


عند اكتشاف مُصدّر GLTF2 لِعادي غير صالح، سيتم استخدام هذا بدلاً من قيمته الأصلية لتجاوز التحقق. القيمة الافتراضية هي (0, 1, 0)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


اسم الملف للمشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


السماح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | New value **Example:** نظام الملفات الافتراضي هو LocalFileSystem، وهو غير آمن في بيئات مثل جانب الخادم، ولكن يمكنك تجاوز وصول نظام الملفات بتحديد تنفيذ مختلف. Aspose.3D يوفر تنفيذات مختلفة لنظام الملفات مثل: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

ويمكنك أيضًا استخدام تنفيذك الخاص.

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
``` |

### setFileSystemFactory(FileSystemFactory value) {#setFileSystemFactory-com.aspose.threed.FileSystemFactory-}
```
public static void setFileSystemFactory(FileSystemFactory value)
```


يضبط فئة المصنع لنظام الملفات. المصنع الافتراضي سيُنشئ com.aspose.threed.LocalFileSystem والذي لا يناسب بيئة الخادم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | New value **Example:** نظام الملفات الافتراضي في SaveOptions/LoadOptions هو نظام ملفات قائم على الدليل، يمكنك تجاوز التنفيذ الافتراضي بتحديده عبر IOConfig.FileSystemFactory: |

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
``` |

### setFlipTexCoordV(boolean value) {#setFlipTexCoordV-boolean-}
```
public void setFlipTexCoordV(boolean value)
```


قلب مكوّن إحداثي القوام v(t)، القيمة الافتراضية هي true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


يدعم glTF القياسي فقط PNG/JPG كتنسيق للملمس، هذا الخيار سيوجه كيفية تحويل Aspose.3D للصور غير القياسية إلى تنسيق مدعوم أثناء التصدير. القيمة الافتراضية هي [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | القيمة الجديدة |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالعثور على الملف الخارجي للتحميل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.util.ArrayList<java.lang.String> | New value **Example:** يوضح الكود التالي كيفية تحديد مسارات البحث عن القوام يدويًا، حتى يتمكن المستورد من العثور عليها |

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
``` |

### setMaterialConverter(MaterialConverter value) {#setMaterialConverter-com.aspose.threed.MaterialConverter-}
```
public void setMaterialConverter(MaterialConverter value)
```


محول مخصص لتحويل مادة الشكل الهندسي إلى مادة PBR. إذا لم يتم تعيينه، سيقوم مُصدّر glTF 2.0 تلقائيًا بتحويل المادة القياسية إلى مادة PBR. القيمة الافتراضية هي null. تُستخدم هذه الخاصية عند تصدير مشهد إلى ملف glTF 2.0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | القيمة الجديدة |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


محتوى JSON لملف GLTF مُنسق للقراءة البشرية، القيمة الافتراضية هي false

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


احفظ الخصائص الديناميكية لكائن المشهد في حقول 'extra' في ملف glTF المُولد. هذا مفيد لتوفير بيانات خاصة بالتطبيق. القيمة الافتراضية هي false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


سلسلة المواد باستخدام امتدادات المواد المشتركة KHR، القيمة الافتراضية هي false. ضبط هذا على false سيتسبب في تصدير Aspose.3D لمجموعة من تظليل القمة/الجزء إذا كان [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة جديدة **Remarks:** هذه الخاصية تعمل فقط مع glTF 1.0 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

