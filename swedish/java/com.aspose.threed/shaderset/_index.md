---
title: ShaderSet
second_title: Aspose.3D for Java API-referens
description: Shaderprogram för varje typ av material
type: docs
weight: 166
url: /sv/java/com.aspose.threed/shaderset/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class ShaderSet implements Closeable
```

Shaderprogram för varje typ av material
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ShaderSet()](#ShaderSet--) | Skapa instansen av [ShaderSet](../../com.aspose.threed/shaderset) |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close()](#close--) | Avsluta denna instans och frigör alla shaderprogram. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | Hämtar reservshader när den erforderliga shadern inte är tillgänglig |
| [getLambert()](#getLambert--) | Hämtar shadern som används för att rendera lambert-materialet |
| [getPbr()](#getPbr--) | Hämtar shadern som används för att rendera PBR-materialet |
| [getPhong()](#getPhong--) | Hämtar shadern som används för att rendera phong-materialet |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(ShaderProgram value)](#setFallback-com.aspose.threed.ShaderProgram-) | Ställer in reservshader när den erforderliga shadern inte är tillgänglig |
| [setLambert(ShaderProgram value)](#setLambert-com.aspose.threed.ShaderProgram-) | Ställer in shadern som används för att rendera lambert-materialet |
| [setPbr(ShaderProgram value)](#setPbr-com.aspose.threed.ShaderProgram-) | Ställer in shadern som används för att rendera PBR-materialet |
| [setPhong(ShaderProgram value)](#setPhong-com.aspose.threed.ShaderProgram-) | Ställer in shadern som används för att rendera phong-materialet |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderSet() {#ShaderSet--}
```
public ShaderSet()
```


Skapa instansen av [ShaderSet](../../com.aspose.threed/shaderset)

### close() {#close--}
```
public void close()
```


Avsluta denna instans och frigör alla shaderprogram.

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
### getFallback() {#getFallback--}
```
public ShaderProgram getFallback()
```


Hämtar reservshader när den erforderliga shadern inte är tillgänglig

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the fallback shader when required shader is unavailable
### getLambert() {#getLambert--}
```
public ShaderProgram getLambert()
```


Hämtar shadern som används för att rendera lambert-materialet

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the lambert material
### getPbr() {#getPbr--}
```
public ShaderProgram getPbr()
```


Hämtar shadern som används för att rendera PBR-materialet

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the PBR material
### getPhong() {#getPhong--}
```
public ShaderProgram getPhong()
```


Hämtar shadern som används för att rendera phong-materialet

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the phong material
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




### setFallback(ShaderProgram value) {#setFallback-com.aspose.threed.ShaderProgram-}
```
public void setFallback(ShaderProgram value)
```


Ställer in reservshader när den erforderliga shadern inte är tillgänglig

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nytt värde |

### setLambert(ShaderProgram value) {#setLambert-com.aspose.threed.ShaderProgram-}
```
public void setLambert(ShaderProgram value)
```


Ställer in shadern som används för att rendera lambert-materialet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nytt värde |

### setPbr(ShaderProgram value) {#setPbr-com.aspose.threed.ShaderProgram-}
```
public void setPbr(ShaderProgram value)
```


Ställer in shadern som används för att rendera PBR-materialet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nytt värde |

### setPhong(ShaderProgram value) {#setPhong-com.aspose.threed.ShaderProgram-}
```
public void setPhong(ShaderProgram value)
```


Ställer in shadern som används för att rendera phong-materialet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nytt värde |

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

