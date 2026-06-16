---
title: "FbxSaveOptions"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "خيارات الحفظ لملف Fbx."
type: docs
weight: 63
url: /ar/java/com.aspose.threed/fbxsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class FbxSaveOptions extends SaveOptions
```

خيارات الحفظ لملف Fbx.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FbxSaveOptions(FileFormat format)](#FbxSaveOptions-com.aspose.threed.FileFormat-) | يُهيئ [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) |
| [FbxSaveOptions(FileContentType contentType)](#FbxSaveOptions-com.aspose.threed.FileContentType-) | تهيئة [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) باستخدام أحدث إصدار مدعوم. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEmbedTextures()](#getEmbedTextures--) | يحصل على ما إذا كان يجب تضمين النسيج في ملف الإخراج النهائي. |
| [getEnableCompression()](#getEnableCompression--) | ضغط البيانات الثنائية الكبيرة في ملف FBX (مثال: |
| [getEncoding()](#getEncoding--) | يحصل على الترميز الافتراضي للملفات النصية. |
| [getExportLegacyMaterialProperties()](#getExportLegacyMaterialProperties--) | يحصل على ما إذا كان يتم تصدير خصائص المواد القديمة، المستخدمة للتوافق العكسي. |
| [getExportTextures()](#getExportTextures--) | حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [getFileFormat()](#getFileFormat--) | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [getFileName()](#getFileName--) | اسم ملف المشهد المصدر/المستورد. |
| [getFileSystem()](#getFileSystem--) | السماح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ. |
| [getFileSystemFactory()](#getFileSystemFactory--) | يحصل على فئة المصنع لنظام الملفات. |
| [getFoldRepeatedCurveData()](#getFoldRepeatedCurveData--) | يحصل على ما إذا كان يتم إعادة استخدام بيانات المنحنى المتكررة بزيادة عدد المراجع للبيانات الأخيرة |
| [getGenerateVertexElementMaterial()](#getGenerateVertexElementMaterial--) | يحصل على ما إذا كان يتم دائمًا إنشاء [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) للهياكل إذا كان العقد المرتبط يحتوي على مواد. |
| [getLookupPaths()](#getLookupPaths--) | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالعثور على الملف الخارجي للتحميل. |
| [getReusePrimitiveMesh()](#getReusePrimitiveMesh--) | إعادة استخدام الشبكة للأشكال الأولية ذات المعلمات نفسها، سيؤدي ذلك إلى تقليل حجم مخرجات FBX بشكل كبير عندما يتم بناء المشهد بمجموعة كبيرة من الأشكال الأولية (مثل المستوردة من ملفات CAD). |
| [getVideoForTexture()](#getVideoForTexture--) | يحصل على ما إذا كان يتم إنشاء مثال فيديو لـ [Texture](../../com.aspose.threed/texture) عند التصدير كـ FBX. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEmbedTextures(boolean value)](#setEmbedTextures-boolean-) | يضبط ما إذا كان يجب تضمين النسيج في ملف الإخراج النهائي. |
| [setEnableCompression(boolean value)](#setEnableCompression-boolean-) | ضغط البيانات الثنائية الكبيرة في ملف FBX (مثال: |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | يضبط الترميز الافتراضي للملفات النصية. |
| [setExportLegacyMaterialProperties(boolean value)](#setExportLegacyMaterialProperties-boolean-) | يضبط ما إذا كان يتم تصدير خصائص المواد القديمة، المستخدمة للتوافق العكسي. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [setFileName(String value)](#setFileName-java.lang.String-) | اسم ملف المشهد المصدر/المستورد. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | السماح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | يضبط فئة المصنع لنظام الملفات. |
| [setFoldRepeatedCurveData(Boolean value)](#setFoldRepeatedCurveData-java.lang.Boolean-) | يضبط ما إذا كان يتم إعادة استخدام بيانات المنحنى المتكررة بزيادة عدد المراجع للبيانات الأخيرة |
| [setGenerateVertexElementMaterial(boolean value)](#setGenerateVertexElementMaterial-boolean-) | يضبط ما إذا كان يتم دائمًا إنشاء [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) للهياكل إذا كان العقد المرتبط يحتوي على مواد. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالعثور على الملف الخارجي للتحميل. |
| [setReusePrimitiveMesh(boolean value)](#setReusePrimitiveMesh-boolean-) | إعادة استخدام الشبكة للأشكال الأولية ذات المعلمات نفسها، سيؤدي ذلك إلى تقليل حجم مخرجات FBX بشكل كبير عندما يتم بناء المشهد بمجموعة كبيرة من الأشكال الأولية (مثل المستوردة من ملفات CAD). |
| [setVideoForTexture(boolean value)](#setVideoForTexture-boolean-) | يضبط ما إذا كان يتم إنشاء مثال فيديو لـ [Texture](../../com.aspose.threed/texture) عند التصدير كـ FBX. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FbxSaveOptions(FileFormat format) {#FbxSaveOptions-com.aspose.threed.FileFormat-}
```
public FbxSaveOptions(FileFormat format)
```


يُهيئ [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) | مثال لـ [getFileFormat](../../com.aspose.threed/fbxsaveoptions\#getFileFormat)، يجب أن يكون تنسيق FBX صالحًا. |

### FbxSaveOptions(FileContentType contentType) {#FbxSaveOptions-com.aspose.threed.FileContentType-}
```
public FbxSaveOptions(FileContentType contentType)
```


تهيئة [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) باستخدام أحدث إصدار مدعوم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | ثنائي أو ASCII |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmbedTextures() {#getEmbedTextures--}
```
public boolean getEmbedTextures()
```


يحصل على ما إذا كان يجب تضمين النسيج في ملف الإخراج النهائي. سيحاول مُصدِّر FBX العثور على البيانات الخام للنسيج من [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem)، وتضمين الملف في ملف FBX النهائي. القيمة الافتراضية هي false.

**Returns:**
منطقي - ما إذا كان يجب تضمين النسيج في ملف الإخراج النهائي. سيحاول مُصدِّر FBX العثور على البيانات الخام للنسيج من [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem)، وتضمين الملف في ملف FBX النهائي. القيمة الافتراضية هي false.
### getEnableCompression() {#getEnableCompression--}
```
public boolean getEnableCompression()
```


ضغط البيانات الثنائية الكبيرة في ملف FBX (مثل بيانات الرسوم المتحركة، نقاط التحكم، بيانات عناصر الرأس، الفهارس)، القيمة الافتراضية هي true.

**Returns:**
منطقي - ضغط البيانات الثنائية الكبيرة في ملف FBX (مثل بيانات الرسوم المتحركة، نقاط التحكم، بيانات عناصر الرأس، الفهارس)، القيمة الافتراضية هي true.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


يحصل على الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم.

**Returns:**
java.nio.charset.Charset - الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم.
### getExportLegacyMaterialProperties() {#getExportLegacyMaterialProperties--}
```
public boolean getExportLegacyMaterialProperties()
```


يحصل على ما إذا كان يتم تصدير خصائص المواد القديمة، المستخدمة للتوافق العكسي. يتم تشغيل هذا الخيار افتراضيًا.

**Returns:**
منطقي - ما إذا كان يتم تصدير خصائص المواد القديمة، المستخدمة للتوافق العكسي. يتم تشغيل هذا الخيار افتراضيًا.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج.

**Returns:**
boolean - محاولة نسخ القوام المستخدمة في المشهد إلى دليل الإخراج.
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
### getFoldRepeatedCurveData() {#getFoldRepeatedCurveData--}
```
public Boolean getFoldRepeatedCurveData()
```


يحصل على ما إذا كان يتم إعادة استخدام بيانات المنحنى المتكررة بزيادة عدد المراجع للبيانات الأخيرة

**Returns:**
java.lang.Boolean - ما إذا كان يتم إعادة استخدام بيانات المنحنى المتكررة بزيادة عدد المراجع للبيانات الأخيرة
### getGenerateVertexElementMaterial() {#getGenerateVertexElementMaterial--}
```
public boolean getGenerateVertexElementMaterial()
```


يحصل على ما إذا كان يتم دائمًا إنشاء [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) للهياكل إذا كان العقد المرتبط يحتوي على مواد. يتم إيقاف هذا الخيار افتراضيًا.

**Returns:**
منطقي - ما إذا كان يتم دائمًا إنشاء [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) للهياكل إذا كان العقد المرتبط يحتوي على مواد. يتم إيقاف هذا الخيار افتراضيًا.
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
### getReusePrimitiveMesh() {#getReusePrimitiveMesh--}
```
public boolean getReusePrimitiveMesh()
```


إعادة استخدام الشبكة للأشكال الأولية ذات المعلمات نفسها، سيؤدي ذلك إلى تقليل حجم مخرجات FBX بشكل كبير عندما يتم بناء المشهد بمجموعة كبيرة من الأشكال الأولية (مثل المستوردة من ملفات CAD). القيمة الافتراضية هي false

**Returns:**
منطقي - إعادة استخدام الشبكة للأشكال الأولية ذات المعلمات نفسها، سيؤدي ذلك إلى تقليل حجم مخرجات FBX بشكل كبير حيث تم بناء المشهد بواسطة مجموعة كبيرة من الأشكال الأولية (مثل المستوردة من ملفات CAD). القيمة الافتراضية هي false
### getVideoForTexture() {#getVideoForTexture--}
```
public boolean getVideoForTexture()
```


يحصل على ما إذا كان يتم إنشاء مثال فيديو لـ [Texture](../../com.aspose.threed/texture) عند التصدير كـ FBX.

**Returns:**
منطقي - ما إذا كان سيتم إنشاء مثيل Video لـ [Texture](../../com.aspose.threed/texture) عند التصدير كـ FBX.
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




### setEmbedTextures(boolean value) {#setEmbedTextures-boolean-}
```
public void setEmbedTextures(boolean value)
```


يحدد ما إذا كان سيتم تضمين القوام في ملف الإخراج النهائي. سيحاول مُصدّر FBX العثور على البيانات الخام للقوام من [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem)، وتضمين الملف في ملف FBX النهائي. القيمة الافتراضية هي false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setEnableCompression(boolean value) {#setEnableCompression-boolean-}
```
public void setEnableCompression(boolean value)
```


ضغط البيانات الثنائية الكبيرة في ملف FBX (مثل بيانات الرسوم المتحركة، نقاط التحكم، بيانات عناصر الرأس، الفهارس)، القيمة الافتراضية هي true.

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

### setExportLegacyMaterialProperties(boolean value) {#setExportLegacyMaterialProperties-boolean-}
```
public void setExportLegacyMaterialProperties(boolean value)
```


يحدد ما إذا كان سيتم تصدير خصائص المواد القديمة، المستخدمة للتوافق العكسي. يتم تشغيل هذا الخيار افتراضيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

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

### setFoldRepeatedCurveData(Boolean value) {#setFoldRepeatedCurveData-java.lang.Boolean-}
```
public void setFoldRepeatedCurveData(Boolean value)
```


يضبط ما إذا كان يتم إعادة استخدام بيانات المنحنى المتكررة بزيادة عدد المراجع للبيانات الأخيرة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.Boolean | القيمة الجديدة |

### setGenerateVertexElementMaterial(boolean value) {#setGenerateVertexElementMaterial-boolean-}
```
public void setGenerateVertexElementMaterial(boolean value)
```


يحدد ما إذا كان سيتم دائمًا إنشاء [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) للهياكل إذا كان العقد المرتبط يحتوي على مواد. يتم إيقاف هذا الخيار افتراضيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

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

### setReusePrimitiveMesh(boolean value) {#setReusePrimitiveMesh-boolean-}
```
public void setReusePrimitiveMesh(boolean value)
```


إعادة استخدام الشبكة للأشكال الأولية ذات المعلمات نفسها، سيؤدي ذلك إلى تقليل حجم مخرجات FBX بشكل كبير عندما يتم بناء المشهد بمجموعة كبيرة من الأشكال الأولية (مثل المستوردة من ملفات CAD). القيمة الافتراضية هي false

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setVideoForTexture(boolean value) {#setVideoForTexture-boolean-}
```
public void setVideoForTexture(boolean value)
```


يضبط ما إذا كان يتم إنشاء مثال فيديو لـ [Texture](../../com.aspose.threed/texture) عند التصدير كـ FBX.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

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

