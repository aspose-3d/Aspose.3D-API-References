---
title: PdfSaveOptions
second_title: Справочник API Aspose.3D для Java
description: Параметры сохранения при экспорте PDF.
type: docs
weight: 125
url: /ru/java/com.aspose.threed/pdfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Параметры сохранения при экспорте PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Конструктор [PdfSaveOptions](../../com.aspose.threed/pdfsaveoptions) |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAuxiliaryColor()](#getAuxiliaryColor--) | Получает вспомогательный цвет, используемый при рендеринге 3D‑контента. |
| [getBackgroundColor()](#getBackgroundColor--) | Цвет фона 3D‑просмотра в PDF‑файле. |
| [getClass()](#getClass--) |  |
| [getEmbedTextures()](#getEmbedTextures--) | Встраивает внешние текстуры в PDF‑файл, значение по умолчанию — false. |
| [getEncoding()](#getEncoding--) | Получает кодировку по умолчанию для текстовых файлов. |
| [getExportTextures()](#getExportTextures--) | Пытается скопировать текстуры, используемые в сцене, в выходной каталог. |
| [getFaceColor()](#getFaceColor--) | Получает цвет поверхности, используемый при рендеринге 3D‑контента. |
| [getFileFormat()](#getFileFormat--) | Получает формат файла, указанный в текущей опции сохранения/загрузки. |
| [getFileName()](#getFileName--) | Имя файла экспортируемой/импортируемой сцены. |
| [getFileSystem()](#getFileSystem--) | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Получает класс фабрики для FileSystem. |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | Получает флаг инвертирования системы координат сцены при экспорте. |
| [getLightingScheme()](#getLightingScheme--) | LightingScheme указывает освещение, применяемое к 3D‑артворку. |
| [getLookupPaths()](#getLookupPaths--) | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [getRenderMode()](#getRenderMode--) | Режим рендеринга указывает стиль, в котором рендерится 3D‑артворк. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAuxiliaryColor(Vector3 value)](#setAuxiliaryColor-com.aspose.threed.Vector3-) | Устанавливает вспомогательный цвет, используемый при рендеринге 3D‑контента. |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | Цвет фона 3D‑просмотра в PDF‑файле. |
| [setEmbedTextures(boolean value)](#setEmbedTextures-boolean-) | Встраивает внешние текстуры в PDF‑файл, значение по умолчанию — false. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Устанавливает кодировку по умолчанию для текстовых файлов. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Пытается скопировать текстуры, используемые в сцене, в выходной каталог. |
| [setFaceColor(Vector3 value)](#setFaceColor-com.aspose.threed.Vector3-) | Устанавливает цвет поверхности, используемый при рендеринге 3D‑контента. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Имя файла экспортируемой/импортируемой сцены. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Устанавливает класс фабрики для FileSystem. |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | Устанавливает флаг инвертирования системы координат сцены при экспорте. |
| [setLightingScheme(PdfLightingScheme value)](#setLightingScheme-com.aspose.threed.PdfLightingScheme-) | LightingScheme указывает освещение, применяемое к 3D‑артворку. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [setRenderMode(PdfRenderMode value)](#setRenderMode-com.aspose.threed.PdfRenderMode-) | Режим рендеринга указывает стиль, в котором рендерится 3D‑артворк. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Конструктор [PdfSaveOptions](../../com.aspose.threed/pdfsaveoptions)

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
### getAuxiliaryColor() {#getAuxiliaryColor--}
```
public Vector3 getAuxiliaryColor()
```


Получает вспомогательный цвет, используемый при рендеринге 3D‑контента. Интерпретация этого цвета зависит от [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the auxiliary color to be used when rendering the 3D content. The interpretation of this color depends on the [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode)
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


Цвет фона 3D‑просмотра в PDF‑файле.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Background color of the 3D view in PDF file.
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


Встраивает внешние текстуры в PDF‑файл, значение по умолчанию — false.

**Returns:**
boolean — Встраивает внешние текстуры в PDF‑файл, значение по умолчанию — false.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Получает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать.

**Returns:**
java.nio.charset.Charset - кодировка по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Пытается скопировать текстуры, используемые в сцене, в выходной каталог.

**Returns:**
boolean — Пытаться копировать текстуры, используемые в сцене, в выходной каталог.
### getFaceColor() {#getFaceColor--}
```
public Vector3 getFaceColor()
```


Получает цвет поверхности, используемый при рендеринге 3D‑контента. Это актуально только когда у [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode) значение Illustration.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the face color to be used when rendering the 3D content. This is only relevant only when the [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode) has a value of Illustration.
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Получает формат файла, указанный в текущей опции сохранения/загрузки.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ.

**Returns:**
java.lang.String - Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

И вы также можете использовать свою собственную реализацию.

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


Получает класс фабрики для FileSystem. Фабрика по умолчанию создаст com.aspose.threed.LocalFileSystem, который не подходит для серверной среды.

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


Получает флаг инвертирования системы координат сцены при экспорте.

**Returns:**
boolean — Инвертировать систему координат сцены при экспорте.
### getLightingScheme() {#getLightingScheme--}
```
public PdfLightingScheme getLightingScheme()
```


LightingScheme указывает освещение, применяемое к 3D‑артворку.

**Returns:**
[PdfLightingScheme](../../com.aspose.threed/pdflightingscheme) - LightingScheme specifies the lighting to apply to 3D artwork.
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки.

**Returns:**
java.util.ArrayList<java.lang.String> - Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D искать внешние файлы для загрузки. **Example:** Следующий код показывает, как вручную указать пути поиска текстур, чтобы импортёр мог их найти

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
```
### getRenderMode() {#getRenderMode--}
```
public PdfRenderMode getRenderMode()
```


Режим рендеринга указывает стиль, в котором рендерится 3D‑артворк.

**Returns:**
[PdfRenderMode](../../com.aspose.threed/pdfrendermode) - Render mode specifies the style in which the 3D artwork is rendered.
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




### setAuxiliaryColor(Vector3 value) {#setAuxiliaryColor-com.aspose.threed.Vector3-}
```
public void setAuxiliaryColor(Vector3 value)
```


Устанавливает вспомогательный цвет, используемый при рендеринге 3D‑контента. Интерпретация этого цвета зависит от [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


Цвет фона 3D‑просмотра в PDF‑файле.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setEmbedTextures(boolean value) {#setEmbedTextures-boolean-}
```
public void setEmbedTextures(boolean value)
```


Встраивает внешние текстуры в PDF‑файл, значение по умолчанию — false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Устанавливает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.nio.charset.Charset | Новое значение |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Пытается скопировать текстуры, используемые в сцене, в выходной каталог.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setFaceColor(Vector3 value) {#setFaceColor-com.aspose.threed.Vector3-}
```
public void setFaceColor(Vector3 value)
```


Устанавливает цвет поверхности, используемый при рендеринге 3D‑контента. Это актуально только когда у [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode) значение Illustration.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Новое значение **Example:** Файловая система по умолчанию — LocalFileSystem, она не безопасна в среде, подобной серверной, но вы можете переопределить доступ к файловой системе, указав другую реализацию. Aspose.3D предоставляет различные реализации FileSystem, такие как: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

И вы также можете использовать свою собственную реализацию.

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


Устанавливает класс фабрики для FileSystem. Фабрика по умолчанию создаст com.aspose.threed.LocalFileSystem, который не подходит для серверной среды.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Новое значение **Example:** Файловая система по умолчанию в SaveOptions/LoadOptions — файловая система, основанная на каталогах. Вы можете переопределить реализацию по умолчанию, указав её через IOConfig.FileSystemFactory: |

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


Устанавливает флаг инвертирования системы координат сцены при экспорте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setLightingScheme(PdfLightingScheme value) {#setLightingScheme-com.aspose.threed.PdfLightingScheme-}
```
public void setLightingScheme(PdfLightingScheme value)
```


LightingScheme указывает освещение, применяемое к 3D‑артворку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfLightingScheme](../../com.aspose.threed/pdflightingscheme) | Новое значение |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.util.ArrayList<java.lang.String> | Новое значение **Example:** Следующий код показывает, как вручную указать пути поиска текстур, чтобы импортёр мог их найти |

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
``` |

### setRenderMode(PdfRenderMode value) {#setRenderMode-com.aspose.threed.PdfRenderMode-}
```
public void setRenderMode(PdfRenderMode value)
```


Режим рендеринга указывает стиль, в котором рендерится 3D‑артворк.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfRenderMode](../../com.aspose.threed/pdfrendermode) | Новое значение |

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

