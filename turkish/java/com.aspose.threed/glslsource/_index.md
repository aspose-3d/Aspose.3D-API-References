---
title: "GLSLSource"
second_title: "Aspose.3D for Java API Referansı"
description: "GLSL'deki gölgelendiricilerin kaynak kodu"
type: docs
weight: 70
url: /tr/java/com.aspose.threed/glslsource/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.ShaderSource](../../com.aspose.threed/shadersource)
```
public final class GLSLSource extends ShaderSource
```

GLSL'deki gölgelendiricilerin kaynak kodu
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GLSLSource()](#GLSLSource--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [defineInclude(String fileName, String content)](#defineInclude-java.lang.String-java.lang.String-) | GLSL kaynak kodunda \#include için sanal dosya tanımla |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComputeShader()](#getComputeShader--) | Hesaplama gölgelendiricisinin kaynak kodunu alır. |
| [getFragmentShader()](#getFragmentShader--) | Parça gölgelendiricisinin kaynak kodunu alır. |
| [getGeometryShader()](#getGeometryShader--) | Geometri gölgelendiricisinin kaynak kodunu alır. |
| [getVertexShader()](#getVertexShader--) | Vertex gölgelendiricisinin kaynak kodunu alır |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setComputeShader(String value)](#setComputeShader-java.lang.String-) | Hesaplama gölgelendiricisinin kaynak kodunu ayarlar. |
| [setFragmentShader(String value)](#setFragmentShader-java.lang.String-) | Parça gölgelendiricisinin kaynak kodunu ayarlar. |
| [setGeometryShader(String value)](#setGeometryShader-java.lang.String-) | Geometri gölgelendiricisinin kaynak kodunu ayarlar. |
| [setVertexShader(String value)](#setVertexShader-java.lang.String-) | Vertex gölgelendiricisinin kaynak kodunu ayarlar |
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


GLSL kaynak kodunda \#include için sanal dosya tanımla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Sanal dosyanın dosya adı |
| içerik | java.lang.String |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Hesaplama gölgelendiricisinin kaynak kodunu alır.

**Returns:**
java.lang.String - compute shader'ın kaynak kodu.
### getFragmentShader() {#getFragmentShader--}
```
public String getFragmentShader()
```


Parça gölgelendiricisinin kaynak kodunu alır.

**Returns:**
java.lang.String - fragment shader'ın kaynak kodu.
### getGeometryShader() {#getGeometryShader--}
```
public String getGeometryShader()
```


Geometri gölgelendiricisinin kaynak kodunu alır.

**Returns:**
java.lang.String - geometry shader'ın kaynak kodu.
### getVertexShader() {#getVertexShader--}
```
public String getVertexShader()
```


Vertex gölgelendiricisinin kaynak kodunu alır

**Returns:**
java.lang.String - vertex shader'ın kaynak kodu
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


Hesaplama gölgelendiricisinin kaynak kodunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setFragmentShader(String value) {#setFragmentShader-java.lang.String-}
```
public void setFragmentShader(String value)
```


Parça gölgelendiricisinin kaynak kodunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setGeometryShader(String value) {#setGeometryShader-java.lang.String-}
```
public void setGeometryShader(String value)
```


Geometri gölgelendiricisinin kaynak kodunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setVertexShader(String value) {#setVertexShader-java.lang.String-}
```
public void setVertexShader(String value)
```


Vertex gölgelendiricisinin kaynak kodunu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

