---
title: AssetInfo
second_title: Справочник API Aspose.3D для Java
description: Информация об объекте.
type: docs
weight: 17
url: /ru/java/com.aspose.threed/assetinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AssetInfo extends A3DObject
```

Информация об активе. Информация об активе может быть прикреплена к [Scene](../../com.aspose.threed/scene). Дочерний [Scene](../../com.aspose.threed/scene) может иметь собственный [AssetInfo](../../com.aspose.threed/assetinfo) для переопределения определения родителя. **Пример:** Следующий код показывает, как прочитать информацию об активе из файла fbx:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The file is created at %s by %s %s",
          scene.getAssetInfo().getCreationTime(),
          scene.getAssetInfo().getApplicationName(),
          scene.getAssetInfo().getApplicationVersion());
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AssetInfo()](#AssetInfo--) | Инициализирует новый экземпляр класса [AssetInfo](../../com.aspose.threed/assetinfo). |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | Инициализирует новый экземпляр класса [AssetInfo](../../com.aspose.threed/assetinfo). |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getAmbient()](#getAmbient--) | Получает или задает цвет фонового освещения по умолчанию этого актива |
| [getApplicationName()](#getApplicationName--) | Получает приложение, создавшее этот актив |
| [getApplicationVendor()](#getApplicationVendor--) | Получает название поставщика приложения |
| [getApplicationVersion()](#getApplicationVersion--) | Получает версию приложения, создавшего этот актив. |
| [getAuthor()](#getAuthor--) | Получает автора этого актива |
| [getAxisSystem()](#getAxisSystem--) | Получает систему координат, вектор вверх и вектор передней части информации об активе. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Получает комментарий к этому активу. |
| [getCoordinateSystem()](#getCoordinateSystem--) | Получает систему координат, используемую в этом активе. |
| [getCopyright()](#getCopyright--) | Получает авторские права документа |
| [getCreationTime()](#getCreationTime--) | Получает или задает время создания этого актива |
| [getFrontVector()](#getFrontVector--) | Получает front-vector, используемый в этом активе. |
| [getKeywords()](#getKeywords--) | Получает ключевые слова этого актива |
| [getModificationTime()](#getModificationTime--) | Получает или задает время изменения этого актива |
| [getName()](#getName--) | Получает имя. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getRevision()](#getRevision--) | Получает номер ревизии этого актива, обычно используемый в системе контроля версий. |
| [getSubject()](#getSubject--) | Получает тему этого актива |
| [getTitle()](#getTitle--) | Получает заголовок этого актива |
| [getUnitName()](#getUnitName--) | Получает единицу длины, используемую в этом активе. |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | Получает коэффициент масштабирования к реальному метру. |
| [getUpVector()](#getUpVector--) | Получает up-vector, используемый в этом активе. |
| [getUrl()](#getUrl--) | Получает или задает URL этого актива. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | Получает или задает цвет фонового освещения по умолчанию этого актива |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | Задает приложение, создавшее этот актив |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | Задает имя поставщика приложения |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | Задает версию приложения, создавшего этот актив. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Задает автора этого актива |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Задает систему координат/вектор вверх/вектор передней стороны информации об активе. |
| [setComment(String value)](#setComment-java.lang.String-) | Задает комментарий к этому активу. |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | Задает систему координат, используемую в этом активе. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Задает авторские права документа |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | Получает или задает время создания этого актива |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | Задает front-vector, используемый в этом активе. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Задает ключевые слова этого актива |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | Получает или задает время изменения этого актива |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setRevision(String value)](#setRevision-java.lang.String-) | Задает номер ревизии этого актива, обычно используемый в системе контроля версий. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Задает тему этого актива |
| [setTitle(String value)](#setTitle-java.lang.String-) | Задает заголовок этого актива |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | Задает единицу длины, используемую в этом активе. |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | Устанавливает коэффициент масштабирования в реальный метр. |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | Устанавливает вектор вверх, используемый в этом объекте. |
| [setUrl(String value)](#setUrl-java.lang.String-) | Получает или задает URL этого актива. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


Инициализирует новый экземпляр класса [AssetInfo](../../com.aspose.threed/assetinfo).

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


Инициализирует новый экземпляр класса [AssetInfo](../../com.aspose.threed/assetinfo).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя |

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
### getAmbient() {#getAmbient--}
```
public Vector4 getAmbient()
```


Получает или задает цвет фонового освещения по умолчанию этого актива

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - or Sets the default ambient color of this asset
### getApplicationName() {#getApplicationName--}
```
public String getApplicationName()
```


Получает приложение, создавшее этот актив

**Returns:**
java.lang.String - приложение, создавшее этот объект
### getApplicationVendor() {#getApplicationVendor--}
```
public String getApplicationVendor()
```


Получает название поставщика приложения

**Returns:**
java.lang.String - имя поставщика приложения
### getApplicationVersion() {#getApplicationVersion--}
```
public String getApplicationVersion()
```


Получает версию приложения, создавшего этот актив.

**Returns:**
java.lang.String - версия приложения, создавшего этот объект.
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Получает автора этого актива

**Returns:**
java.lang.String - автор этого объекта
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Получает систему координат, вектор вверх и вектор передней части информации об активе.

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the coordinate system/up vector/front vector of the asset info.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public String getComment()
```


