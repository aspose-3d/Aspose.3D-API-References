---
title: "FileSystem"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "تغليف نظام الملفات."
type: docs
weight: 67
url: /ar/java/com.aspose.threed/filesystem/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class FileSystem implements Closeable
```

تغليف نظام الملفات. ستستخدم Aspose.3D هذا لقراءة/كتابة الاعتمادات. **مثال:** يوضح الشيفرة التالية كيفية استيراد ملف، وتوفير الملفات التابعة في دليل معين

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new LocalFileSystem("textures/"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FileSystem()](#FileSystem--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [close()](#close--) | قم بتحرير نظام الملفات وإصدار موارده. |
| [createDummyFileSystem()](#createDummyFileSystem--) | إنشاء نظام ملفات تجريبي، عمليات القراءة/الكتابة هي عمليات تجريبية. |
| [createLocalFileSystem(String directory)](#createLocalFileSystem-java.lang.String-) | تهيئة [FileSystem](../../com.aspose.threed/filesystem) جديد يقتصر على الوصول إلى الدليل المحلي. |
| [createMemoryFileSystem()](#createMemoryFileSystem--) | إنشاء نظام ملفات قائم على الذاكرة سيقوم بربط عمليات القراءة/الكتابة بالذاكرة. |
| [createMemoryFileSystem(HashMap<String,MemoryStream> files)](#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--) | إنشاء نظام ملفات قائم على الذاكرة سيقوم بربط عمليات القراءة/الكتابة بالذاكرة. |
| [createZipFileSystem(Stream stream)](#createZipFileSystem-com.aspose.threed.Stream-) | إنشاء نظام ملفات لتوفير وصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. |
| [createZipFileSystem(Stream stream, String baseDir)](#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-) | إنشاء نظام ملفات لتوفير وصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. |
| [createZipFileSystem(String fileName)](#createZipFileSystem-java.lang.String-) | نظام الملفات لتوفير وصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | إنشاء تدفق لقراءة التبعيات. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | إنشاء تدفق لكتابة التبعيات. |
### FileSystem() {#FileSystem--}
```
public FileSystem()
```


### close() {#close--}
```
public void close()
```


قم بتحرير نظام الملفات وإصدار موارده.

### createDummyFileSystem() {#createDummyFileSystem--}
```
public static FileSystem createDummyFileSystem()
```


إنشاء نظام ملفات تجريبي، عمليات القراءة/الكتابة هي عمليات تجريبية.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A dummy file system **Example:** The following code shows how to export file to memory, and ignore all dependent file generation.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var dfs = FileSystem.CreateDummyFileSystem();
     opt.setFileSystem(dfs);
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
```
### createLocalFileSystem(String directory) {#createLocalFileSystem-java.lang.String-}
```
public static FileSystem createLocalFileSystem(String directory)
```


تهيئة [FileSystem](../../com.aspose.threed/filesystem) جديد يقتصر على الوصول إلى الدليل المحلي. جميع عمليات القراءة/الكتابة على هذه المثيلة من FileSystem سيتم ربطها بالدليل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| دليل | java.lang.String | الدليل في نظام الملفات الفعلي الخاص بك كدليل الجذر الافتراضي. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A new instance of file system to provide local file access
### createMemoryFileSystem() {#createMemoryFileSystem--}
```
public static FileSystem createMemoryFileSystem()
```


إنشاء نظام ملفات قائم على الذاكرة سيقوم بربط عمليات القراءة/الكتابة بالذاكرة.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A memory-based file system **Example:** The following code shows how to export file to memory, includes the dependent file by using MemoryFileSystem.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var mfs = new HashMap<String, MemoryStream>();
     opt.setFileSystem(FileSystem.createMemoryFileSystem(mfs));
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
     //the test.obj was written to variable ms, and we can also get the test.mtl file content by
     var materialFile = mfs.get("test.mtl");
```
### createMemoryFileSystem(HashMap<String,MemoryStream> files) {#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--}
```
public static FileSystem createMemoryFileSystem(HashMap<String,MemoryStream> files)
```


إنشاء نظام ملفات قائم على الذاكرة سيقوم بربط عمليات القراءة/الكتابة بالذاكرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملفات | java.util.HashMap<java.lang.String,com.aspose.threed.MemoryStream> | هذا يتيح لك قراءة/كتابة الملفات الافتراضية. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A memory-based file system **Example:** The following code shows how to export file to memory, includes the dependent file by using MemoryFileSystem.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var mfs = new HashMap<String, MemoryStream>();
     opt.setFileSystem(FileSystem.createMemoryFileSystem(mfs));
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
     //the test.obj was written to variable ms, and we can also get the test.mtl file content by
     var materialFile = mfs.get("test.mtl");
```
### createZipFileSystem(Stream stream) {#createZipFileSystem-com.aspose.threed.Stream-}
```
public static FileSystem createZipFileSystem(Stream stream)
```


إنشاء نظام ملفات لتوفير وصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. سيتم التخلص من نظام الملفات بعد عملية الفتح/الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | التدفق للوصول إلى ملف zip |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(Stream stream, String baseDir) {#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-}
```
public static FileSystem createZipFileSystem(Stream stream, String baseDir)
```


إنشاء نظام ملفات لتوفير وصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. سيتم التخلص من نظام الملفات بعد عملية الفتح/الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | التدفق للوصول إلى ملف zip |
| baseDir | java.lang.String | الدليل الأساسي داخل ملف zip. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(String fileName) {#createZipFileSystem-java.lang.String-}
```
public static FileSystem createZipFileSystem(String fileName)
```


نظام ملفات لتوفير وصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. سيتم التخلص من نظام الملفات بعد عملية الفتح/الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف لملف zip. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
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




### readFile(String fileName, IOConfig options) {#readFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream readFile(String fileName, IOConfig options)
```


إنشاء تدفق لقراءة التبعيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف للفتح للقراءة |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | خيارات الحفظ أو التحميل |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for reading the file.
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

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream writeFile(String fileName, IOConfig options)
```


إنشاء تدفق لكتابة التبعيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف للفتح للكتابة |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | خيارات الحفظ أو التحميل |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for writing the file
