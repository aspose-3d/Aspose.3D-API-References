---
title: ShaderSet
second_title: Aspose.3D for Java API-referentie
description: Shaderprogramma's voor elk type materiaal
type: docs
weight: 166
url: /nl/java/com.aspose.threed/shaderset/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class ShaderSet implements Closeable
```

Shaderprogramma's voor elk type materiaal
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ShaderSet()](#ShaderSet--) | Maak de instantie van [ShaderSet](../../com.aspose.threed/shaderset) |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [close()](#close--) | Verwijder deze instantie en maak alle shaderprogramma's vrij. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | Haalt de fallback-shader op wanneer de vereiste shader niet beschikbaar is. |
| [getLambert()](#getLambert--) | Haalt de shader op die wordt gebruikt om het lambert-materiaal te renderen. |
| [getPbr()](#getPbr--) | Haalt de shader op die wordt gebruikt om het PBR-materiaal te renderen. |
| [getPhong()](#getPhong--) | Haalt de shader op die wordt gebruikt om het phong-materiaal te renderen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(ShaderProgram value)](#setFallback-com.aspose.threed.ShaderProgram-) | Stelt de fallback-shader in wanneer de vereiste shader niet beschikbaar is. |
| [setLambert(ShaderProgram value)](#setLambert-com.aspose.threed.ShaderProgram-) | Stelt de shader in die wordt gebruikt om het lambert-materiaal te renderen. |
| [setPbr(ShaderProgram value)](#setPbr-com.aspose.threed.ShaderProgram-) | Stelt de shader in die wordt gebruikt om het PBR-materiaal te renderen. |
| [setPhong(ShaderProgram value)](#setPhong-com.aspose.threed.ShaderProgram-) | Stelt de shader in die wordt gebruikt om het phong-materiaal te renderen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderSet() {#ShaderSet--}
```
public ShaderSet()
```


Maak de instantie van [ShaderSet](../../com.aspose.threed/shaderset)

### close() {#close--}
```
public void close()
```


Verwijder deze instantie en maak alle shaderprogramma's vrij.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de fallback-shader op wanneer de vereiste shader niet beschikbaar is.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the fallback shader when required shader is unavailable
### getLambert() {#getLambert--}
```
public ShaderProgram getLambert()
```


Haalt de shader op die wordt gebruikt om het lambert-materiaal te renderen.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the lambert material
### getPbr() {#getPbr--}
```
public ShaderProgram getPbr()
```


Haalt de shader op die wordt gebruikt om het PBR-materiaal te renderen.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the PBR material
### getPhong() {#getPhong--}
```
public ShaderProgram getPhong()
```


Haalt de shader op die wordt gebruikt om het phong-materiaal te renderen.

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


Stelt de fallback-shader in wanneer de vereiste shader niet beschikbaar is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nieuwe waarde |

### setLambert(ShaderProgram value) {#setLambert-com.aspose.threed.ShaderProgram-}
```
public void setLambert(ShaderProgram value)
```


Stelt de shader in die wordt gebruikt om het lambert-materiaal te renderen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nieuwe waarde |

### setPbr(ShaderProgram value) {#setPbr-com.aspose.threed.ShaderProgram-}
```
public void setPbr(ShaderProgram value)
```


Stelt de shader in die wordt gebruikt om het PBR-materiaal te renderen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nieuwe waarde |

### setPhong(ShaderProgram value) {#setPhong-com.aspose.threed.ShaderProgram-}
```
public void setPhong(ShaderProgram value)
```


Stelt de shader in die wordt gebruikt om het phong-materiaal te renderen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nieuwe waarde |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

