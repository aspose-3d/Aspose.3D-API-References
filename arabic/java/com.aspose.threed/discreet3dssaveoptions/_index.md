---
title: "Discreet3dsSaveOptions"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "خيارات الحفظ لملف 3DS."
type: docs
weight: 44
url: /ar/java/com.aspose.threed/discreet3dssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Discreet3dsSaveOptions extends SaveOptions
```

خيارات الحفظ لملف 3DS.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Discreet3dsSaveOptions()](#Discreet3dsSaveOptions--) | منشئ [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions) |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDuplicatedNameCounterBase()](#getDuplicatedNameCounterBase--) | العداد المستخدم لإنشاء اسم جديد للأسماء المكررة، القيمة الافتراضية هي 2. |
| [getDuplicatedNameCounterFormat()](#getDuplicatedNameCounterFormat--) | تنسيق العداد المكرر، القيمة الافتراضية هي سلسلة فارغة. |
| [getDuplicatedNameSeparator()](#getDuplicatedNameSeparator--) | الفاصل بين اسم الكائن والعداد المكرر، القيمة الافتراضية هي "\_". |
| [getEncoding()](#getEncoding--) | يحصل على الترميز الافتراضي للملفات النصية. |
| [getExportCamera()](#getExportCamera--) | يحدد ما إذا كان يتم تصدير جميع الكاميرات في المشهد. |
| [getExportLight()](#getExportLight--) | يحدد ما إذا كان يتم تصدير جميع الأضواء في المشهد. |
| [getExportTextures()](#getExportTextures--) | حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [getFileFormat()](#getFileFormat--) | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [getFileName()](#getFileName--) | اسم ملف المشهد المصدر/المستورد. |
| [getFileSystem()](#getFileSystem--) | السماح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ. |
| [getFileSystemFactory()](#getFileSystemFactory--) | يحصل على فئة المصنع لنظام الملفات. |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | يحصل على عكس نظام الإحداثيات لنقاط التحكم/العمود أثناء الاستيراد/التصدير. |
| [getGammaCorrectedColor()](#getGammaCorrectedColor--) | قد يحتوي ملف 3ds على اللون الأصلي واللون المصحح للجاما لنفس الخاصية، ضبط هذا على true سيستخدم اللون المصحح للجاما إذا كان ممكنًا، وإلا سيحاول Aspose.3D استخدام اللون الأصلي. |
| [getHighPreciseColor()](#getHighPreciseColor--) | إذا كان هذا صحيحًا، فإن ملف 3ds المُولد سيستخدم لونًا عالي الدقة، مما يعني أن كل قناة من الأحمر/الأخضر/الأزرق تكون في صيغة عائمة 32 بت. |
| [getLookupPaths()](#getLookupPaths--) | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالعثور على الملف الخارجي للتحميل. |
| [getMasterScale()](#getMasterScale--) | يحصل على مقياس الإتقان المستخدم في التصدير. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDuplicatedNameCounterBase(int value)](#setDuplicatedNameCounterBase-int-) | العداد المستخدم لإنشاء اسم جديد للأسماء المكررة، القيمة الافتراضية هي 2. |
| [setDuplicatedNameCounterFormat(String value)](#setDuplicatedNameCounterFormat-java.lang.String-) | تنسيق العداد المكرر، القيمة الافتراضية هي سلسلة فارغة. |
| [setDuplicatedNameSeparator(String value)](#setDuplicatedNameSeparator-java.lang.String-) | الفاصل بين اسم الكائن والعداد المكرر، القيمة الافتراضية هي "\_". |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | يضبط الترميز الافتراضي للملفات النصية. |
| [setExportCamera(boolean value)](#setExportCamera-boolean-) | يضبط ما إذا كان سيتم تصدير جميع الكاميرات في المشهد. |
| [setExportLight(boolean value)](#setExportLight-boolean-) | يضبط ما إذا كان سيتم تصدير جميع الأضواء في المشهد. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [setFileName(String value)](#setFileName-java.lang.String-) | اسم ملف المشهد المصدر/المستورد. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | السماح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | يضبط فئة المصنع لنظام الملفات. |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | يضبط عكس نظام الإحداثيات لنقاط التحكم/العمود أثناء الاستيراد/التصدير. |
| [setGammaCorrectedColor(boolean value)](#setGammaCorrectedColor-boolean-) | قد يحتوي ملف 3ds على اللون الأصلي واللون المصحح للجاما لنفس الخاصية، ضبط هذا على true سيستخدم اللون المصحح للجاما إذا كان ممكنًا، وإلا سيحاول Aspose.3D استخدام اللون الأصلي. |
| [setHighPreciseColor(boolean value)](#setHighPreciseColor-boolean-) | إذا كان هذا صحيحًا، فإن ملف 3ds المُولد سيستخدم لونًا عالي الدقة، مما يعني أن كل قناة من الأحمر/الأخضر/الأزرق تكون في صيغة عائمة 32 بت. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالعثور على الملف الخارجي للتحميل. |
| [setMasterScale(double value)](#setMasterScale-double-) | يضبط مقياس الإعداد الرئيسي المستخدم في التصدير. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Discreet3dsSaveOptions() {#Discreet3dsSaveOptions--}
```
public Discreet3dsSaveOptions()
```


منشئ [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions)

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
### getDuplicatedNameCounterBase() {#getDuplicatedNameCounterBase--}
```
public int getDuplicatedNameCounterBase()
```


العداد المستخدم لإنشاء اسم جديد للأسماء المكررة، القيمة الافتراضية هي 2.

**Returns:**
int - العداد المستخدم لإنشاء اسم جديد للأسماء المكررة، القيمة الافتراضية هي 2.
### getDuplicatedNameCounterFormat() {#getDuplicatedNameCounterFormat--}
```
public String getDuplicatedNameCounterFormat()
```


تنسيق العداد المكرر، القيمة الافتراضية هي سلسلة فارغة.

**Returns:**
java.lang.String - تنسيق العداد المكرر، القيمة الافتراضية هي سلسلة فارغة.
### getDuplicatedNameSeparator() {#getDuplicatedNameSeparator--}
```
public String getDuplicatedNameSeparator()
```


الفاصل بين اسم الكائن والعداد المكرر، القيمة الافتراضية هي "\_". عندما يحتوي المشهد على كائنات تستخدم نفس الاسم، سيولد مُصدّر Aspose.3D 3DS اسمًا مختلفًا للكائن. على سبيل المثال هناك عقدتين تحملان الاسم "Box"، ستحصل العقدة الأولى على الاسم "Box"، وستحصل العقدة الثانية على اسم جديد "Box\_2" باستخدام الإعداد الافتراضي.

**Returns:**
java.lang.String - الفاصل بين اسم الكائن والعداد المكرر، القيمة الافتراضية هي "\_". عندما يحتوي المشهد على كائنات تستخدم نفس الاسم، سيولد مُصدّر Aspose.3D 3DS اسمًا مختلفًا للكائن. على سبيل المثال هناك عقدتين تحملان الاسم "Box"، ستحصل العقدة الأولى على الاسم "Box"، وستحصل العقدة الثانية على اسم جديد "Box\_2" باستخدام الإعداد الافتراضي.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


يحصل على الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم.

**Returns:**
java.nio.charset.Charset - الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم.
### getExportCamera() {#getExportCamera--}
```
public boolean getExportCamera()
```


يحدد ما إذا كان يتم تصدير جميع الكاميرات في المشهد.

**Returns:**
boolean - ما إذا كان سيتم تصدير جميع الكاميرات في المشهد.
### getExportLight() {#getExportLight--}
```
public boolean getExportLight()
```


يحدد ما إذا كان يتم تصدير جميع الأضواء في المشهد.

**Returns:**
boolean - ما إذا كان سيتم تصدير جميع الأضواء في المشهد.
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
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


يحصل على عكس نظام الإحداثيات لنقاط التحكم/العمود أثناء الاستيراد/التصدير.

**Returns:**
boolean - عكس نظام إحداثيات نقاط التحكم/العمودي أثناء الاستيراد/التصدير.
### getGammaCorrectedColor() {#getGammaCorrectedColor--}
```
public boolean getGammaCorrectedColor()
```


قد يحتوي ملف 3ds على اللون الأصلي واللون المصحح للجاما لنفس الخاصية، ضبط هذا على true سيستخدم اللون المصحح للجاما إذا كان ممكنًا، وإلا سيحاول Aspose.3D استخدام اللون الأصلي.

**Returns:**
boolean - قد يحتوي ملف 3ds على اللون الأصلي واللون المصحح غاما لنفس الخاصية، ضبط هذا على true سيستخدم اللون المصحح غاما إذا كان ممكنًا، وإلا سيحاول Aspose.3D استخدام اللون الأصلي.
### getHighPreciseColor() {#getHighPreciseColor--}
```
public boolean getHighPreciseColor()
```


إذا كان هذا صحيحًا، سيستخدم ملف 3ds المُولد لونًا عالي الدقة، مما يعني أن كل قناة من الأحمر/الأخضر/الأزرق تكون في صيغة 32 بت عائمة. وإلا سيستخدم الملف المُولد لونًا 24 بت، حيث كل قناة تستخدم بايت 8 بت. القيمة الافتراضية هي false، لأن ليس كل التطبيقات تدعم اللون عالي الدقة.

**Returns:**
boolean - إذا كان هذا صحيحًا، سيستخدم ملف 3ds المُولد لونًا عالي الدقة، مما يعني أن كل قناة من الأحمر/الأخضر/الأزرق تكون في صيغة 32 بت عائمة. وإلا سيستخدم الملف المُولد لونًا 24 بت، حيث كل قناة تستخدم بايت 8 بت. القيمة الافتراضية هي false، لأن ليس كل التطبيقات تدعم اللون عالي الدقة.
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
### getMasterScale() {#getMasterScale--}
```
public double getMasterScale()
```


يحصل على مقياس الإتقان المستخدم في التصدير.

**Returns:**
double - مقياس الإعداد الرئيسي المستخدم في التصدير.
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




### setDuplicatedNameCounterBase(int value) {#setDuplicatedNameCounterBase-int-}
```
public void setDuplicatedNameCounterBase(int value)
```


العداد المستخدم لإنشاء اسم جديد للأسماء المكررة، القيمة الافتراضية هي 2.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setDuplicatedNameCounterFormat(String value) {#setDuplicatedNameCounterFormat-java.lang.String-}
```
public void setDuplicatedNameCounterFormat(String value)
```


تنسيق العداد المكرر، القيمة الافتراضية هي سلسلة فارغة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setDuplicatedNameSeparator(String value) {#setDuplicatedNameSeparator-java.lang.String-}
```
public void setDuplicatedNameSeparator(String value)
```


الفاصل بين اسم الكائن والعداد المكرر، القيمة الافتراضية هي "\_". عندما يحتوي المشهد على كائنات تستخدم نفس الاسم، سيولد مُصدّر Aspose.3D 3DS اسمًا مختلفًا للكائن. على سبيل المثال هناك عقدتين تحملان الاسم "Box"، ستحصل العقدة الأولى على الاسم "Box"، وستحصل العقدة الثانية على اسم جديد "Box\_2" باستخدام الإعداد الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدّر سيقرر أي ترميز يستخدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.nio.charset.Charset | القيمة الجديدة |

### setExportCamera(boolean value) {#setExportCamera-boolean-}
```
public void setExportCamera(boolean value)
```


يضبط ما إذا كان سيتم تصدير جميع الكاميرات في المشهد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setExportLight(boolean value) {#setExportLight-boolean-}
```
public void setExportLight(boolean value)
```


يضبط ما إذا كان سيتم تصدير جميع الأضواء في المشهد.

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

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


يضبط عكس نظام الإحداثيات لنقاط التحكم/العمود أثناء الاستيراد/التصدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setGammaCorrectedColor(boolean value) {#setGammaCorrectedColor-boolean-}
```
public void setGammaCorrectedColor(boolean value)
```


قد يحتوي ملف 3ds على اللون الأصلي واللون المصحح للجاما لنفس الخاصية، ضبط هذا على true سيستخدم اللون المصحح للجاما إذا كان ممكنًا، وإلا سيحاول Aspose.3D استخدام اللون الأصلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setHighPreciseColor(boolean value) {#setHighPreciseColor-boolean-}
```
public void setHighPreciseColor(boolean value)
```


إذا كان هذا صحيحًا، سيستخدم ملف 3ds المُولد لونًا عالي الدقة، مما يعني أن كل قناة من الأحمر/الأخضر/الأزرق تكون في صيغة 32 بت عائمة. وإلا سيستخدم الملف المُولد لونًا 24 بت، حيث كل قناة تستخدم بايت 8 بت. القيمة الافتراضية هي false، لأن ليس كل التطبيقات تدعم اللون عالي الدقة.

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

### setMasterScale(double value) {#setMasterScale-double-}
```
public void setMasterScale(double value)
```


يضبط مقياس الإعداد الرئيسي المستخدم في التصدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

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

