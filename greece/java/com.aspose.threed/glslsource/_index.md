---
title: GLSLSource
second_title: Aspose.3D for Java API Reference
description: Ο πηγαίος κώδικας των shaders σε GLSL
type: docs
weight: 70
url: /el/java/com.aspose.threed/glslsource/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.ShaderSource](../../com.aspose.threed/shadersource)
```
public final class GLSLSource extends ShaderSource
```

Ο πηγαίος κώδικας των shaders σε GLSL
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [GLSLSource()](#GLSLSource--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [defineInclude(String fileName, String content)](#defineInclude-java.lang.String-java.lang.String-) | Ορίστε εικονικό αρχείο για \#include στον κώδικα πηγής GLSL |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComputeShader()](#getComputeShader--) | Λαμβάνει τον κώδικα πηγής του compute shader. |
| [getFragmentShader()](#getFragmentShader--) | Λαμβάνει τον κώδικα πηγής του fragment shader. |
| [getGeometryShader()](#getGeometryShader--) | Λαμβάνει τον κώδικα πηγής του geometry shader. |
| [getVertexShader()](#getVertexShader--) | Λαμβάνει τον κώδικα πηγής του vertex shader |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setComputeShader(String value)](#setComputeShader-java.lang.String-) | Ορίζει τον κώδικα πηγής του compute shader. |
| [setFragmentShader(String value)](#setFragmentShader-java.lang.String-) | Ορίζει τον κώδικα πηγής του fragment shader. |
| [setGeometryShader(String value)](#setGeometryShader-java.lang.String-) | Ορίζει τον κώδικα πηγής του geometry shader. |
| [setVertexShader(String value)](#setVertexShader-java.lang.String-) | Ορίζει τον κώδικα πηγής του vertex shader |
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


Ορίστε εικονικό αρχείο για \#include στον κώδικα πηγής GLSL

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου του εικονικού αρχείου |
| content | java.lang.String |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Λαμβάνει τον κώδικα πηγής του compute shader.

**Returns:**
java.lang.String - ο κώδικας πηγής του compute shader.
### getFragmentShader() {#getFragmentShader--}
```
public String getFragmentShader()
```


Λαμβάνει τον κώδικα πηγής του fragment shader.

**Returns:**
java.lang.String - ο κώδικας πηγής του fragment shader.
### getGeometryShader() {#getGeometryShader--}
```
public String getGeometryShader()
```


Λαμβάνει τον κώδικα πηγής του geometry shader.

**Returns:**
java.lang.String - ο κώδικας πηγής του geometry shader.
### getVertexShader() {#getVertexShader--}
```
public String getVertexShader()
```


Λαμβάνει τον κώδικα πηγής του vertex shader

**Returns:**
java.lang.String - ο κώδικας πηγής του vertex shader
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


Ορίζει τον κώδικα πηγής του compute shader.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setFragmentShader(String value) {#setFragmentShader-java.lang.String-}
```
public void setFragmentShader(String value)
```


Ορίζει τον κώδικα πηγής του fragment shader.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setGeometryShader(String value) {#setGeometryShader-java.lang.String-}
```
public void setGeometryShader(String value)
```


Ορίζει τον κώδικα πηγής του geometry shader.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setVertexShader(String value) {#setVertexShader-java.lang.String-}
```
public void setVertexShader(String value)
```


Ορίζει τον κώδικα πηγής του vertex shader

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

