---
title: "GLSLSource"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "الكود المصدري للـ shaders في GLSL"
type: docs
weight: 70
url: /ar/java/com.aspose.threed/glslsource/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.ShaderSource](../../com.aspose.threed/shadersource)
```
public final class GLSLSource extends ShaderSource
```

الكود المصدري للـ shaders في GLSL
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [GLSLSource()](#GLSLSource--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [defineInclude(String fileName, String content)](#defineInclude-java.lang.String-java.lang.String-) | تعريف ملف افتراضي لـ \#include في شفرة مصدر GLSL |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComputeShader()](#getComputeShader--) | يحصل على شفرة المصدر لظل الحوسبة. |
| [getFragmentShader()](#getFragmentShader--) | يحصل على شفرة المصدر لظل الجزء. |
| [getGeometryShader()](#getGeometryShader--) | يحصل على شفرة المصدر لظل الهندسة. |
| [getVertexShader()](#getVertexShader--) | يحصل على شفرة المصدر لظل الرأس |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setComputeShader(String value)](#setComputeShader-java.lang.String-) | يضبط شفرة المصدر لظل الحوسبة. |
| [setFragmentShader(String value)](#setFragmentShader-java.lang.String-) | يضبط شفرة المصدر لظل الجزء. |
| [setGeometryShader(String value)](#setGeometryShader-java.lang.String-) | يضبط شفرة المصدر لظل الهندسة. |
| [setVertexShader(String value)](#setVertexShader-java.lang.String-) | يضبط شفرة المصدر لظل الرأس |
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


تعريف ملف افتراضي لـ \#include في شفرة مصدر GLSL

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف للملف الافتراضي |
| المحتوى | java.lang.String |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
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


يحصل على شفرة المصدر لظل الحوسبة.

**Returns:**
java.lang.String - شفرة المصدر للـ compute shader.
### getFragmentShader() {#getFragmentShader--}
```
public String getFragmentShader()
```


يحصل على شفرة المصدر لظل الجزء.

**Returns:**
java.lang.String - شفرة المصدر للـ fragment shader.
### getGeometryShader() {#getGeometryShader--}
```
public String getGeometryShader()
```


يحصل على شفرة المصدر لظل الهندسة.

**Returns:**
java.lang.String - شفرة المصدر للـ geometry shader.
### getVertexShader() {#getVertexShader--}
```
public String getVertexShader()
```


يحصل على شفرة المصدر لظل الرأس

**Returns:**
java.lang.String - شفرة المصدر للـ vertex shader
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


يضبط شفرة المصدر لظل الحوسبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setFragmentShader(String value) {#setFragmentShader-java.lang.String-}
```
public void setFragmentShader(String value)
```


يضبط شفرة المصدر لظل الجزء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setGeometryShader(String value) {#setGeometryShader-java.lang.String-}
```
public void setGeometryShader(String value)
```


يضبط شفرة المصدر لظل الهندسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setVertexShader(String value) {#setVertexShader-java.lang.String-}
```
public void setVertexShader(String value)
```


يضبط شفرة المصدر لظل الرأس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

