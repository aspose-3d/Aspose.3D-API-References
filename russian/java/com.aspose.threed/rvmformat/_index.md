---
title: RvmFormat
second_title: Справочник API Aspose.3D для Java
description: Формат RVM
type: docs
weight: 156
url: /ru/java/com.aspose.threed/rvmformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileFormat](../../com.aspose.threed/fileformat)
```
public class RvmFormat extends FileFormat
```

Формат RVM
## Поля

| Поле | Описание |
| --- | --- |
| [AMF](#AMF) | Формат файла аддитивного производства |
| [ASE](#ASE) | Формат ASCII Scene Exporter программы 3D Studio Max. |
| [ASPOSE3D_WEB](#ASPOSE3D-WEB) | Формат Aspose.3D Web. |
| [BLENDER](#BLENDER) | Формат 3D файла Blender |
| [COLLADA](#COLLADA) | Формат файла Collada |
| [DISCREET3DS](#DISCREET3DS) | Формат файла 3D Studio |
| [DRACO](#DRACO) | Google Draco Mesh |
| [DXF](#DXF) | AutoCAD DXF |
| [FBX6100ASCII](#FBX6100ASCII) | ASCII FBX формат файла, версия 6.1.0 |
| [FBX6100_BINARY](#FBX6100-BINARY) | Binary FBX формат файла, версия 6.1.0 |
| [FBX7200ASCII](#FBX7200ASCII) | ASCII FBX формат файла, версия 7.2.0 |
| [FBX7200_BINARY](#FBX7200-BINARY) | Binary FBX формат файла, версия 7.2.0 |
| [FBX7300ASCII](#FBX7300ASCII) | ASCII FBX формат файла, версия 7.3.0 |
| [FBX7300_BINARY](#FBX7300-BINARY) | Binary FBX формат файла, версия 7.3.0 |
| [FBX7400ASCII](#FBX7400ASCII) | ASCII FBX формат файла, версия 7.4.0 |
| [FBX7400_BINARY](#FBX7400-BINARY) | Binary FBX формат файла, версия 7.4.0 |
| [FBX7500ASCII](#FBX7500ASCII) | Формат файла ASCII FBX, версия 7.5.0 |
| [FBX7500_BINARY](#FBX7500-BINARY) | Формат файла Binary FBX, версия 7.5.0 |
| [FBX7600ASCII](#FBX7600ASCII) | Формат файла ASCII FBX, версия 7.6.0 |
| [FBX7600_BINARY](#FBX7600-BINARY) | Формат файла Binary FBX, версия 7.6.0 |
| [FBX7700ASCII](#FBX7700ASCII) | Формат файла ASCII FBX, версия 7.7.0 |
| [FBX7700_BINARY](#FBX7700-BINARY) | Формат файла Binary FBX, версия 7.7.0 |
| [GLTF](#GLTF) | glTF группы Khronos |
| [GLTF2](#GLTF2) | glTF версии 2.0 группы Khronos |
| [GLTF2_BINARY](#GLTF2-BINARY) | glTF версии 2.0 группы Khronos |
| [GLTF_BINARY](#GLTF-BINARY) | glTF в бинарном формате группы Khronos |
| [HTML5](#HTML5) | Файл HTML5 |
| [IFC](#IFC) | Модель данных ISO 16739-1 Industry Foundation Classes. |
| [MAYAASCII](#MAYAASCII) | Autodesk Maya в формате ASCII |
| [MAYA_BINARY](#MAYA-BINARY) | Autodesk Maya в бинарном формате |
| [MICROSOFT3MF](#MICROSOFT3MF) | Microsoft 3D Manufacturing Format |
| [PCD](#PCD) | Файл PCL Point Cloud Data в режиме ASCII |
| [PCD_BINARY](#PCD-BINARY) | Файл PCL Point Cloud Data в бинарном режиме |
| [PDF](#PDF) | Portable Document Format от Adobe |
| [PLY](#PLY) | Polygon File Format или Stanford Triangle Format |
| [RVM_BINARY](#RVM-BINARY) | Модель AVEVA Plant Design Management System в бинарном формате |
| [RVM_TEXT](#RVM-TEXT) | Модель AVEVA Plant Design Management System в текстовом формате |
| [SIEMENSJT8](#SIEMENSJT8) | Файл Siemens JT версии 8 |
| [SIEMENSJT9](#SIEMENSJT9) | Файл Siemens JT версии 9 |
| [STLASCII](#STLASCII) | Формат файла ASCII STL |
| [STL_BINARY](#STL-BINARY) | Формат файла Binary STL |
| [UNIVERSAL3D](#UNIVERSAL3D) | Формат файла Universal3D |
| [USD](#USD) | Универсальное описание сцены |
| [USDA](#USDA) | Универсальное описание сцены в формате ASCII. |
| [USDZ](#USDZ) | Сжатое универсальное описание сцены |
| [VRML](#VRML) | Язык моделирования виртуальной реальности |
| [WAVEFRONTOBJ](#WAVEFRONTOBJ) | Формат файла Obj от Wavefront |
| [XYZ](#XYZ) | Файл облака точек Xyz |
| [X_BINARY](#X-BINARY) | Файл DirectX X в бинарном формате |
| [X_TEXT](#X-TEXT) | Файл DirectX X в бинарном формате |
| [ZIP](#ZIP) | ZIP-архив, содержащий другие 3D форматы файлов. |
## Методы

| Метод | Описание |
| --- | --- |
| [createLoadOptions()](#createLoadOptions--) | Создать параметры загрузки по умолчанию для этого формата файла |
| [createSaveOptions()](#createSaveOptions--) | Создать параметры сохранения по умолчанию для этого формата файла |
| [detect(Stream stream, String fileName)](#detect-com.aspose.threed.Stream-java.lang.String-) | Определить формат файла из потока данных, имя файла является необязательным для угадывания типов без магического заголовка. |
| [detect(String fileName)](#detect-java.lang.String-) | Определить формат файла по имени файла, файл должен быть доступен для чтения, чтобы Aspose.3D мог определить формат файла по заголовку. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanExport()](#getCanExport--) | Получает, поддерживает ли Aspose.3D экспорт сцены в текущий формат файла. |
| [getCanImport()](#getCanImport--) | Получает, поддерживает ли Aspose.3D импорт сцены из текущего формата файла. |
| [getClass()](#getClass--) |  |
| [getContentType()](#getContentType--) | Получает тип содержимого формата файла |
| [getExtension()](#getExtension--) | Получает имя расширения этого типа. |
| [getExtensions()](#getExtensions--) | Получает имена расширений этого типа. |
| [getFileFormatType()](#getFileFormatType--) | Получает тип формата файла |
| [getFormatByExtension(String extensionName)](#getFormatByExtension-java.lang.String-) | Получает предпочтительный формат файла по имени расширения. Имя расширения должно начинаться с точки ('.'). |
| [getFormats()](#getFormats--) | Доступ ко всем поддерживаемым форматам |
| [getVersion()](#getVersion--) | Получает версию формата файла |
| [hashCode()](#hashCode--) |  |
| [loadAttributes(Scene scene, Stream stream)](#loadAttributes-com.aspose.threed.Scene-com.aspose.threed.Stream-) | Загрузить атрибуты из указанного потока |
| [loadAttributes(Scene scene, Stream stream, String prefix)](#loadAttributes-com.aspose.threed.Scene-com.aspose.threed.Stream-java.lang.String-) | Загрузить атрибуты из указанного потока |
| [loadAttributes(Scene scene, String fileName)](#loadAttributes-com.aspose.threed.Scene-java.lang.String-) | Загрузить атрибуты из указанного имени файла |
| [loadAttributes(Scene scene, String fileName, String prefix)](#loadAttributes-com.aspose.threed.Scene-java.lang.String-java.lang.String-) | Загрузить атрибуты из указанного имени файла |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Форматы в строку |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AMF {#AMF}
```
public static final FileFormat AMF
```


Формат файла аддитивного производства

### ASE {#ASE}
```
public static final FileFormat ASE
```


Формат ASCII Scene Exporter программы 3D Studio Max.

### ASPOSE3D_WEB {#ASPOSE3D-WEB}
```
public static final FileFormat ASPOSE3D_WEB
```


Формат Aspose.3D Web.

### BLENDER {#BLENDER}
```
public static final FileFormat BLENDER
```


Формат 3D файла Blender

### COLLADA {#COLLADA}
```
public static final FileFormat COLLADA
```


Формат файла Collada

### DISCREET3DS {#DISCREET3DS}
```
public static final FileFormat DISCREET3DS
```


Формат файла 3D Studio

### DRACO {#DRACO}
```
public static final DracoFormat DRACO
```


Google Draco Mesh

### DXF {#DXF}
```
public static final FileFormat DXF
```


AutoCAD DXF

### FBX6100ASCII {#FBX6100ASCII}
```
public static final FileFormat FBX6100ASCII
```


ASCII FBX формат файла, версия 6.1.0

### FBX6100_BINARY {#FBX6100-BINARY}
```
public static final FileFormat FBX6100_BINARY
```


Binary FBX формат файла, версия 6.1.0

### FBX7200ASCII {#FBX7200ASCII}
```
public static final FileFormat FBX7200ASCII
```


ASCII FBX формат файла, версия 7.2.0

### FBX7200_BINARY {#FBX7200-BINARY}
```
public static final FileFormat FBX7200_BINARY
```


Binary FBX формат файла, версия 7.2.0

### FBX7300ASCII {#FBX7300ASCII}
```
public static final FileFormat FBX7300ASCII
```


ASCII FBX формат файла, версия 7.3.0

### FBX7300_BINARY {#FBX7300-BINARY}
```
public static final FileFormat FBX7300_BINARY
```


Binary FBX формат файла, версия 7.3.0

### FBX7400ASCII {#FBX7400ASCII}
```
public static final FileFormat FBX7400ASCII
```


ASCII FBX формат файла, версия 7.4.0

### FBX7400_BINARY {#FBX7400-BINARY}
```
public static final FileFormat FBX7400_BINARY
```


Binary FBX формат файла, версия 7.4.0

### FBX7500ASCII {#FBX7500ASCII}
```
public static final FileFormat FBX7500ASCII
```


Формат файла ASCII FBX, версия 7.5.0

### FBX7500_BINARY {#FBX7500-BINARY}
```
public static final FileFormat FBX7500_BINARY
```


Формат файла Binary FBX, версия 7.5.0

### FBX7600ASCII {#FBX7600ASCII}
```
public static final FileFormat FBX7600ASCII
```


Формат файла ASCII FBX, версия 7.6.0

### FBX7600_BINARY {#FBX7600-BINARY}
```
public static final FileFormat FBX7600_BINARY
```


Формат файла Binary FBX, версия 7.6.0

### FBX7700ASCII {#FBX7700ASCII}
```
public static final FileFormat FBX7700ASCII
```


Формат файла ASCII FBX, версия 7.7.0

### FBX7700_BINARY {#FBX7700-BINARY}
```
public static final FileFormat FBX7700_BINARY
```


Формат файла Binary FBX, версия 7.7.0

### GLTF {#GLTF}
```
public static final FileFormat GLTF
```


glTF группы Khronos

### GLTF2 {#GLTF2}
```
public static final FileFormat GLTF2
```


glTF версии 2.0 группы Khronos

### GLTF2_BINARY {#GLTF2-BINARY}
```
public static final FileFormat GLTF2_BINARY
```


glTF версии 2.0 группы Khronos

### GLTF_BINARY {#GLTF-BINARY}
```
public static final FileFormat GLTF_BINARY
```


glTF в бинарном формате группы Khronos

### HTML5 {#HTML5}
```
public static final FileFormat HTML5
```


Файл HTML5

### IFC {#IFC}
```
public static final FileFormat IFC
```


Модель данных ISO 16739-1 Industry Foundation Classes.

### MAYAASCII {#MAYAASCII}
```
public static final FileFormat MAYAASCII
```


Autodesk Maya в формате ASCII

### MAYA_BINARY {#MAYA-BINARY}
```
public static final FileFormat MAYA_BINARY
```


Autodesk Maya в бинарном формате

### MICROSOFT3MF {#MICROSOFT3MF}
```
public static final Microsoft3MFFormat MICROSOFT3MF
```


Microsoft 3D Manufacturing Format

### PCD {#PCD}
```
public static final FileFormat PCD
```


Файл PCL Point Cloud Data в режиме ASCII

### PCD_BINARY {#PCD-BINARY}
```
public static final FileFormat PCD_BINARY
```


Файл PCL Point Cloud Data в бинарном режиме

### PDF {#PDF}
```
public static final PdfFormat PDF
```


Portable Document Format от Adobe

### PLY {#PLY}
```
public static final PlyFormat PLY
```


Polygon File Format или Stanford Triangle Format

### RVM_BINARY {#RVM-BINARY}
```
public static final RvmFormat RVM_BINARY
```


Модель AVEVA Plant Design Management System в бинарном формате

### RVM_TEXT {#RVM-TEXT}
```
public static final RvmFormat RVM_TEXT
```


Модель AVEVA Plant Design Management System в текстовом формате

### SIEMENSJT8 {#SIEMENSJT8}
```
public static final FileFormat SIEMENSJT8
```


Файл Siemens JT версии 8

### SIEMENSJT9 {#SIEMENSJT9}
```
public static final FileFormat SIEMENSJT9
```


Файл Siemens JT версии 9

### STLASCII {#STLASCII}
```
public static final FileFormat STLASCII
```


Формат файла ASCII STL

### STL_BINARY {#STL-BINARY}
```
public static final FileFormat STL_BINARY
```


Формат файла Binary STL

### UNIVERSAL3D {#UNIVERSAL3D}
```
public static final FileFormat UNIVERSAL3D
```


Формат файла Universal3D

### USD {#USD}
```
public static final FileFormat USD
```


Универсальное описание сцены

### USDA {#USDA}
```
public static final FileFormat USDA
```


Универсальное описание сцены в формате ASCII.

### USDZ {#USDZ}
```
public static final FileFormat USDZ
```


Сжатое универсальное описание сцены

### VRML {#VRML}
```
public static final FileFormat VRML
```


Язык моделирования виртуальной реальности

### WAVEFRONTOBJ {#WAVEFRONTOBJ}
```
public static final FileFormat WAVEFRONTOBJ
```


Формат файла Obj от Wavefront

### XYZ {#XYZ}
```
public static final FileFormat XYZ
```


Файл облака точек Xyz

### X_BINARY {#X-BINARY}
```
public static final FileFormat X_BINARY
```


Файл DirectX X в бинарном формате

### X_TEXT {#X-TEXT}
```
public static final FileFormat X_TEXT
```


Файл DirectX X в бинарном формате

### ZIP {#ZIP}
```
public static final FileFormat ZIP
```


ZIP-архив, содержащий другие 3D форматы файлов.

### createLoadOptions() {#createLoadOptions--}
```
public LoadOptions createLoadOptions()
```


Создать параметры загрузки по умолчанию для этого формата файла

**Returns:**
[LoadOptions](../../com.aspose.threed/loadoptions) - A default load option for current format
### createSaveOptions() {#createSaveOptions--}
```
public SaveOptions createSaveOptions()
```


Создать параметры сохранения по умолчанию для этого формата файла

**Returns:**
[SaveOptions](../../com.aspose.threed/saveoptions) - A default save option for current format
### detect(Stream stream, String fileName) {#detect-com.aspose.threed.Stream-java.lang.String-}
```
public static FileFormat detect(Stream stream, String fileName)
```


Определить формат файла из потока данных, имя файла является необязательным для угадывания типов без магического заголовка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Поток, содержащий данные для определения |
| fileName | java.lang.String | Исходное имя файла данных, используемое как подсказка. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### detect(String fileName) {#detect-java.lang.String-}
```
public static FileFormat detect(String fileName)
```


Определить формат файла по имени файла, файл должен быть доступен для чтения, чтобы Aspose.3D мог определить формат файла по заголовку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Путь к файлу для определения формата файла. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCanExport() {#getCanExport--}
```
public boolean getCanExport()
```


Получает, поддерживает ли Aspose.3D экспорт сцены в текущий формат файла.

**Returns:**
boolean - поддерживает ли Aspose.3D экспорт сцены в текущий формат файла. **Пример:** Следующий код показывает, как проверить, поддерживается ли экспорт в указанный формат.

```
var outputFormat = ".glb";
     var format = FileFormat.getFormatByExtension(outputFormat);
     if (format.getCanExport())
         System.out.printf("Can export to %s", outputFormat);
```
### getCanImport() {#getCanImport--}
```
public boolean getCanImport()
```


Получает, поддерживает ли Aspose.3D импорт сцены из текущего формата файла.

**Returns:**
boolean - поддерживает ли Aspose.3D импорт сцены из текущего формата файла. **Пример:** Следующий код показывает, как проверить, поддерживается ли импорт из указанного формата.

```
var outputFormat = ".glb";
     var format = FileFormat.getFormatByExtension(outputFormat);
     if (format.getCanImport())
         System.out.printf("Can import from %s", outputFormat);
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentType() {#getContentType--}
```
public FileContentType getContentType()
```


Получает тип содержимого формата файла

**Returns:**
[FileContentType](../../com.aspose.threed/filecontenttype) - file format content type **Example:**

```
var format = FileFormat.MAYA_BINARY;
     if (format.getContentType() == FileContentType.BINARY)
         System.out.printf("%s is binary format", format);
     else
         System.out.printf("%s is text-based format", format);
```
### getExtension() {#getExtension--}
```
public String getExtension()
```


Получает имя расширения этого типа.

**Returns:**
java.lang.String - имя расширения этого типа. **Пример:**

```
var format = FileFormat.MAYA_BINARY;
     System.out.printf("Extension of %s is %s", format, format.getExtension());
```
### getExtensions() {#getExtensions--}
```
public String[] getExtensions()
```


Получает имена расширений этого типа.

**Returns:**
java.lang.String[] - имена расширений этого типа.
### getFileFormatType() {#getFileFormatType--}
```
public FileFormatType getFileFormatType()
```


Получает тип формата файла

**Returns:**
[FileFormatType](../../com.aspose.threed/fileformattype) - file format type
### getFormatByExtension(String extensionName) {#getFormatByExtension-java.lang.String-}
```
public static FileFormat getFormatByExtension(String extensionName)
```


Получает предпочтительный формат файла по имени расширения. Имя расширения должно начинаться с точки ('.').

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| extensionName | java.lang.String | Имя расширения начинается с '.' для запроса. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - Instance of [FileFormat](../../com.aspose.threed/fileformat), otherwise null returned. **Example:** The following code shows how to save scene to memory using specified format

```
Scene scene = new Scene(new Box());
     var outputFormat = ".glb";
     var format = FileFormat.getFormatByExtension(outputFormat);
     var output = new ByteArrayOutputStream();
     scene.save(output);
```
### getFormats() {#getFormats--}
```
public static List<FileFormat> getFormats()
```


Доступ ко всем поддерживаемым форматам

**Returns:**
java.util.List<com.aspose.threed.FileFormat> - Доступ ко всем поддерживаемым форматам
### getVersion() {#getVersion--}
```
public Version getVersion()
```


Получает версию формата файла

**Returns:**
[Version](../../com.aspose.threed/version) - file format version
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadAttributes(Scene scene, Stream stream) {#loadAttributes-com.aspose.threed.Scene-com.aspose.threed.Stream-}
```
public void loadAttributes(Scene scene, Stream stream)
```


Загрузить атрибуты из указанного потока

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Сцена, к которой будут применены атрибуты |
| stream | [Stream](../../com.aspose.threed/stream) | Поток, содержащий атрибуты |

### loadAttributes(Scene scene, Stream stream, String prefix) {#loadAttributes-com.aspose.threed.Scene-com.aspose.threed.Stream-java.lang.String-}
```
public void loadAttributes(Scene scene, Stream stream, String prefix)
```


Загрузить атрибуты из указанного потока

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Сцена, к которой будут применены атрибуты |
| stream | [Stream](../../com.aspose.threed/stream) | Поток, содержащий атрибуты |
| префикс | java.lang.String | Префикс атрибутов, используемый для избежания конфликтов имён, значение по умолчанию — "rvm:" |

### loadAttributes(Scene scene, String fileName) {#loadAttributes-com.aspose.threed.Scene-java.lang.String-}
```
public void loadAttributes(Scene scene, String fileName)
```


Загрузить атрибуты из указанного имени файла

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Сцена, к которой будут применены атрибуты |
| fileName | java.lang.String | Имя файла, содержащего атрибуты |

### loadAttributes(Scene scene, String fileName, String prefix) {#loadAttributes-com.aspose.threed.Scene-java.lang.String-java.lang.String-}
```
public void loadAttributes(Scene scene, String fileName, String prefix)
```


Загрузить атрибуты из указанного имени файла

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Сцена, к которой будут применены атрибуты |
| fileName | java.lang.String | Имя файла, содержащего атрибуты |
| префикс | java.lang.String | Префикс атрибутов, используемый для избежания конфликтов имён, значение по умолчанию — "rvm:" |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Форматы в строку

**Returns:**
java.lang.String - Строка объекта
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

