---
title: "ShaderSet"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Programmes de shader pour chaque type de matériau"
type: docs
weight: 166
url: /fr/java/com.aspose.threed/shaderset/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class ShaderSet implements Closeable
```

Programmes de shader pour chaque type de matériau
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ShaderSet()](#ShaderSet--) | Construire l'instance de [ShaderSet](../../com.aspose.threed/shaderset) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [close()](#close--) | Supprimez cette instance et libérez tous les programmes de shaders. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | Obtient le shader de secours lorsque le shader requis n'est pas disponible |
| [getLambert()](#getLambert--) | Obtient le shader utilisé pour rendre le matériau lambert |
| [getPbr()](#getPbr--) | Obtient le shader utilisé pour rendre le matériau PBR |
| [getPhong()](#getPhong--) | Obtient le shader utilisé pour rendre le matériau phong |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(ShaderProgram value)](#setFallback-com.aspose.threed.ShaderProgram-) | Définit le shader de secours lorsque le shader requis n'est pas disponible |
| [setLambert(ShaderProgram value)](#setLambert-com.aspose.threed.ShaderProgram-) | Définit le shader utilisé pour rendre le matériau lambert |
| [setPbr(ShaderProgram value)](#setPbr-com.aspose.threed.ShaderProgram-) | Définit le shader utilisé pour rendre le matériau PBR |
| [setPhong(ShaderProgram value)](#setPhong-com.aspose.threed.ShaderProgram-) | Définit le shader utilisé pour rendre le matériau phong |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderSet() {#ShaderSet--}
```
public ShaderSet()
```


Construire l'instance de [ShaderSet](../../com.aspose.threed/shaderset)

### close() {#close--}
```
public void close()
```


Supprimez cette instance et libérez tous les programmes de shaders.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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


Obtient le shader de secours lorsque le shader requis n'est pas disponible

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the fallback shader when required shader is unavailable
### getLambert() {#getLambert--}
```
public ShaderProgram getLambert()
```


Obtient le shader utilisé pour rendre le matériau lambert

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the lambert material
### getPbr() {#getPbr--}
```
public ShaderProgram getPbr()
```


Obtient le shader utilisé pour rendre le matériau PBR

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the PBR material
### getPhong() {#getPhong--}
```
public ShaderProgram getPhong()
```


Obtient le shader utilisé pour rendre le matériau phong

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


Définit le shader de secours lorsque le shader requis n'est pas disponible

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nouvelle valeur |

### setLambert(ShaderProgram value) {#setLambert-com.aspose.threed.ShaderProgram-}
```
public void setLambert(ShaderProgram value)
```


Définit le shader utilisé pour rendre le matériau lambert

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nouvelle valeur |

### setPbr(ShaderProgram value) {#setPbr-com.aspose.threed.ShaderProgram-}
```
public void setPbr(ShaderProgram value)
```


Définit le shader utilisé pour rendre le matériau PBR

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nouvelle valeur |

### setPhong(ShaderProgram value) {#setPhong-com.aspose.threed.ShaderProgram-}
```
public void setPhong(ShaderProgram value)
```


Définit le shader utilisé pour rendre le matériau phong

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nouvelle valeur |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

