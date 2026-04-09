---
title: GLSLSource
second_title: Aspose.3D for Java API-referens
description: Källkoden för shaders i GLSL
type: docs
weight: 70
url: /sv/java/com.aspose.threed/glslsource/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.ShaderSource](../../com.aspose.threed/shadersource)
```
public final class GLSLSource extends ShaderSource
```

Källkoden för shaders i GLSL
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GLSLSource()](#GLSLSource--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [defineInclude(String fileName, String content)](#defineInclude-java.lang.String-java.lang.String-) | Definiera virtuell fil för \#include i GLSL-källkod |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComputeShader()](#getComputeShader--) | Gets the source code of the compute shader. |
| [getFragmentShader()](#getFragmentShader--) | Gets the source code of the fragment shader. |
| [getGeometryShader()](#getGeometryShader--) | Gets the source code of the geometry shader. |
| [getVertexShader()](#getVertexShader--) | Gets the source code of the vertex shader |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setComputeShader(String value)](#setComputeShader-java.lang.String-) | Sets the source code of the compute shader. |
| [setFragmentShader(String value)](#setFragmentShader-java.lang.String-) | Sets the source code of the fragment shader. |
| [setGeometryShader(String value)](#setGeometryShader-java.lang.String-) | Sets the source code of the geometry shader. |
| [setVertexShader(String value)](#setVertexShader-java.lang.String-) | Sets the source code of the vertex shader |
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


Definiera virtuell fil för \#include i GLSL-källkod

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn för den virtuella filen |
| innehåll | java.lang.String |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Gets the source code of the compute shader.

**Returns:**
java.lang.String - källkoden för compute‑shadern.
### getFragmentShader() {#getFragmentShader--}
```
public String getFragmentShader()
```


Gets the source code of the fragment shader.

**Returns:**
java.lang.String - källkoden för fragment‑shadern.
### getGeometryShader() {#getGeometryShader--}
```
public String getGeometryShader()
```


Gets the source code of the geometry shader.

**Returns:**
java.lang.String - källkoden för geometry‑shadern.
### getVertexShader() {#getVertexShader--}
```
public String getVertexShader()
```


Gets the source code of the vertex shader

**Returns:**
java.lang.String - källkoden för vertex‑shadern
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


Sets the source code of the compute shader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setFragmentShader(String value) {#setFragmentShader-java.lang.String-}
```
public void setFragmentShader(String value)
```


Sets the source code of the fragment shader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setGeometryShader(String value) {#setGeometryShader-java.lang.String-}
```
public void setGeometryShader(String value)
```


Sets the source code of the geometry shader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setVertexShader(String value) {#setVertexShader-java.lang.String-}
```
public void setVertexShader(String value)
```


Sets the source code of the vertex shader

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

