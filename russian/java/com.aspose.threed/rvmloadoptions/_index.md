---
title: RvmLoadOptions
second_title: Справочник API Aspose.3D для Java
description: Параметры загрузки для файла RVM системы AVEVA Plant Design Management Systems.
type: docs
weight: 157
url: /ru/java/com.aspose.threed/rvmloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class RvmLoadOptions extends LoadOptions
```

Параметры загрузки для файла RVM системы AVEVA Plant Design Management System. **Example:** Следующий код показывает, как настроить параметры тесселяции примитивных геометрий, импортированных из файла RVM, с использованием RvmLoadOptions.

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
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RvmLoadOptions(FileContentType contentType)](#RvmLoadOptions-com.aspose.threed.FileContentType-) | Создайте экземпляр [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) |
| [RvmLoadOptions()](#RvmLoadOptions--) | Создайте экземпляр [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributePrefix()](#getAttributePrefix--) | Получает префикс атрибутов, определённых во внешних файлах атрибутов. Префикс используется для избежания конфликтов имён, значение по умолчанию — "rvm:" |
| [getCenterScene()](#getCenterScene--) | Центрировать сцену после её загрузки. |
| [getClass()](#getClass--) |  |
| [getCylinderRadialSegments()](#getCylinderRadialSegments--) | Получает количество радиальных сегментов цилиндра, значение по умолчанию — 16 |
| [getDishLatitudeSegments()](#getDishLatitudeSegments--) | Получает количество сегментов широты тарелки, значение по умолчанию — 8 |
| [getDishLongitudeSegments()](#getDishLongitudeSegments--) | Получает количество сегментов долготы тарелки, значение по умолчанию — 12 |
| [getEncoding()](#getEncoding--) | Получает кодировку по умолчанию для текстовых файлов. |
| [getFileFormat()](#getFileFormat--) | Получает формат файла, указанный в текущей опции сохранения/загрузки. |
| [getFileName()](#getFileName--) | Имя файла экспортируемой/импортируемой сцены. |
| [getFileSystem()](#getFileSystem--) | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Получает класс фабрики для FileSystem. |
| [getGenerateMaterials()](#getGenerateMaterials--) | Генерировать материалы со случайными цветами для каждого объекта в сцене, если таблица цветов не экспортирована в файле RVM. |
| [getLookupAttributes()](#getLookupAttributes--) | Получает, следует ли загружать атрибуты из внешнего файла списка атрибутов (.att/.attrib/.txt), значение по умолчанию — true. |
| [getLookupPaths()](#getLookupPaths--) | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [getRectangularTorusSegments()](#getRectangularTorusSegments--) | Получает количество радиальных сегментов прямоугольного тора, значение по умолчанию — 20 |
| [getTorusTubularSegments()](#getTorusTubularSegments--) | Получает количество трубчатых сегментов тора, значение по умолчанию — 20 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | Устанавливает префикс атрибутов, определённых во внешних файлах атрибутов. Префикс используется для избежания конфликтов имён, значение по умолчанию — "rvm:" |
| [setCenterScene(boolean value)](#setCenterScene-boolean-) | Центрировать сцену после её загрузки. |
| [setCylinderRadialSegments(int value)](#setCylinderRadialSegments-int-) | Устанавливает количество радиальных сегментов цилиндра, значение по умолчанию — 16 |
| [setDishLatitudeSegments(int value)](#setDishLatitudeSegments-int-) | Устанавливает количество сегментов широты тарелки, значение по умолчанию — 8 |
| [setDishLongitudeSegments(int value)](#setDishLongitudeSegments-int-) | Устанавливает количество сегментов долготы тарелки, значение по умолчанию — 12 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Устанавливает кодировку по умолчанию для текстовых файлов. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Имя файла экспортируемой/импортируемой сцены. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Устанавливает класс фабрики для FileSystem. |
| [setGenerateMaterials(boolean value)](#setGenerateMaterials-boolean-) | Генерировать материалы со случайными цветами для каждого объекта в сцене, если таблица цветов не экспортирована в файле RVM. |
| [setLookupAttributes(boolean value)](#setLookupAttributes-boolean-) | Устанавливает, следует ли загружать атрибуты из внешнего файла списка атрибутов (.att/.attrib/.txt), значение по умолчанию — true. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [setRectangularTorusSegments(int value)](#setRectangularTorusSegments-int-) | Устанавливает количество радиальных сегментов прямоугольного тора, значение по умолчанию — 20 |
| [setTorusTubularSegments(int value)](#setTorusTubularSegments-int-) | Устанавливает количество трубчатых сегментов тора, значение по умолчанию — 20 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmLoadOptions(FileContentType contentType) {#RvmLoadOptions-com.aspose.threed.FileContentType-}
```
public RvmLoadOptions(FileContentType contentType)
```


Создайте экземпляр [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### RvmLoadOptions() {#RvmLoadOptions--}
```
public RvmLoadOptions()
```


Создайте экземпляр [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions)

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
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


Получает префикс атрибутов, определённых во внешних файлах атрибутов. Префикс используется для избежания конфликтов имён, значение по умолчанию — "rvm:"

**Returns:**
java.lang.String - префикс атрибутов, определённых во внешних файлах атрибутов, Префикс используется для избежания конфликтов имён, значение по умолчанию "rvm:"
### getCenterScene() {#getCenterScene--}
```
public boolean getCenterScene()
```


Центрировать сцену после её загрузки.

**Returns:**
boolean - Центрировать сцену после её загрузки.
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


Получает количество радиальных сегментов цилиндра, значение по умолчанию — 16

**Returns:**
int - количество радиальных сегментов цилиндра, значение по умолчанию 16
### getDishLatitudeSegments() {#getDishLatitudeSegments--}
```
public int getDishLatitudeSegments()
```


Получает количество сегментов широты тарелки, значение по умолчанию — 8

**Returns:**
int - количество сегментов широты тарелки, значение по умолчанию 8
### getDishLongitudeSegments() {#getDishLongitudeSegments--}
```
public int getDishLongitudeSegments()
```


Получает количество сегментов долготы тарелки, значение по умолчанию — 12

**Returns:**
int - количество сегментов долготы тарелки, значение по умолчанию 12
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Получает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать.

**Returns:**
java.nio.charset.Charset - кодировка по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать.
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
### getGenerateMaterials() {#getGenerateMaterials--}
```
public boolean getGenerateMaterials()
```


Генерировать материалы со случайными цветами для каждого объекта в сцене, если таблица цветов не экспортирована в файле RVM. Значение по умолчанию true

**Returns:**
boolean - Генерировать материалы со случайными цветами для каждого объекта в сцене, если таблица цветов не экспортирована в файле RVM. Значение по умолчанию true
### getLookupAttributes() {#getLookupAttributes--}
```
public boolean getLookupAttributes()
```


Получает, следует ли загружать атрибуты из внешнего файла списка атрибутов (.att/.attrib/.txt), значение по умолчанию — true.

**Returns:**
boolean - загружать атрибуты из внешнего файла списка атрибутов (.att/.attrib/.txt), значение по умолчанию true.
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
### getRectangularTorusSegments() {#getRectangularTorusSegments--}
```
public int getRectangularTorusSegments()
```


Получает количество радиальных сегментов прямоугольного тора, значение по умолчанию — 20

**Returns:**
int - количество радиальных сегментов прямоугольного тора, значение по умолчанию 20
### getTorusTubularSegments() {#getTorusTubularSegments--}
```
public int getTorusTubularSegments()
```


Получает количество трубчатых сегментов тора, значение по умолчанию — 20

**Returns:**
int - количество трубчатых сегментов тора, значение по умолчанию 20
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


Устанавливает префикс атрибутов, определённых во внешних файлах атрибутов. Префикс используется для избежания конфликтов имён, значение по умолчанию — "rvm:"

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setCenterScene(boolean value) {#setCenterScene-boolean-}
```
public void setCenterScene(boolean value)
```


Центрировать сцену после её загрузки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setCylinderRadialSegments(int value) {#setCylinderRadialSegments-int-}
```
public void setCylinderRadialSegments(int value)
```


Устанавливает количество радиальных сегментов цилиндра, значение по умолчанию — 16

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setDishLatitudeSegments(int value) {#setDishLatitudeSegments-int-}
```
public void setDishLatitudeSegments(int value)
```


Устанавливает количество сегментов широты тарелки, значение по умолчанию — 8

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setDishLongitudeSegments(int value) {#setDishLongitudeSegments-int-}
```
public void setDishLongitudeSegments(int value)
```


Устанавливает количество сегментов долготы тарелки, значение по умолчанию — 12

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Устанавливает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.nio.charset.Charset | Новое значение |

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

### setGenerateMaterials(boolean value) {#setGenerateMaterials-boolean-}
```
public void setGenerateMaterials(boolean value)
```


Генерировать материалы со случайными цветами для каждого объекта в сцене, если таблица цветов не экспортирована в файле RVM. Значение по умолчанию true

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setLookupAttributes(boolean value) {#setLookupAttributes-boolean-}
```
public void setLookupAttributes(boolean value)
```


Устанавливает, следует ли загружать атрибуты из внешнего файла списка атрибутов (.att/.attrib/.txt), значение по умолчанию — true.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

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

### setRectangularTorusSegments(int value) {#setRectangularTorusSegments-int-}
```
public void setRectangularTorusSegments(int value)
```


Устанавливает количество радиальных сегментов прямоугольного тора, значение по умолчанию — 20

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setTorusTubularSegments(int value) {#setTorusTubularSegments-int-}
```
public void setTorusTubularSegments(int value)
```


Устанавливает количество трубчатых сегментов тора, значение по умолчанию — 20

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

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