Получает комментарий к этому активу.

**Returns:**
java.lang.String - комментарий к этому объекту.
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


Получает систему координат, используемую в этом активе.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system used in this asset.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Получает авторские права документа

**Returns:**
java.lang.String - авторские права документа
### getCreationTime() {#getCreationTime--}
```
public Calendar getCreationTime()
```


Получает или задает время создания этого актива

**Returns:**
java.util.Calendar - или устанавливает время создания этого объекта
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


Получает front-vector, используемый в этом активе.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Получает ключевые слова этого актива

**Returns:**
java.lang.String - ключевые слова этого объекта
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


Получает или задает время изменения этого актива

**Returns:**
java.util.Calendar - или устанавливает время изменения этого объекта
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
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
### getRevision() {#getRevision--}
```
public String getRevision()
```


Получает номер ревизии этого актива, обычно используемый в системе контроля версий.

**Returns:**
java.lang.String - номер ревизии этого объекта, обычно используемый в системе контроля версий.
### getSubject() {#getSubject--}
```
public String getSubject()
```


Получает тему этого актива

**Returns:**
java.lang.String - тема этого объекта
### getTitle() {#getTitle--}
```
public String getTitle()
```


Получает заголовок этого актива

**Returns:**
java.lang.String - название этого объекта
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


Получает единицу длины, используемую в этом объекте. например, см/м/км/дюйм/фут

**Returns:**
java.lang.String - единица длины, используемая в этом объекте. например, см/м/км/дюйм/фут
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


Получает коэффициент масштабирования к реальному метру.

**Returns:**
double - коэффициент масштабирования в реальный метр. **Remarks:** Это игнорируется при сериализации, если имя единицы равно null.
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


Получает up-vector, используемый в этом активе.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


Получает или задает URL этого актива.

**Returns:**
java.lang.String - или устанавливает URL этого объекта.
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
### setAmbient(Vector4 value) {#setAmbient-com.aspose.threed.Vector4-}
```
public void setAmbient(Vector4 value)
```


Получает или задает цвет фонового освещения по умолчанию этого актива

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector4](../../com.aspose.threed/vector4) | Новое значение |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


Задает приложение, создавшее этот актив

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


Задает имя поставщика приложения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


Задает версию приложения, создавшего этот актив.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Задает автора этого актива

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


Задает систему координат/вектор вверх/вектор передней стороны информации об активе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Новое значение |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Задает комментарий к этому активу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


Задает систему координат, используемую в этом активе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Новое значение |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Задает авторские права документа

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


Получает или задает время создания этого актива

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Calendar | Новое значение |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


Задает front-vector, используемый в этом активе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Новое значение |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Задает ключевые слова этого актива

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


Получает или задает время изменения этого актива

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Calendar | Новое значение |

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

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


Задает номер ревизии этого актива, обычно используемый в системе контроля версий.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Задает тему этого актива

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Задает заголовок этого актива

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


Устанавливает единицу длины, используемую в этом объекте. например, см/м/км/дюйм/фут

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


Устанавливает коэффициент масштабирования в реальный метр.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение **Remarks:** Это игнорируется при сериализации, если имя единицы равно null. |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


Устанавливает вектор вверх, используемый в этом объекте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Новое значение |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


Получает или задает URL этого актива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

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

