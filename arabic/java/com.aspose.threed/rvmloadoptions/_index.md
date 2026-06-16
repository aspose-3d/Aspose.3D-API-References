---
title: "RvmLoadOptions"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "خيارات التحميل لملف RVM الخاص بأنظمة إدارة تصميم مصانع AVEVA."
type: docs
weight: 157
url: /ar/java/com.aspose.threed/rvmloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class RvmLoadOptions extends LoadOptions
```

خيارات التحميل لملف RVM الخاص بنظام إدارة تصميم مصانع AVEVA. **مثال:** يوضح الشيفرة التالية كيفية تخصيص معلمات التسطير للأشكال الأولية المستوردة من ملف RVM باستخدام RvmLoadOptions.

```
RvmLoadOptions opt = new RvmLoadOptions();
             opt.setRectangularTorusSegments(30);
             opt.setCylinderRadialSegments(20);
             opt.setDishLatitudeSegments(20);
             opt.setDishLongitudeSegments(20);
             opt.setCenterScene(true);
             var scene = Scene.fromFile("input.rvm", opt);
             scene.save("output.obj");
```
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RvmLoadOptions(FileContentType contentType)](#RvmLoadOptions-com.aspose.threed.FileContentType-) | إنشاء مثيل من [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) |
| [RvmLoadOptions()](#RvmLoadOptions--) | إنشاء مثيل من [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributePrefix()](#getAttributePrefix--) | يحصل على بادئة السمات التي تم تعريفها في ملفات السمات الخارجية، تُستخدم البادئة لتجنب تعارض الأسماء، القيمة الافتراضية هي "rvm:" |
| [getCenterScene()](#getCenterScene--) | مركزة المشهد بعد تحميله. |
| [getClass()](#getClass--) |  |
| [getCylinderRadialSegments()](#getCylinderRadialSegments--) | يحصل على عدد قطاعات الأسطوانة الشعاعية، القيمة الافتراضية هي 16 |
| [getDishLatitudeSegments()](#getDishLatitudeSegments--) | يحصل على عدد قطاعات دائرة الطبق العرضية، القيمة الافتراضية هي 8 |
| [getDishLongitudeSegments()](#getDishLongitudeSegments--) | يحصل على عدد قطاعات دائرة الطبق الطولية، القيمة الافتراضية هي 12 |
| [getEncoding()](#getEncoding--) | يحصل على الترميز الافتراضي للملفات النصية. |
| [getFileFormat()](#getFileFormat--) | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [getFileName()](#getFileName--) | اسم ملف المشهد المصدر/المستورد. |
| [getFileSystem()](#getFileSystem--) | السماح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ. |
| [getFileSystemFactory()](#getFileSystemFactory--) | يحصل على فئة المصنع لنظام الملفات. |
| [getGenerateMaterials()](#getGenerateMaterials--) | إنشاء مواد بألوان عشوائية لكل كائن في المشهد إذا لم يتم تصدير جدول الألوان داخل ملف RVM. |
| [getLookupAttributes()](#getLookupAttributes--) | يحصل على ما إذا كان سيتم تحميل السمات من ملف قائمة السمات الخارجية (.att/.attrib/.txt)، القيمة الافتراضية هي true. |
| [getLookupPaths()](#getLookupPaths--) | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالعثور على الملف الخارجي للتحميل. |
| [getRectangularTorusSegments()](#getRectangularTorusSegments--) | يحصل على عدد قطاعات الحلقة المستطيلة الشعاعية، القيمة الافتراضية هي 20 |
| [getTorusTubularSegments()](#getTorusTubularSegments--) | يحصل على عدد قطاعات الحلقة الأنبوبيّة، القيمة الافتراضية هي 20 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | يضبط بادئة السمات التي تم تعريفها في ملفات السمات الخارجية، تُستخدم البادئة لتجنب تعارض الأسماء، القيمة الافتراضية هي "rvm:" |
| [setCenterScene(boolean value)](#setCenterScene-boolean-) | مركزة المشهد بعد تحميله. |
| [setCylinderRadialSegments(int value)](#setCylinderRadialSegments-int-) | يضبط عدد قطاعات الأسطوانة الشعاعية، القيمة الافتراضية هي 16 |
| [setDishLatitudeSegments(int value)](#setDishLatitudeSegments-int-) | يضبط عدد قطاعات دائرة الطبق العرضية، القيمة الافتراضية هي 8 |
| [setDishLongitudeSegments(int value)](#setDishLongitudeSegments-int-) | يضبط عدد قطاعات دائرة الطبق الطولية، القيمة الافتراضية هي 12 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | يضبط الترميز الافتراضي للملفات النصية. |
| [setFileName(String value)](#setFileName-java.lang.String-) | اسم ملف المشهد المصدر/المستورد. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | السماح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | يضبط فئة المصنع لنظام الملفات. |
| [setGenerateMaterials(boolean value)](#setGenerateMaterials-boolean-) | إنشاء مواد بألوان عشوائية لكل كائن في المشهد إذا لم يتم تصدير جدول الألوان داخل ملف RVM. |
| [setLookupAttributes(boolean value)](#setLookupAttributes-boolean-) | يضبط ما إذا كان سيتم تحميل السمات من ملف قائمة السمات الخارجية (.att/.attrib/.txt)، القيمة الافتراضية هي true. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالعثور على الملف الخارجي للتحميل. |
| [setRectangularTorusSegments(int value)](#setRectangularTorusSegments-int-) | يضبط عدد قطاعات الحلقة المستطيلة الشعاعية، القيمة الافتراضية هي 20 |
| [setTorusTubularSegments(int value)](#setTorusTubularSegments-int-) | يضبط عدد قطاعات الحلقة الأنبوبيّة، القيمة الافتراضية هي 20 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmLoadOptions(FileContentType contentType) {#RvmLoadOptions-com.aspose.threed.FileContentType-}
```
public RvmLoadOptions(FileContentType contentType)
```


إنشاء مثيل من [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### RvmLoadOptions() {#RvmLoadOptions--}
```
public RvmLoadOptions()
```


إنشاء مثيل من [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions)

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
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


يحصل على بادئة السمات التي تم تعريفها في ملفات السمات الخارجية، تُستخدم البادئة لتجنب تعارض الأسماء، القيمة الافتراضية هي "rvm:"

**Returns:**
java.lang.String - البادئة للسمات التي تم تعريفها في ملفات السمات الخارجية، تُستخدم البادئة لتجنب تعارض الأسماء، القيمة الافتراضية هي "rvm:"
### getCenterScene() {#getCenterScene--}
```
public boolean getCenterScene()
```


مركزة المشهد بعد تحميله.

**Returns:**
boolean - مركز المشهد بعد تحميله.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCylinderRadialSegments() {#getCylinderRadialSegments--}
```
public int getCylinderRadialSegments()
```


يحصل على عدد قطاعات الأسطوانة الشعاعية، القيمة الافتراضية هي 16

**Returns:**
int - عدد القطاعات الشعاعية للأسطوانة، القيمة الافتراضية هي 16
### getDishLatitudeSegments() {#getDishLatitudeSegments--}
```
public int getDishLatitudeSegments()
```


يحصل على عدد قطاعات دائرة الطبق العرضية، القيمة الافتراضية هي 8

**Returns:**
int - عدد قطاعات خط العرض للطبق، القيمة الافتراضية هي 8
### getDishLongitudeSegments() {#getDishLongitudeSegments--}
```
public int getDishLongitudeSegments()
```


يحصل على عدد قطاعات دائرة الطبق الطولية، القيمة الافتراضية هي 12

**Returns:**
int - عدد قطاعات خط الطول للطبق، القيمة الافتراضية هي 12
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


يحصل على الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم.

**Returns:**
java.nio.charset.Charset - الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم.
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
### getGenerateMaterials() {#getGenerateMaterials--}
```
public boolean getGenerateMaterials()
```


إنشاء مواد بألوان عشوائية لكل كائن في المشهد إذا لم يتم تصدير جدول الألوان داخل ملف RVM. القيمة الافتراضية هي true

**Returns:**
boolean - إنشاء مواد بألوان عشوائية لكل كائن في المشهد إذا لم يتم تصدير جدول الألوان داخل ملف RVM. القيمة الافتراضية هي true
### getLookupAttributes() {#getLookupAttributes--}
```
public boolean getLookupAttributes()
```


يحصل على ما إذا كان سيتم تحميل السمات من ملف قائمة السمات الخارجية (.att/.attrib/.txt)، القيمة الافتراضية هي true.

**Returns:**
boolean - ما إذا كان سيتم تحميل السمات من ملف قائمة السمات الخارجية (.att/.attrib/.txt)، القيمة الافتراضية هي true.
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
### getRectangularTorusSegments() {#getRectangularTorusSegments--}
```
public int getRectangularTorusSegments()
```


يحصل على عدد قطاعات الحلقة المستطيلة الشعاعية، القيمة الافتراضية هي 20

**Returns:**
int - عدد القطاعات الشعاعية للطُرْس المستطيل، القيمة الافتراضية هي 20
### getTorusTubularSegments() {#getTorusTubularSegments--}
```
public int getTorusTubularSegments()
```


يحصل على عدد قطاعات الحلقة الأنبوبيّة، القيمة الافتراضية هي 20

**Returns:**
int - عدد القطاعات الأنبوبيّة للطُرْس، القيمة الافتراضية هي 20
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




### setAttributePrefix(String value) {#setAttributePrefix-java.lang.String-}
```
public void setAttributePrefix(String value)
```


يضبط بادئة السمات التي تم تعريفها في ملفات السمات الخارجية، تُستخدم البادئة لتجنب تعارض الأسماء، القيمة الافتراضية هي "rvm:"

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setCenterScene(boolean value) {#setCenterScene-boolean-}
```
public void setCenterScene(boolean value)
```


مركزة المشهد بعد تحميله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setCylinderRadialSegments(int value) {#setCylinderRadialSegments-int-}
```
public void setCylinderRadialSegments(int value)
```


يضبط عدد قطاعات الأسطوانة الشعاعية، القيمة الافتراضية هي 16

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setDishLatitudeSegments(int value) {#setDishLatitudeSegments-int-}
```
public void setDishLatitudeSegments(int value)
```


يضبط عدد قطاعات دائرة الطبق العرضية، القيمة الافتراضية هي 8

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setDishLongitudeSegments(int value) {#setDishLongitudeSegments-int-}
```
public void setDishLongitudeSegments(int value)
```


يضبط عدد قطاعات دائرة الطبق الطولية، القيمة الافتراضية هي 12

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدّر سيقرر أي ترميز يستخدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.nio.charset.Charset | القيمة الجديدة |

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

### setGenerateMaterials(boolean value) {#setGenerateMaterials-boolean-}
```
public void setGenerateMaterials(boolean value)
```


إنشاء مواد بألوان عشوائية لكل كائن في المشهد إذا لم يتم تصدير جدول الألوان داخل ملف RVM. القيمة الافتراضية هي true

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setLookupAttributes(boolean value) {#setLookupAttributes-boolean-}
```
public void setLookupAttributes(boolean value)
```


يضبط ما إذا كان سيتم تحميل السمات من ملف قائمة السمات الخارجية (.att/.attrib/.txt)، القيمة الافتراضية هي true.

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

### setRectangularTorusSegments(int value) {#setRectangularTorusSegments-int-}
```
public void setRectangularTorusSegments(int value)
```


يضبط عدد قطاعات الحلقة المستطيلة الشعاعية، القيمة الافتراضية هي 20

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setTorusTubularSegments(int value) {#setTorusTubularSegments-int-}
```
public void setTorusTubularSegments(int value)
```


يضبط عدد قطاعات الحلقة الأنبوبيّة، القيمة الافتراضية هي 20

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

