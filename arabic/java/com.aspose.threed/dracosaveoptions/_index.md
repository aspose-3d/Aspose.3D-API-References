---
title: "DracoSaveOptions"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "خيارات الحفظ لملفات Google draco"
type: docs
weight: 47
url: /ar/java/com.aspose.threed/dracosaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class DracoSaveOptions extends SaveOptions
```

خيارات الحفظ لملفات Google draco
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [DracoSaveOptions()](#DracoSaveOptions--) | إنشاء تكوين افتراضي لحفظ ملفات draco. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | تطبيق [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) على الشبكة. |
| [getClass()](#getClass--) |  |
| [getColorBits()](#getColorBits--) | عدد بتات التكميم للون القمم، القيمة الافتراضية هي 10 |
| [getCompressionLevel()](#getCompressionLevel--) | مستوى الضغط، القيمة الافتراضية هي [DracoCompressionLevel.STANDARD](../../com.aspose.threed/dracocompressionlevel\#STANDARD) |
| [getEncoding()](#getEncoding--) | يحصل على الترميز الافتراضي للملفات النصية. |
| [getExportTextures()](#getExportTextures--) | حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [getFileFormat()](#getFileFormat--) | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [getFileName()](#getFileName--) | اسم ملف المشهد المصدر/المستورد. |
| [getFileSystem()](#getFileSystem--) | السماح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ. |
| [getFileSystemFactory()](#getFileSystemFactory--) | يحصل على فئة المصنع لنظام الملفات. |
| [getLookupPaths()](#getLookupPaths--) | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالعثور على الملف الخارجي للتحميل. |
| [getNormalBits()](#getNormalBits--) | عدد بتات التكميم للمتجهات العادية، القيمة الافتراضية هي 10 |
| [getPointCloud()](#getPointCloud--) | تصدير المشهد كسحابة نقطية، القيمة الافتراضية هي false. |
| [getPositionBits()](#getPositionBits--) | عدد بتات التكميم للموقع، القيمة الافتراضية هي 14 |
| [getTextureCoordinateBits()](#getTextureCoordinateBits--) | عدد بتات التكميم لإحداثيات القوام، القيمة الافتراضية هي 12 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | تطبيق [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) على الشبكة. |
| [setColorBits(int value)](#setColorBits-int-) | عدد بتات التكميم للون القمم، القيمة الافتراضية هي 10 |
| [setCompressionLevel(DracoCompressionLevel value)](#setCompressionLevel-com.aspose.threed.DracoCompressionLevel-) | مستوى الضغط، القيمة الافتراضية هي [DracoCompressionLevel.STANDARD](../../com.aspose.threed/dracocompressionlevel\#STANDARD) |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | يضبط الترميز الافتراضي للملفات النصية. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [setFileName(String value)](#setFileName-java.lang.String-) | اسم ملف المشهد المصدر/المستورد. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | السماح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | يضبط فئة المصنع لنظام الملفات. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالعثور على الملف الخارجي للتحميل. |
| [setNormalBits(int value)](#setNormalBits-int-) | عدد بتات التكميم للمتجهات العادية، القيمة الافتراضية هي 10 |
| [setPointCloud(boolean value)](#setPointCloud-boolean-) | تصدير المشهد كسحابة نقطية، القيمة الافتراضية هي false. |
| [setPositionBits(int value)](#setPositionBits-int-) | عدد بتات التكميم للموقع، القيمة الافتراضية هي 14 |
| [setTextureCoordinateBits(int value)](#setTextureCoordinateBits-int-) | عدد بتات التكميم لإحداثيات القوام، القيمة الافتراضية هي 12 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DracoSaveOptions() {#DracoSaveOptions--}
```
public DracoSaveOptions()
```


إنشاء تكوين افتراضي لحفظ ملفات draco.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorBits() {#getColorBits--}
```
public int getColorBits()
```


عدد بتات التكميم للون القمم، القيمة الافتراضية هي 10

**Returns:**
عدد صحيح - عدد بتات التكميم للون القمم، القيمة الافتراضية هي 10
### getCompressionLevel() {#getCompressionLevel--}
```
public DracoCompressionLevel getCompressionLevel()
```


مستوى الضغط، القيمة الافتراضية هي [DracoCompressionLevel.STANDARD](../../com.aspose.threed/dracocompressionlevel\#STANDARD)

**Returns:**
[DracoCompressionLevel](../../com.aspose.threed/dracocompressionlevel) - Compression level, default value is [DracoCompressionLevel.STANDARD](../../com.aspose.threed/dracocompressionlevel\#STANDARD)
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
### getNormalBits() {#getNormalBits--}
```
public int getNormalBits()
```


عدد بتات التكميم للمتجهات العادية، القيمة الافتراضية هي 10

**Returns:**
عدد صحيح - عدد بتات التكميم للمتجهات العادية، القيمة الافتراضية هي 10
### getPointCloud() {#getPointCloud--}
```
public boolean getPointCloud()
```


تصدير المشهد كسحابة نقطية، القيمة الافتراضية هي false.

**Returns:**
منطقي - تصدير المشهد كسحابة نقطية، القيمة الافتراضية هي false.
### getPositionBits() {#getPositionBits--}
```
public int getPositionBits()
```


عدد بتات التكميم للموقع، القيمة الافتراضية هي 14

**Returns:**
عدد صحيح - عدد بتات التكميم للموقع، القيمة الافتراضية هي 14
### getTextureCoordinateBits() {#getTextureCoordinateBits--}
```
public int getTextureCoordinateBits()
```


عدد بتات التكميم لإحداثيات القوام، القيمة الافتراضية هي 12

**Returns:**
عدد صحيح - عدد بتات التكميم لإحداثيات القوام، القيمة الافتراضية هي 12
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

### setColorBits(int value) {#setColorBits-int-}
```
public void setColorBits(int value)
```


عدد بتات التكميم للون القمم، القيمة الافتراضية هي 10

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setCompressionLevel(DracoCompressionLevel value) {#setCompressionLevel-com.aspose.threed.DracoCompressionLevel-}
```
public void setCompressionLevel(DracoCompressionLevel value)
```


مستوى الضغط، القيمة الافتراضية هي [DracoCompressionLevel.STANDARD](../../com.aspose.threed/dracocompressionlevel\#STANDARD)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DracoCompressionLevel](../../com.aspose.threed/dracocompressionlevel) | القيمة الجديدة |

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

### setNormalBits(int value) {#setNormalBits-int-}
```
public void setNormalBits(int value)
```


عدد بتات التكميم للمتجهات العادية، القيمة الافتراضية هي 10

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setPointCloud(boolean value) {#setPointCloud-boolean-}
```
public void setPointCloud(boolean value)
```


تصدير المشهد كسحابة نقطية، القيمة الافتراضية هي false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setPositionBits(int value) {#setPositionBits-int-}
```
public void setPositionBits(int value)
```


عدد بتات التكميم للموقع، القيمة الافتراضية هي 14

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setTextureCoordinateBits(int value) {#setTextureCoordinateBits-int-}
```
public void setTextureCoordinateBits(int value)
```


عدد بتات التكميم لإحداثيات القوام، القيمة الافتراضية هي 12

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

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

