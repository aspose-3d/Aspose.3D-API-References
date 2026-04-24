---
title: TextureData
second_title: Справочник API Aspose.3D для Java
description: Этот класс содержит необработанные данные и определение формата текстуры.
type: docs
weight: 187
url: /ru/java/com.aspose.threed/texturedata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureData extends A3DObject
```

Этот класс содержит необработанные данные и определение формата текстуры.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)](#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---) | Конструктор [TextureData](../../com.aspose.threed/texturedata) |
| [TextureData(int width, int height, PixelFormat pixelFormat)](#TextureData-int-int-com.aspose.threed.PixelFormat-) | Создаёт новый [TextureData](../../com.aspose.threed/texturedata) и выделяет данные пикселей. |
| [TextureData()](#TextureData--) | Конструктор [TextureData](../../com.aspose.threed/texturedata) |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Загрузить текстуру из файла |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Загрузить текстуру из потока |
| [getBytesPerPixel()](#getBytesPerPixel--) | Количество байтов в пикселе |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Необработанные байты данных пикселя |
| [getHeight()](#getHeight--) | Количество вертикальных пикселей |
| [getName()](#getName--) | Получает имя. |
| [getPixelFormat()](#getPixelFormat--) | Формат пикселя |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getStride()](#getStride--) | Количество байтов в строке сканирования. |
| [getWidth()](#getWidth--) | Количество горизонтальных пикселей |
| [hashCode()](#hashCode--) |  |
| [mapPixels(PixelMapMode mapMode)](#mapPixels-com.aspose.threed.PixelMapMode-) | Отобразить все пиксели для чтения/записи |
| [mapPixels(PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Отобразить все пиксели для чтения/записи в заданном формате пикселей |
| [mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Отобразить пиксели, указанные прямоугольником, для чтения/записи в заданном формате пикселей |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [save(Stream stream, String format)](#save-com.aspose.threed.Stream-java.lang.String-) | Сохранить данные текстуры в указанный формат изображения |
| [save(String fileName)](#save-java.lang.String-) | Сохранить данные текстуры в файл изображения |
| [save(String fileName, String format)](#save-java.lang.String-java.lang.String-) | Сохранить данные текстуры в файл изображения |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [toString()](#toString--) |  |
| [transformPixelFormat(PixelFormat pixelFormat)](#transformPixelFormat-com.aspose.threed.PixelFormat-) | Преобразовать расположение пикселя в новый формат пикселей. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data) {#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)
```


Конструктор [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ширина | int |  |
| высота | int |  |
| шаг | int |  |
| bytesPerPixel | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |
| данные | byte[] |  |

### TextureData(int width, int height, PixelFormat pixelFormat) {#TextureData-int-int-com.aspose.threed.PixelFormat-}
```
public TextureData(int width, int height, PixelFormat pixelFormat)
```


Создаёт новый [TextureData](../../com.aspose.threed/texturedata) и выделяет данные пикселей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ширина | int |  |
| высота | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |

### TextureData() {#TextureData--}
```
public TextureData()
```


Конструктор [TextureData](../../com.aspose.threed/texturedata)

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
public static TextureData fromFile(String fileName)
```


Загрузить текстуру из файла

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static TextureData fromStream(Stream stream)
```


Загрузить текстуру из потока

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### getBytesPerPixel() {#getBytesPerPixel--}
```
public int getBytesPerPixel()
```


Количество байтов в пикселе

**Returns:**
int - Количество байтов в пикселе
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


Необработанные байты данных пикселя

**Returns:**
byte[] - Необработанные байты данных пикселя
### getHeight() {#getHeight--}
```
public int getHeight()
```


Количество вертикальных пикселей

**Returns:**
int - Количество вертикальных пикселей
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
### getPixelFormat() {#getPixelFormat--}
```
public PixelFormat getPixelFormat()
```


Формат пикселя

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat) - The pixel's format
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
### getStride() {#getStride--}
```
public int getStride()
```


Количество байтов в строке сканирования.

**Returns:**
int - Количество байтов в строке сканирования.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Количество горизонтальных пикселей

**Returns:**
int - Количество горизонтальных пикселей
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mapPixels(PixelMapMode mapMode) {#mapPixels-com.aspose.threed.PixelMapMode-}
```
public PixelMapping mapPixels(PixelMapMode mapMode)
```


Отобразить все пиксели для чтения/записи

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Режим отображения |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(PixelMapMode mapMode, PixelFormat format)
```


Отобразить все пиксели для чтения/записи в заданном формате пикселей

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Режим отображения |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Формат пикселя |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```


Отобразить пиксели, указанные прямоугольником, для чтения/записи в заданном формате пикселей

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rect](../../com.aspose.threed/rect) | Область пикселей, к которой будет осуществляться доступ |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Режим отображения |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Формат пикселя |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping) - Returns a mapping object, it should be disposed when no longer needed.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
### save(Stream stream, String format) {#save-com.aspose.threed.Stream-java.lang.String-}
```
public void save(Stream stream, String format)
```


Сохранить данные текстуры в указанный формат изображения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Поток, содержащий сохранённое изображение |
| формат | java.lang.String | Формат изображения, обычно расширение файла |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Сохранить данные текстуры в файл изображения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла, в котором будет сохранено изображение. |

### save(String fileName, String format) {#save-java.lang.String-java.lang.String-}
```
public void save(String fileName, String format)
```


Сохранить данные текстуры в файл изображения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла, в котором будет сохранено изображение. |
| формат | java.lang.String | Формат изображения выходного файла. |

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
### transformPixelFormat(PixelFormat pixelFormat) {#transformPixelFormat-com.aspose.threed.PixelFormat-}
```
public void transformPixelFormat(PixelFormat pixelFormat)
```


Преобразовать расположение пикселя в новый формат пикселей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) | Формат пикселя назначения |

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

