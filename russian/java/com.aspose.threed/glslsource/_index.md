---
title: GLSLSource
second_title: Справочник API Aspose.3D для Java
description: Исходный код шейдеров на GLSL
type: docs
weight: 70
url: /ru/java/com.aspose.threed/glslsource/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.ShaderSource](../../com.aspose.threed/shadersource)
```
public final class GLSLSource extends ShaderSource
```

Исходный код шейдеров на GLSL
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GLSLSource()](#GLSLSource--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [defineInclude(String fileName, String content)](#defineInclude-java.lang.String-java.lang.String-) | Определить виртуальный файл для \#include в исходном коде GLSL |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComputeShader()](#getComputeShader--) | Получает исходный код вычислительного шейдера. |
| [getFragmentShader()](#getFragmentShader--) | Получает исходный код фрагментного шейдера. |
| [getGeometryShader()](#getGeometryShader--) | Получает исходный код геометрического шейдера. |
| [getVertexShader()](#getVertexShader--) | Получает исходный код вершинного шейдера |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setComputeShader(String value)](#setComputeShader-java.lang.String-) | Устанавливает исходный код вычислительного шейдера. |
| [setFragmentShader(String value)](#setFragmentShader-java.lang.String-) | Устанавливает исходный код фрагментного шейдера. |
| [setGeometryShader(String value)](#setGeometryShader-java.lang.String-) | Устанавливает исходный код геометрического шейдера. |
| [setVertexShader(String value)](#setVertexShader-java.lang.String-) | Устанавливает исходный код вершинного шейдера |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GLSLSource() {#GLSLSource--}
```
public GLSLSource()
```


### defineInclude(String fileName, String content) {#defineInclude-java.lang.String-java.lang.String-}
```
public void defineInclude(String fileName, String content)
```


Определить виртуальный файл для \#include в исходном коде GLSL

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла виртуального файла |
| содержимое | java.lang.String |  |

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
### getComputeShader() {#getComputeShader--}
```
public String getComputeShader()
```


Получает исходный код вычислительного шейдера.

**Returns:**
java.lang.String - исходный код вычислительного шейдера.
### getFragmentShader() {#getFragmentShader--}
```
public String getFragmentShader()
```


Получает исходный код фрагментного шейдера.

**Returns:**
java.lang.String - исходный код фрагментного шейдера.
### getGeometryShader() {#getGeometryShader--}
```
public String getGeometryShader()
```


Получает исходный код геометрического шейдера.

**Returns:**
java.lang.String - исходный код геометрического шейдера.
### getVertexShader() {#getVertexShader--}
```
public String getVertexShader()
```


Получает исходный код вершинного шейдера

**Returns:**
java.lang.String - исходный код вершинного шейдера
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




### setComputeShader(String value) {#setComputeShader-java.lang.String-}
```
public void setComputeShader(String value)
```


Устанавливает исходный код вычислительного шейдера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setFragmentShader(String value) {#setFragmentShader-java.lang.String-}
```
public void setFragmentShader(String value)
```


Устанавливает исходный код фрагментного шейдера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setGeometryShader(String value) {#setGeometryShader-java.lang.String-}
```
public void setGeometryShader(String value)
```


Устанавливает исходный код геометрического шейдера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setVertexShader(String value) {#setVertexShader-java.lang.String-}
```
public void setVertexShader(String value)
```


Устанавливает исходный код вершинного шейдера

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

