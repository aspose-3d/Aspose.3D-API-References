---
title: GltfSaveOptions
second_title: Справочник API Aspose.3D для Java
description: Параметры сохранения для формата glTF.
type: docs
weight: 74
url: /ru/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

Параметры сохранения для формата glTF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | Конструктор [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | Конструктор [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | Применить [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) к сетке. |
| [getBufferFile()](#getBufferFile--) | Имя внешнего буферного файла, используемого для хранения двоичных данных. |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | Получает, включено ли сжатие draco |
| [getEmbedAssets()](#getEmbedAssets--) | Встраивает все внешние ресурсы в виде base64 в один файл в режиме ASCII, значение по умолчанию — false. |
| [getEncoding()](#getEncoding--) | Получает кодировку по умолчанию для текстовых файлов. |
| [getExportTextures()](#getExportTextures--) | Пытается скопировать текстуры, используемые в сцене, в выходной каталог. |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | Использовать внешний кодировщик draco для ускорения скорости сжатия draco. |
| [getFallbackNormal()](#getFallbackNormal--) | Когда экспортёр GLTF2 обнаруживает недопустимую нормаль, вместо её исходного значения будет использовано это значение, чтобы обойти проверку. |
| [getFileFormat()](#getFileFormat--) | Получает формат файла, указанный в текущей опции сохранения/загрузки. |
| [getFileName()](#getFileName--) | Имя файла экспортируемой/импортируемой сцены. |
| [getFileSystem()](#getFileSystem--) | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Получает класс фабрики для FileSystem. |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | Отразить компонент текстурной координаты v(t), значение по умолчанию — true. |
| [getImageFormat()](#getImageFormat--) | Стандартный glTF поддерживает только PNG/JPG в качестве формата текстур, эта опция определит, как Aspose.3D будет конвертировать нестандартные изображения в поддерживаемый формат во время экспорта. |
| [getLookupPaths()](#getLookupPaths--) | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [getMaterialConverter()](#getMaterialConverter--) | Пользовательский конвертер для преобразования материала геометрии в PBR‑материал. Если он не задан, экспортер glTF 2.0 автоматически преобразует стандартный материал в PBR‑материал. |
| [getPrettyPrint()](#getPrettyPrint--) | Содержимое JSON файла GLTF отступает для удобства чтения человеком, значение по умолчанию — false. |
| [getSaveExtras()](#getSaveExtras--) | Сохранить динамические свойства объектов сцены в поля 'extra' в сгенерированном файле glTF. |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | Сериализовать материалы с использованием общих расширений KHR, значение по умолчанию — false. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | Применить [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) к сетке. |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | Имя внешнего буферного файла, используемого для хранения двоичных данных. |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | Устанавливает, включать ли сжатие Draco. |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | Встраивает все внешние ресурсы в виде base64 в один файл в режиме ASCII, значение по умолчанию — false. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Устанавливает кодировку по умолчанию для текстовых файлов. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Пытается скопировать текстуры, используемые в сцене, в выходной каталог. |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | Использовать внешний кодировщик draco для ускорения скорости сжатия draco. |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | Когда экспортёр GLTF2 обнаруживает недопустимую нормаль, вместо её исходного значения будет использовано это значение, чтобы обойти проверку. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Имя файла экспортируемой/импортируемой сцены. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Устанавливает класс фабрики для FileSystem. |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | Отразить компонент текстурной координаты v(t), значение по умолчанию — true. |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | Стандартный glTF поддерживает только PNG/JPG в качестве формата текстур, эта опция определит, как Aspose.3D будет конвертировать нестандартные изображения в поддерживаемый формат во время экспорта. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | Пользовательский конвертер для преобразования материала геометрии в PBR‑материал. Если он не задан, экспортер glTF 2.0 автоматически преобразует стандартный материал в PBR‑материал. |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | Содержимое JSON файла GLTF отступает для удобства чтения человеком, значение по умолчанию — false. |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | Сохранить динамические свойства объектов сцены в поля 'extra' в сгенерированном файле glTF. |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | Сериализовать материалы с использованием общих расширений KHR, значение по умолчанию — false. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


Конструктор [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


Конструктор [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

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
### getApplyUnitScale() {#getApplyUnitScale--}
```
public boolean getApplyUnitScale()
```


Применить [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) к сетке. Значение по умолчанию — false.

**Returns:**
boolean — Применить [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) к сетке. Значение по умолчанию — false.
### getBufferFile() {#getBufferFile--}
```
public String getBufferFile()
```


Имя внешнего буферного файла, используемого для хранения бинарных данных. Если файл не указан, Aspose.3D сгенерирует имя автоматически. Игнорируется при экспорте glTF в бинарном режиме.

**Returns:**
java.lang.String — Имя внешнего буферного файла, используемого для хранения бинарных данных. Если файл не указан, Aspose.3D сгенерирует имя автоматически. Игнорируется при экспорте glTF в бинарном режиме.
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


Получает, включено ли сжатие draco

**Returns:**
boolean — включать ли сжатие Draco.
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


Встраивает все внешние ресурсы в виде base64 в один файл в режиме ASCII, значение по умолчанию — false.

**Returns:**
boolean — Встраивать все внешние ресурсы в виде base64 в один файл в ASCII‑режиме, значение по умолчанию — false.
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
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


Использовать внешний кодировщик draco для ускорения скорости сжатия draco.

**Returns:**
java.lang.String — Использовать внешний кодировщик Draco для ускорения скорости сжатия Draco. **Remarks:** Aspose.3D создаст новый подпроцесс для кодирования сетки в формат Draco, используйте его на свой страх и риск.
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


Когда экспортер GLTF2 обнаруживает недопустимую нормаль, вместо её оригинального значения будет использовано это значение, чтобы обойти проверку. Значение по умолчанию — (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
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
### getFlipTexCoordV() {#getFlipTexCoordV--}
```
public boolean getFlipTexCoordV()
```


Отразить компонент текстурной координаты v(t), значение по умолчанию — true.

**Returns:**
boolean — Инвертировать компонент v(t) текстурных координат, значение по умолчанию — true.
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


Стандартный glTF поддерживает только PNG/JPG в качестве формата текстур, эта опция определит, как Aspose.3D будет конвертировать нестандартные изображения в поддерживаемый формат во время экспорта. Значение по умолчанию — [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\\#PNG)

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
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
### getMaterialConverter() {#getMaterialConverter--}
```
public MaterialConverter getMaterialConverter()
```


Пользовательский конвертер для преобразования материала геометрии в PBR‑материал. Если он не задан, экспортер glTF 2.0 автоматически преобразует стандартный материал в PBR‑материал. Значение по умолчанию — null. Это свойство используется при экспорте сцены в файл glTF 2.0.

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


Содержимое JSON файла GLTF отступает для удобства чтения человеком, значение по умолчанию — false.

**Returns:**
boolean — Содержимое JSON файла GLTF отступает для удобства чтения человеком, значение по умолчанию — false.
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


Сохранить динамические свойства объектов сцены в поля 'extra' в сгенерированном файле glTF. Это полезно для предоставления данных, специфичных для приложения. Значение по умолчанию — false.

**Returns:**
boolean — Сохранить динамические свойства объектов сцены в поля 'extra' в сгенерированном файле glTF. Это полезно для предоставления данных, специфичных для приложения. Значение по умолчанию — false.
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


Сериализовать материалы с использованием общих расширений KHR, значение по умолчанию — false. Установка этого параметра в false заставит Aspose.3D экспортировать набор вершинных/фрагментных шейдеров, если [getExportShaders](../../com.aspose.threed/gltfsaveoptions\\#getExportShaders).

**Returns:**
boolean — Сериализовать материалы с использованием общих расширений KHR, значение по умолчанию — false. Установка этого параметра в false заставит Aspose.3D экспортировать набор вершинных/фрагментных шейдеров, если [getExportShaders](../../com.aspose.threed/gltfsaveoptions\\#getExportShaders) **Remarks:** Это свойство работает только с glTF 1.0.
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


Применить [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) к сетке. Значение по умолчанию — false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


Имя внешнего буферного файла, используемого для хранения бинарных данных. Если файл не указан, Aspose.3D сгенерирует имя автоматически. Игнорируется при экспорте glTF в бинарном режиме.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


Устанавливает, включать ли сжатие Draco.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


Встраивает все внешние ресурсы в виде base64 в один файл в режиме ASCII, значение по умолчанию — false.

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

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


Использовать внешний кодировщик draco для ускорения скорости сжатия draco.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение **Remarks:** Aspose.3D создаст новый подпроцесс для кодирования сетки в формат Draco, используйте его на свой страх и риск. |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


Когда экспортер GLTF2 обнаруживает недопустимую нормаль, вместо её оригинального значения будет использовано это значение, чтобы обойти проверку. Значение по умолчанию — (0, 1, 0).

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

### setFlipTexCoordV(boolean value) {#setFlipTexCoordV-boolean-}
```
public void setFlipTexCoordV(boolean value)
```


Отразить компонент текстурной координаты v(t), значение по умолчанию — true.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


Стандартный glTF поддерживает только PNG/JPG в качестве формата текстур, эта опция определит, как Aspose.3D будет конвертировать нестандартные изображения в поддерживаемый формат во время экспорта. Значение по умолчанию — [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\\#PNG)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | Новое значение |

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

### setMaterialConverter(MaterialConverter value) {#setMaterialConverter-com.aspose.threed.MaterialConverter-}
```
public void setMaterialConverter(MaterialConverter value)
```


Пользовательский конвертер для преобразования материала геометрии в PBR‑материал. Если он не задан, экспортер glTF 2.0 автоматически преобразует стандартный материал в PBR‑материал. Значение по умолчанию — null. Это свойство используется при экспорте сцены в файл glTF 2.0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | Новое значение |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


Содержимое JSON файла GLTF отступает для удобства чтения человеком, значение по умолчанию — false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


Сохранить динамические свойства объектов сцены в поля 'extra' в сгенерированном файле glTF. Это полезно для предоставления данных, специфичных для приложения. Значение по умолчанию — false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


Сериализовать материалы с использованием общих расширений KHR, значение по умолчанию — false. Установка этого параметра в false заставит Aspose.3D экспортировать набор вершинных/фрагментных шейдеров, если [getExportShaders](../../com.aspose.threed/gltfsaveoptions\\#getExportShaders).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение **Remarks:** Это свойство работает только с glTF 1.0. |

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

