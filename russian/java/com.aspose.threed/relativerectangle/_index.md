---
title: RelativeRectangle
second_title: Справочник API Aspose.3D для Java
description: Относительный прямоугольник  Формула между относительным компонентом и абсолютным значением:  Scale  Reference Width  offset  Поэтому, если мы хотим представить абсолютное значение, оставьте все поля масштабирования нулевыми и используйте вместо этого поля смещения.
type: docs
weight: 147
url: /ru/java/com.aspose.threed/relativerectangle/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class RelativeRectangle implements Struct<RelativeRectangle>, Serializable
```

Относительный прямоугольник Формула преобразования относительного компонента в абсолютное значение: Scale \\* (Reference Width) + offset. Поэтому, если мы хотим представить абсолютное значение, оставьте все поля масштаба нулевыми и используйте вместо этого поля смещения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RelativeRectangle(int left, int top, int width, int height)](#RelativeRectangle-int-int-int-int-) | Создать [RelativeRectangle](../../com.aspose.threed/relativerectangle) |
| [RelativeRectangle()](#RelativeRectangle--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(RelativeRectangle src)](#copyFrom-com.aspose.threed.RelativeRectangle-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)](#fromScale-float-float-float-float-) | Создать [RelativeRectangle](../../com.aspose.threed/relativerectangle) с нулевыми всеми полями смещения и полями масштабирования из заданных параметров. |
| [getClass()](#getClass--) |  |
| [getOffsetHeight()](#getOffsetHeight--) | Получает смещение по высоте |
| [getOffsetWidth()](#getOffsetWidth--) | Получает смещение по ширине |
| [getOffsetX()](#getOffsetX--) | Получает смещение по координате X |
| [getOffsetY()](#getOffsetY--) | Получает смещение по координате Y |
| [getScaleHeight()](#getScaleHeight--) | Относительная высота |
| [getScaleWidth()](#getScaleWidth--) | Относительная ширина |
| [getScaleX()](#getScaleX--) | Относительная координата X |
| [getScaleY()](#getScaleY--) | Относительная координата Y |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffsetHeight(int value)](#setOffsetHeight-int-) | Устанавливает смещение по высоте |
| [setOffsetWidth(int value)](#setOffsetWidth-int-) | Устанавливает смещение по ширине |
| [setOffsetX(int value)](#setOffsetX-int-) | Устанавливает смещение по координате X |
| [setOffsetY(int value)](#setOffsetY-int-) | Устанавливает смещение по координате Y |
| [setScaleHeight(float value)](#setScaleHeight-float-) | Относительная высота |
| [setScaleWidth(float value)](#setScaleWidth-float-) | Относительная ширина |
| [setScaleX(float value)](#setScaleX-float-) | Относительная координата X |
| [setScaleY(float value)](#setScaleY-float-) | Относительная координата Y |
| [toAbsolute(int left, int top, int width, int height)](#toAbsolute-int-int-int-int-) | Преобразовать относительный прямоугольник в абсолютный прямоугольник |
| [toString()](#toString--) | Преобразует значение этого экземпляра в java.lang.String. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelativeRectangle(int left, int top, int width, int height) {#RelativeRectangle-int-int-int-int-}
```
public RelativeRectangle(int left, int top, int width, int height)
```


Создать [RelativeRectangle](../../com.aspose.threed/relativerectangle)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| слева | int |  |
| верх | int |  |
| ширина | int |  |
| высота | int |  |

### RelativeRectangle() {#RelativeRectangle--}
```
public RelativeRectangle()
```


### clone() {#clone--}
```
public RelativeRectangle clone()
```


Клонировать текущий экземпляр

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### copyFrom(RelativeRectangle src) {#copyFrom-com.aspose.threed.RelativeRectangle-}
```
public void copyFrom(RelativeRectangle src)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [RelativeRectangle](../../com.aspose.threed/relativerectangle) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight) {#fromScale-float-float-float-float-}
```
public static RelativeRectangle fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)
```


Создать [RelativeRectangle](../../com.aspose.threed/relativerectangle) с нулевыми всеми полями смещения и полями масштабирования из заданных параметров.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleX | float |  |
| scaleY | float |  |
| scaleWidth | float |  |
| scaleHeight | float |  |

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOffsetHeight() {#getOffsetHeight--}
```
public int getOffsetHeight()
```


Получает смещение по высоте

**Returns:**
int - смещение по высоте
### getOffsetWidth() {#getOffsetWidth--}
```
public int getOffsetWidth()
```


Получает смещение по ширине

**Returns:**
int - смещение по ширине
### getOffsetX() {#getOffsetX--}
```
public int getOffsetX()
```


Получает смещение по координате X

**Returns:**
int - смещение по координате X
### getOffsetY() {#getOffsetY--}
```
public int getOffsetY()
```


Получает смещение по координате Y

**Returns:**
int - смещение по координате Y
### getScaleHeight() {#getScaleHeight--}
```
public float getScaleHeight()
```


Относительная высота

**Returns:**
float - относительная высота
### getScaleWidth() {#getScaleWidth--}
```
public float getScaleWidth()
```


Относительная ширина

**Returns:**
float - относительная ширина
### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Относительная координата X

**Returns:**
float - относительная координата X
### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Относительная координата Y

**Returns:**
float - относительная координата Y
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setOffsetHeight(int value) {#setOffsetHeight-int-}
```
public void setOffsetHeight(int value)
```


Устанавливает смещение по высоте

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setOffsetWidth(int value) {#setOffsetWidth-int-}
```
public void setOffsetWidth(int value)
```


Устанавливает смещение по ширине

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setOffsetX(int value) {#setOffsetX-int-}
```
public void setOffsetX(int value)
```


Устанавливает смещение по координате X

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setOffsetY(int value) {#setOffsetY-int-}
```
public void setOffsetY(int value)
```


Устанавливает смещение по координате Y

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setScaleHeight(float value) {#setScaleHeight-float-}
```
public void setScaleHeight(float value)
```


Относительная высота

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Новое значение |

### setScaleWidth(float value) {#setScaleWidth-float-}
```
public void setScaleWidth(float value)
```


Относительная ширина

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Новое значение |

### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Относительная координата X

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Новое значение |

### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Относительная координата Y

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Новое значение |

### toAbsolute(int left, int top, int width, int height) {#toAbsolute-int-int-int-int-}
```
public Rect toAbsolute(int left, int top, int width, int height)
```


Преобразовать относительный прямоугольник в абсолютный прямоугольник

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| слева | int | Левая сторона прямоугольника |
| верх | int | Верхняя сторона прямоугольника |
| ширина | int | Ширина прямоугольника |
| высота | int | Высота прямоугольника |

**Returns:**
[Rect](../../com.aspose.threed/rect)
### toString() {#toString--}
```
public String toString()
```


Преобразует значение этого экземпляра в java.lang.String.

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

