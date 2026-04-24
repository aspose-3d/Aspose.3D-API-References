---
title: Сцена
second_title: Справочник API Aspose.3D для Java
description: 
type: docs
weight: 161
url: /ru/java/com.aspose.threed/scene/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Scene extends SceneObject
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Scene(Entity entity)](#Scene-com.aspose.threed.Entity-) | Инициализирует новый экземпляр класса [Scene](../../com.aspose.threed/scene) с сущностью, присоединённой к новому узлу. |
| [Scene(Scene parentScene, String name)](#Scene-com.aspose.threed.Scene-java.lang.String-) | Инициализирует новый экземпляр класса [Scene](../../com.aspose.threed/scene) как подсцену. |
| [Scene()](#Scene--) | Инициализирует новый экземпляр класса [Scene](../../com.aspose.threed/scene). |
## Поля

| Поле | Описание |
| --- | --- |
| [VERSION](#VERSION) | Получает текущую версию релиза |
## Методы

| Метод | Описание |
| --- | --- |
| [clear()](#clear--) | Очищает содержимое сцены и восстанавливает настройки по умолчанию. |
| [createAnimationClip(String name)](#createAnimationClip-java.lang.String-) | Краткая функция для создания и регистрации [AnimationClip](../../com.aspose.threed/animationclip). Первый [AnimationClip](../../com.aspose.threed/animationclip) будет назначен методу [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Открывает сцену по указанному пути |
| [fromFile(String fileName, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.Cancellation-) | Открывает сцену по указанному пути |
| [fromFile(String fileName, FileFormat format)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-) | Открывает сцену по указанному пути, используя указанный формат файла. |
| [fromFile(String fileName, FileFormat format, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Открывает сцену по указанному пути, используя указанный формат файла. |
| [fromFile(String fileName, LoadOptions options)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-) | Открывает сцену по указанному пути, используя указанный формат файла. |
| [fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Открывает сцену по указанному пути, используя указанный формат файла. |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Открывает сцену из заданного потока |
| [fromStream(Stream stream, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Открывает сцену из заданного потока |
| [fromStream(Stream stream, FileFormat format)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Открывает сцену из заданного потока, используя указанный формат файла. |
| [fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Открывает сцену из заданного потока, используя указанный формат файла. |
| [fromStream(Stream stream, LoadOptions options)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода. |
| [fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Открывает сцену из заданного потока |
| [fromStream(InputStream stream, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-) | Открывает сцену из заданного потока |
| [fromStream(InputStream stream, FileFormat format)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-) | Открывает сцену из заданного потока, используя указанный формат файла. |
| [fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Открывает сцену из заданного потока, используя указанный формат файла. |
| [fromStream(InputStream stream, LoadOptions options)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-) | Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода. |
| [fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода. |
| [getAnimationClip(String name)](#getAnimationClip-java.lang.String-) | Получает именованный [AnimationClip](../../com.aspose.threed/animationclip) |
| [getAnimationClips()](#getAnimationClips--) | Получает все [AnimationClip](../../com.aspose.threed/animationclip), определённые в сцене. |
| [getAssetInfo()](#getAssetInfo--) | Получает информацию о верхнеуровневом активе |
| [getClass()](#getClass--) |  |
| [getCurrentAnimationClip()](#getCurrentAnimationClip--) | Получает активный [AnimationClip](../../com.aspose.threed/animationclip) |
| [getLibrary()](#getLibrary--) | Объекты, которые не используются напрямую в иерархии сцены, могут быть определены в библиотеке. |
| [getName()](#getName--) | Получает имя. |
| [getPoses()](#getPoses--) | Получает все [Pose](../../com.aspose.threed/pose), используемые в этой сцене. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getRootNode()](#getRootNode--) | Получает корневой узел сцены. |
| [getScene()](#getScene--) | Получает сцену, к которой принадлежит этот объект |
| [getSubScenes()](#getSubScenes--) | Получает все подсцены |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(Stream stream)](#open-com.aspose.threed.Stream-) | Открывает сцену из заданного потока |
| [open(Stream stream, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Открывает сцену из заданного потока |
| [open(Stream stream, FileFormat format)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Открывает сцену из заданного потока, используя указанный формат файла. |
| [open(Stream stream, FileFormat format, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Открывает сцену из заданного потока, используя указанный формат файла. |
| [open(Stream stream, LoadOptions options)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода. |
| [open(Stream stream, LoadOptions options, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода. |
| [open(InputStream stream)](#open-java.io.InputStream-) | Открывает сцену из заданного потока |
| [open(InputStream stream, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.Cancellation-) | Открывает сцену из заданного потока |
| [open(InputStream stream, FileFormat format)](#open-java.io.InputStream-com.aspose.threed.FileFormat-) | Открывает сцену из заданного потока, используя указанный формат файла. |
| [open(InputStream stream, FileFormat format, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Открывает сцену из заданного потока, используя указанный формат файла. |
| [open(InputStream stream, LoadOptions options)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-) | Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода. |
| [open(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода. |
| [open(String fileName)](#open-java.lang.String-) | Открывает сцену по указанному пути |
| [open(String fileName, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.Cancellation-) | Открывает сцену по указанному пути |
| [open(String fileName, FileFormat format)](#open-java.lang.String-com.aspose.threed.FileFormat-) | Открывает сцену по указанному пути, используя указанный формат файла. |
| [open(String fileName, FileFormat format, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Открывает сцену по указанному пути, используя указанный формат файла. |
| [open(String fileName, LoadOptions options)](#open-java.lang.String-com.aspose.threed.LoadOptions-) | Открывает сцену по указанному пути, используя указанный формат файла. |
| [open(String fileName, LoadOptions options, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Открывает сцену по указанному пути, используя указанный формат файла. |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [render(Camera camera, TextureData bitmap)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-) | Отрисовывает сцену в bitmap с точки зрения заданной камеры. |
| [render(Camera camera, TextureData bitmap, ImageRenderOptions options)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-) | Отрисовывает сцену в bitmap с точки зрения заданной камеры. |
| [render(Camera camera, String fileName)](#render-com.aspose.threed.Camera-java.lang.String-) | Отрисовывает сцену во внешний файл с точки зрения заданной камеры. |
| [render(Camera camera, String fileName, Vector2 size, String format)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-) | Отрисовывает сцену во внешний файл с точки зрения заданной камеры. |
| [render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-) | Отрисовывает сцену во внешний файл с точки зрения заданной камеры. |
| [save(Stream stream, FileFormat format)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Сохраняет сцену в поток, используя указанный формат файла. |
| [save(Stream stream, FileFormat format, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Сохраняет сцену в поток, используя указанный формат файла. |
| [save(Stream stream, SaveOptions options)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-) | Сохраняет сцену в поток, используя указанный формат файла. |
| [save(Stream stream, SaveOptions options, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Сохраняет сцену в поток, используя указанный формат файла. |
| [save(OutputStream stream, FileFormat format)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-) | Сохраняет сцену в поток, используя указанный формат файла. |
| [save(OutputStream stream, FileFormat format, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Сохраняет сцену в поток, используя указанный формат файла. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-) | Сохраняет сцену в поток, используя указанный формат файла. |
| [save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Сохраняет сцену в поток, используя указанный формат файла. |
| [save(String fileName)](#save-java.lang.String-) | Сохраняет сцену в указанный путь, используя указанный формат файла. |
| [save(String fileName, FileFormat format)](#save-java.lang.String-com.aspose.threed.FileFormat-) | Сохраняет сцену в указанный путь, используя указанный формат файла. |
| [save(String fileName, FileFormat format, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Сохраняет сцену в указанный путь, используя указанный формат файла. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.threed.SaveOptions-) | Сохраняет сцену в указанный путь, используя указанный формат файла. |
| [save(String fileName, SaveOptions options, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Сохраняет сцену в указанный путь, используя указанный формат файла. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Устанавливает информацию о верхнеуровневом ресурсе |
| [setCurrentAnimationClip(AnimationClip value)](#setCurrentAnimationClip-com.aspose.threed.AnimationClip-) | Устанавливает активный [AnimationClip](../../com.aspose.threed/animationclip) |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scene(Entity entity) {#Scene-com.aspose.threed.Entity-}
```
public Scene(Entity entity)
```


Инициализирует новый экземпляр класса [Scene](../../com.aspose.threed/scene) с сущностью, присоединённой к новому узлу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | entity | [Entity](../../com.aspose.threed/entity) | Первоначальная сущность, присоединённая к сцене **Пример:** Следующий код показывает, как создать [getScene](../../com.aspose.threed/scene\#getScene) напрямую из [Entity](../../com.aspose.threed/entity): |

```
var scene = new Scene(new Box());
``` |

### Scene(Scene parentScene, String name) {#Scene-com.aspose.threed.Scene-java.lang.String-}
```
public Scene(Scene parentScene, String name)
```


Инициализирует новый экземпляр класса [Scene](../../com.aspose.threed/scene) как подсцену.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parentScene | [Scene](../../com.aspose.threed/scene) | Родительская сцена. |
| имя | java.lang.String | Имя сцены. |

### Scene() {#Scene--}
```
public Scene()
```


Инициализирует новый экземпляр класса [Scene](../../com.aspose.threed/scene).

### VERSION {#VERSION}
```
public static final String VERSION
```


Получает текущую версию релиза

### clear() {#clear--}
```
public void clear()
```


Очищает содержимое сцены и восстанавливает настройки по умолчанию.

### createAnimationClip(String name) {#createAnimationClip-java.lang.String-}
```
public AnimationClip createAnimationClip(String name)
```


Краткая функция для создания и регистрации [AnimationClip](../../com.aspose.threed/animationclip). Первый [AnimationClip](../../com.aspose.threed/animationclip) будет назначен методу [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя анимационного клипа |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - A new animation clip instance with given name
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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Находит свойство. Оно может быть динамическим свойством (созданным с помощью CreateDynamicProperty/SetProperty) или нативным свойством (определяемым по его имени)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyName | java.lang.String | Имя свойства. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static Scene fromFile(String fileName)
```


Открывает сцену по указанному пути

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, Cancellation cancellationToken)
```


Открывает сцену по указанному пути

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-}
```
public static Scene fromFile(String fileName, FileFormat format)
```


Открывает сцену по указанному пути, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат файла. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, FileFormat format, Cancellation cancellationToken)
```


Открывает сцену по указанному пути, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат файла. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-}
```
public static Scene fromFile(String fileName, LoadOptions options)
```


Открывает сцену по указанному пути, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Более подробная конфигурация для открытия потока. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Открывает сцену по указанному пути, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Более подробная конфигурация для открытия потока. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static Scene fromStream(Stream stream)
```


Открывает сцену из заданного потока

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, Cancellation cancellationToken)
```


Открывает сцену из заданного потока

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(Stream stream, FileFormat format)
```


Открывает сцену из заданного потока, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат файла. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Открывает сцену из заданного потока, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат файла. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(Stream stream, LoadOptions options)
```


Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Более подробная конфигурация для открытия потока. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Более подробная конфигурация для открытия потока. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static Scene fromStream(InputStream stream)
```


Открывает сцену из заданного потока

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | stream | java.io.InputStream | Входной поток, пользователь отвечает за закрытие потока. **Пример:** Следующий код показывает, как создать сцену из потока с источником токена отмены |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, Cancellation cancellationToken)
```


Открывает сцену из заданного потока

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, пользователь отвечает за закрытие потока. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки **Пример:** Следующий код показывает, как создать сцену из потока с источником токена отмены |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, cts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(InputStream stream, FileFormat format)
```


Открывает сцену из заданного потока, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, пользователь отвечает за закрытие потока. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Формат файла. **Пример:** Следующий код показывает, как создать сцену из потока |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


Открывает сцену из заданного потока, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, пользователь отвечает за закрытие потока. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат файла. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки **Пример:** Следующий код показывает, как создать сцену из потока |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(InputStream stream, LoadOptions options)
```


Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, пользователь отвечает за закрытие потока. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Более подробная конфигурация для открытия потока. **Пример:** Следующий код показывает, как создать сцену из потока с параметрами загрузки |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, пользователь отвечает за закрытие потока. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Более подробная конфигурация для открытия потока. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки **Пример:** Следующий код показывает, как создать сцену из потока с параметрами загрузки |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### getAnimationClip(String name) {#getAnimationClip-java.lang.String-}
```
public AnimationClip getAnimationClip(String name)
```


Получает именованный [AnimationClip](../../com.aspose.threed/animationclip)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя [AnimationClip](../../com.aspose.threed/animationclip) для поиска |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - Returned AnimationClip
### getAnimationClips() {#getAnimationClips--}
```
public List<AnimationClip> getAnimationClips()
```


Получает все [AnimationClip](../../com.aspose.threed/animationclip), определённые в сцене.

**Returns:**
java.util.List<com.aspose.threed.AnimationClip> - все [AnimationClip](../../com.aspose.threed/animationclip), определённые в сцене.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Получает информацию о верхнеуровневом активе

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - the top-level asset information **Example:** The following code shows how to read the application information from a FBX file:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrentAnimationClip() {#getCurrentAnimationClip--}
```
public AnimationClip getCurrentAnimationClip()
```


Получает активный [AnimationClip](../../com.aspose.threed/animationclip)

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - the active [AnimationClip](../../com.aspose.threed/animationclip)
### getLibrary() {#getLibrary--}
```
public List<A3DObject> getLibrary()
```


Объекты, которые не используются напрямую в иерархии сцены, могут быть определены в Library. Это полезно, когда вы используете подсцены и размещаете переиспользуемые компоненты в подсценах.

**Returns:**
java.util.List<com.aspose.threed.A3DObject> - Объекты, которые не используются напрямую в иерархии сцены, могут быть определены в Library. Это полезно, когда вы используете подсцены и размещаете переиспользуемые компоненты в подсценах.
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
### getPoses() {#getPoses--}
```
public Collection<Pose> getPoses()
```


Получает все [Pose](../../com.aspose.threed/pose), используемые в этой сцене.

**Returns:**
java.util.Collection<com.aspose.threed.Pose> - все [Pose](../../com.aspose.threed/pose), используемые в этой сцене.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Получает коллекцию всех свойств.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Получить значение указанного свойства

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Имя свойства |

**Returns:**
java.lang.Object - Значение найденного свойства
### getRootNode() {#getRootNode--}
```
public Node getRootNode()
```


Получает корневой узел сцены.

**Returns:**
[Node](../../com.aspose.threed/node) - the root node of the scene. **Example:** The following code shows how to create a node with Box entity attached to the root node.

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box());
     scene.save("box.stl");
```
### getScene() {#getScene--}
```
public Scene getScene()
```


Получает сцену, к которой принадлежит этот объект

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSubScenes() {#getSubScenes--}
```
public List<Scene> getSubScenes()
```


Получает все подсцены

**Returns:**
java.util.List<com.aspose.threed.Scene> - все подсцены
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




### open(Stream stream) {#open-com.aspose.threed.Stream-}
```
public void open(Stream stream)
```


Открывает сцену из заданного потока

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |

### open(Stream stream, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, Cancellation cancellationToken)
```


Открывает сцену из заданного потока

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки |

### open(Stream stream, FileFormat format) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void open(Stream stream, FileFormat format)
```


Открывает сцену из заданного потока, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат файла. |

### open(Stream stream, FileFormat format, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Открывает сцену из заданного потока, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат файла. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки |

### open(Stream stream, LoadOptions options) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public void open(Stream stream, LoadOptions options)
```


Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Более подробная конфигурация для открытия потока. |

### open(Stream stream, LoadOptions options, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Более подробная конфигурация для открытия потока. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки |

### open(InputStream stream) {#open-java.io.InputStream-}
```
public void open(InputStream stream)
```


Открывает сцену из заданного потока

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | stream | java.io.InputStream | Входной поток, пользователь отвечает за закрытие потока. **Пример:** Следующий код показывает, как открыть сцену из потока |

```
var scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs);    
     }
``` |

### open(InputStream stream, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, Cancellation cancellationToken)
```


Открывает сцену из заданного потока

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, пользователь отвечает за закрытие потока. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки **Example:** Следующий код показывает, как открыть сцену из потока с токеном отмены |

```
var scene = new Scene();    
     Cancellation cts = new Cancellation();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, cts);    
     }
``` |

### open(InputStream stream, FileFormat format) {#open-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public void open(InputStream stream, FileFormat format)
```


Открывает сцену из заданного потока, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, пользователь отвечает за закрытие потока. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Формат файла. **Example:** Следующий код показывает, как открыть сцену из потока |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, FileFormat format, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


Открывает сцену из заданного потока, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, пользователь отвечает за закрытие потока. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат файла. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки **Example:** Следующий код показывает, как открыть сцену из потока |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, LoadOptions options) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public void open(InputStream stream, LoadOptions options)
```


Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, пользователь отвечает за закрытие потока. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Более подробная конфигурация для открытия потока. **Example:** Следующий код показывает, как открыть сцену из потока с дополнительными параметрами загрузки |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


Открывает сцену из заданного потока, используя указанную конфигурацию ввода-вывода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, пользователь отвечает за закрытие потока. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Более подробная конфигурация для открытия потока. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки **Example:** Следующий код показывает, как открыть сцену из потока с дополнительными параметрами загрузки |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(String fileName) {#open-java.lang.String-}
```
public void open(String fileName)
```


Открывает сцену по указанному пути

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |

### open(String fileName, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.Cancellation-}
```
public void open(String fileName, Cancellation cancellationToken)
```


Открывает сцену по указанному пути

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки |

### open(String fileName, FileFormat format) {#open-java.lang.String-com.aspose.threed.FileFormat-}
```
public void open(String fileName, FileFormat format)
```


Открывает сцену по указанному пути, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат файла. |

### open(String fileName, FileFormat format, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(String fileName, FileFormat format, Cancellation cancellationToken)
```


Открывает сцену по указанному пути, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат файла. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки |

### open(String fileName, LoadOptions options) {#open-java.lang.String-com.aspose.threed.LoadOptions-}
```
public void open(String fileName, LoadOptions options)
```


Открывает сцену по указанному пути, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Более подробная конфигурация для открытия потока. |

### open(String fileName, LoadOptions options, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Открывает сцену по указанному пути, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Более подробная конфигурация для открытия потока. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи загрузки |

### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Удаляет динамическое свойство.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Какое свойство удалить |

**Returns:**
boolean - true, если свойство успешно удалено
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Удалить указанное свойство, определяемое по имени

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Какое свойство удалить |

**Returns:**
boolean - true, если свойство успешно удалено
### render(Camera camera, TextureData bitmap) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-}
```
public void render(Camera camera, TextureData bitmap)
```


Отрисовывает сцену в bitmap с точки зрения заданной камеры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | С какой точки зрения камеры рендерить сцену |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Цель полученного результата рендеринга |

### render(Camera camera, TextureData bitmap, ImageRenderOptions options) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```


Отрисовывает сцену в bitmap с точки зрения заданной камеры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | С какой точки зрения камеры рендерить сцену |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Цель полученного результата рендеринга |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | Опция для настройки некоторых внутренних параметров. |

### render(Camera camera, String fileName) {#render-com.aspose.threed.Camera-java.lang.String-}
```
public void render(Camera camera, String fileName)
```


Рендерить сцену во внешний файл с заданной точки зрения камеры. Размер вывода по умолчанию 1024x768, а формат вывода — png

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | С какой точки зрения камеры рендерить сцену |
| fileName | java.lang.String | Имя выходного файла |

### render(Camera camera, String fileName, Vector2 size, String format) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-}
```
public void render(Camera camera, String fileName, Vector2 size, String format)
```


Отрисовывает сцену во внешний файл с точки зрения заданной камеры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | С какой точки зрения камеры рендерить сцену |
| fileName | java.lang.String | Имя выходного файла |
| size | [Vector2](../../com.aspose.threed/vector2) | Размер окончательного отрендеренного изображения |
| формат | java.lang.String | Формат изображения выходного файла |

### render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)
```


Отрисовывает сцену во внешний файл с точки зрения заданной камеры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | С какой точки зрения камеры рендерить сцену |
| fileName | java.lang.String | Имя выходного файла |
| size | [Vector2](../../com.aspose.threed/vector2) | Размер окончательного отрендеренного изображения |
| формат | java.lang.String | Формат изображения выходного файла |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | Опция для настройки некоторых внутренних параметров. |

### save(Stream stream, FileFormat format) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void save(Stream stream, FileFormat format)
```


Сохраняет сцену в поток, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат. |

### save(Stream stream, FileFormat format, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Сохраняет сцену в поток, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи сохранения |

### save(Stream stream, SaveOptions options) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-}
```
public void save(Stream stream, SaveOptions options)
```


Сохраняет сцену в поток, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Более подробная конфигурация для сохранения потока. |

### save(Stream stream, SaveOptions options, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, SaveOptions options, Cancellation cancellationToken)
```


Сохраняет сцену в поток, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Входной поток, пользователь отвечает за закрытие потока. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Более подробная конфигурация для сохранения потока. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи сохранения |

### save(OutputStream stream, FileFormat format) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-}
```
public void save(OutputStream stream, FileFormat format)
```


Сохраняет сцену в поток, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Входной поток, пользователь отвечает за закрытие потока. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Формат. **Example:** Следующий код показывает, как сохранить сцену |

```
Scene scene = Scene.fromFile("input.fbx");    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ);    
     }
``` |

### save(OutputStream stream, FileFormat format, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, FileFormat format, Cancellation cancellationToken)
```


Сохраняет сцену в поток, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Входной поток, пользователь отвечает за закрытие потока. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи сохранения **Example:** Следующий код показывает, как сохранить сцену |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ, cts);    
     }
``` |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


Сохраняет сцену в поток, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Входной поток, пользователь отвечает за закрытие потока. |
|  | options | [SaveOptions](../../com.aspose.threed/saveoptions) | Более подробная конфигурация для сохранения потока. **Example:** Следующий код показывает, как сохранить сцену |

```
Scene scene = Scene.fromFile("input.fbx");    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt);    
     }
``` |

### save(OutputStream stream, SaveOptions options, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)
```


Сохраняет сцену в поток, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Входной поток, пользователь отвечает за закрытие потока. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Более подробная конфигурация для сохранения потока. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи сохранения **Example:** Следующий код показывает, как сохранить сцену |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt, cts);    
     }
``` |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Сохраняет сцену в указанный путь, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |

### save(String fileName, FileFormat format) {#save-java.lang.String-com.aspose.threed.FileFormat-}
```
public void save(String fileName, FileFormat format)
```


Сохраняет сцену в указанный путь, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат. |

### save(String fileName, FileFormat format, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(String fileName, FileFormat format, Cancellation cancellationToken)
```


Сохраняет сцену в указанный путь, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Формат. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи сохранения |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.threed.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


Сохраняет сцену в указанный путь, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Более подробная конфигурация для сохранения потока. |

### save(String fileName, SaveOptions options, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(String fileName, SaveOptions options, Cancellation cancellationToken)
```


Сохраняет сцену в указанный путь, используя указанный формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Более подробная конфигурация для сохранения потока. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Токен отмены для задачи сохранения |

### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Устанавливает информацию о верхнеуровневом ресурсе

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [AssetInfo](../../com.aspose.threed/assetinfo) | Новое значение **Example:** Следующий код показывает, как прочитать информацию о приложении из файла FBX: |

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
``` |

### setCurrentAnimationClip(AnimationClip value) {#setCurrentAnimationClip-com.aspose.threed.AnimationClip-}
```
public void setCurrentAnimationClip(AnimationClip value)
```


Устанавливает активный [AnimationClip](../../com.aspose.threed/animationclip)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [AnimationClip](../../com.aspose.threed/animationclip) | Новое значение |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Устанавливает значение указанного свойства

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Имя свойства |
| значение | java.lang.Object | Значение свойства |

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

