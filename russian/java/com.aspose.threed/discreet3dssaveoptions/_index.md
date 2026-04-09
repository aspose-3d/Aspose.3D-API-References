---
title: Discreet3dsSaveOptions
second_title: Справочник API Aspose.3D для Java
description: Параметры сохранения для файла 3DS.
type: docs
weight: 44
url: /ru/java/com.aspose.threed/discreet3dssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Discreet3dsSaveOptions extends SaveOptions
```

Параметры сохранения для файла 3DS.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Discreet3dsSaveOptions()](#Discreet3dsSaveOptions--) | Конструктор [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions) |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDuplicatedNameCounterBase()](#getDuplicatedNameCounterBase--) | Счётчик, используемый при генерации новых имён для дублированных имён, значение по умолчанию — 2. |
| [getDuplicatedNameCounterFormat()](#getDuplicatedNameCounterFormat--) | Формат дублированного счётчика, значение по умолчанию — пустая строка. |
| [getDuplicatedNameSeparator()](#getDuplicatedNameSeparator--) | Разделитель между именем объекта и дублированным счётчиком, значение по умолчанию — "\\_". |
| [getEncoding()](#getEncoding--) | Получает кодировку по умолчанию для текстовых файлов. |
| [getExportCamera()](#getExportCamera--) | Получает, экспортировать ли все камеры в сцене. |
| [getExportLight()](#getExportLight--) | Получает, экспортировать ли все источники света в сцене. |
| [getExportTextures()](#getExportTextures--) | Пытается скопировать текстуры, используемые в сцене, в выходной каталог. |
| [getFileFormat()](#getFileFormat--) | Получает формат файла, указанный в текущей опции сохранения/загрузки. |
| [getFileName()](#getFileName--) | Имя файла экспортируемой/импортируемой сцены. |
| [getFileSystem()](#getFileSystem--) | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Получает класс фабрики для FileSystem. |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | Получает инверсию системы координат контрольных точек/нормалей при импорте/экспорте. |
| [getGammaCorrectedColor()](#getGammaCorrectedColor--) | Файл 3ds может содержать оригинальный цвет и цвет с гамма‑коррекцией для одного и того же атрибута. Установка этого параметра в true заставит использовать цвет с гамма‑коррекцией, если это возможно; в противном случае Aspose.3D попытается использовать оригинальный цвет. |
| [getHighPreciseColor()](#getHighPreciseColor--) | Если значение true, сгенерированный файл 3ds будет использовать высокоточный цвет, то есть каждый канал красного/зелёного/синего будет представлен 32‑битным числом с плавающей точкой. |
| [getLookupPaths()](#getLookupPaths--) | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [getMasterScale()](#getMasterScale--) | Получает основной масштаб, используемый при экспорте. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDuplicatedNameCounterBase(int value)](#setDuplicatedNameCounterBase-int-) | Счётчик, используемый при генерации новых имён для дублированных имён, значение по умолчанию — 2. |
| [setDuplicatedNameCounterFormat(String value)](#setDuplicatedNameCounterFormat-java.lang.String-) | Формат дублированного счётчика, значение по умолчанию — пустая строка. |
| [setDuplicatedNameSeparator(String value)](#setDuplicatedNameSeparator-java.lang.String-) | Разделитель между именем объекта и дублированным счётчиком, значение по умолчанию — "\\_". |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Устанавливает кодировку по умолчанию для текстовых файлов. |
| [setExportCamera(boolean value)](#setExportCamera-boolean-) | Устанавливает, экспортировать ли все камеры в сцене. |
| [setExportLight(boolean value)](#setExportLight-boolean-) | Устанавливает, экспортировать ли все источники света в сцене. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Пытается скопировать текстуры, используемые в сцене, в выходной каталог. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Имя файла экспортируемой/импортируемой сцены. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Устанавливает класс фабрики для FileSystem. |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | Устанавливает инверсию системы координат контрольных точек/нормалей при импорте/экспорте. |
| [setGammaCorrectedColor(boolean value)](#setGammaCorrectedColor-boolean-) | Файл 3ds может содержать оригинальный цвет и цвет с гамма‑коррекцией для одного и того же атрибута. Установка этого параметра в true заставит использовать цвет с гамма‑коррекцией, если это возможно; в противном случае Aspose.3D попытается использовать оригинальный цвет. |
| [setHighPreciseColor(boolean value)](#setHighPreciseColor-boolean-) | Если значение true, сгенерированный файл 3ds будет использовать высокоточный цвет, то есть каждый канал красного/зелёного/синего будет представлен 32‑битным числом с плавающей точкой. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [setMasterScale(double value)](#setMasterScale-double-) | Устанавливает основной масштаб, используемый при экспорте. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Discreet3dsSaveOptions() {#Discreet3dsSaveOptions--}
```
public Discreet3dsSaveOptions()
```


Конструктор [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions)

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


Счётчик, используемый при генерации новых имён для дублированных имён, значение по умолчанию — 2.

**Returns:**
int — Счётчик, используемый при генерации нового имени для дублированных имён, значение по умолчанию — 2.
### getDuplicatedNameCounterFormat() {#getDuplicatedNameCounterFormat--}
```
public String getDuplicatedNameCounterFormat()
```


Формат дублированного счётчика, значение по умолчанию — пустая строка.

**Returns:**
java.lang.String — Формат дублирующего счётчика, значение по умолчанию — пустая строка.
### getDuplicatedNameSeparator() {#getDuplicatedNameSeparator--}
```
public String getDuplicatedNameSeparator()
```


Разделитель между именем объекта и дублирующим счётчиком, значение по умолчанию — "\_". Когда сцена содержит объекты с одинаковым именем, экспортер Aspose.3D 3DS создаст другое имя для объекта. Например, есть два узла с именем "Box": первый узел будет иметь имя "Box", а второй получит новое имя "Box\_2" при использовании конфигурации по умолчанию.

**Returns:**
java.lang.String — Разделитель между именем объекта и дублирующим счётчиком, значение по умолчанию — "\_". Когда сцена содержит объекты с одинаковым именем, экспортер Aspose.3D 3DS создаст другое имя для объекта. Например, есть два узла с именем "Box": первый узел будет иметь имя "Box", а второй получит новое имя "Box\_2" при использовании конфигурации по умолчанию.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Получает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать.

**Returns:**
java.nio.charset.Charset - кодировка по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать.
### getExportCamera() {#getExportCamera--}
```
public boolean getExportCamera()
```


Получает, экспортировать ли все камеры в сцене.

**Returns:**
boolean — экспортировать ли все камеры в сцене.
### getExportLight() {#getExportLight--}
```
public boolean getExportLight()
```


Получает, экспортировать ли все источники света в сцене.

**Returns:**
boolean — экспортировать ли все источники света в сцене.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Пытается скопировать текстуры, используемые в сцене, в выходной каталог.

**Returns:**
boolean — Пытаться копировать текстуры, используемые в сцене, в выходной каталог.
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


Получает инверсию системы координат контрольных точек/нормалей при импорте/экспорте.

**Returns:**
boolean - инвертировать систему координат контрольных точек/нормалей при импорте/экспорте.
### getGammaCorrectedColor() {#getGammaCorrectedColor--}
```
public boolean getGammaCorrectedColor()
```


Файл 3ds может содержать оригинальный цвет и цвет с гамма‑коррекцией для одного и того же атрибута. Установка этого параметра в true заставит использовать цвет с гамма‑коррекцией, если это возможно; в противном случае Aspose.3D попытается использовать оригинальный цвет.

**Returns:**
boolean — Файл 3ds может содержать оригинальный цвет и цвет с гамма‑коррекцией для одного и того же атрибута; установка значения true заставит использовать цвет с гамма‑коррекцией, если это возможно, иначе Aspose.3D попытается использовать оригинальный цвет.
### getHighPreciseColor() {#getHighPreciseColor--}
```
public boolean getHighPreciseColor()
```


Если значение true, сгенерированный файл 3ds будет использовать высокоточный цвет, то есть каждый канал красного/зелёного/синего будет представлен 32‑битным float. В противном случае файл будет использовать 24‑битный цвет, каждый канал — 8‑битный байт. Значение по умолчанию — false, поскольку не все приложения поддерживают высокоточный цвет.

**Returns:**
boolean — Если значение true, сгенерированный файл 3ds будет использовать высокоточный цвет, то есть каждый канал красного/зелёного/синего будет представлен 32‑битным float. В противном случае файл будет использовать 24‑битный цвет, каждый канал — 8‑битный байт. Значение по умолчанию — false, поскольку не все приложения поддерживают высокоточный цвет.
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
### getMasterScale() {#getMasterScale--}
```
public double getMasterScale()
```


Получает основной масштаб, используемый при экспорте.

**Returns:**
double — основной масштаб, используемый при экспорте.
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


Счётчик, используемый при генерации новых имён для дублированных имён, значение по умолчанию — 2.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setDuplicatedNameCounterFormat(String value) {#setDuplicatedNameCounterFormat-java.lang.String-}
```
public void setDuplicatedNameCounterFormat(String value)
```


Формат дублированного счётчика, значение по умолчанию — пустая строка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setDuplicatedNameSeparator(String value) {#setDuplicatedNameSeparator-java.lang.String-}
```
public void setDuplicatedNameSeparator(String value)
```


Разделитель между именем объекта и дублирующим счётчиком, значение по умолчанию — "\_". Когда сцена содержит объекты с одинаковым именем, экспортер Aspose.3D 3DS создаст другое имя для объекта. Например, есть два узла с именем "Box": первый узел будет иметь имя "Box", а второй получит новое имя "Box\_2" при использовании конфигурации по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Устанавливает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.nio.charset.Charset | Новое значение |

### setExportCamera(boolean value) {#setExportCamera-boolean-}
```
public void setExportCamera(boolean value)
```


Устанавливает, экспортировать ли все камеры в сцене.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setExportLight(boolean value) {#setExportLight-boolean-}
```
public void setExportLight(boolean value)
```


Устанавливает, экспортировать ли все источники света в сцене.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Пытается скопировать текстуры, используемые в сцене, в выходной каталог.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

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


Устанавливает инверсию системы координат контрольных точек/нормалей при импорте/экспорте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setGammaCorrectedColor(boolean value) {#setGammaCorrectedColor-boolean-}
```
public void setGammaCorrectedColor(boolean value)
```


Файл 3ds может содержать оригинальный цвет и цвет с гамма‑коррекцией для одного и того же атрибута. Установка этого параметра в true заставит использовать цвет с гамма‑коррекцией, если это возможно; в противном случае Aspose.3D попытается использовать оригинальный цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setHighPreciseColor(boolean value) {#setHighPreciseColor-boolean-}
```
public void setHighPreciseColor(boolean value)
```


Если значение true, сгенерированный файл 3ds будет использовать высокоточный цвет, то есть каждый канал красного/зелёного/синего будет представлен 32‑битным float. В противном случае файл будет использовать 24‑битный цвет, каждый канал — 8‑битный байт. Значение по умолчанию — false, поскольку не все приложения поддерживают высокоточный цвет.

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

### setMasterScale(double value) {#setMasterScale-double-}
```
public void setMasterScale(double value)
```


Устанавливает основной масштаб, используемый при экспорте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

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

