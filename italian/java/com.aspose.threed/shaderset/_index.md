---
title: ShaderSet
second_title: Aspose.3D for Java API Reference
description: Programmi shader per ogni tipo di materiale
type: docs
weight: 166
url: /it/java/com.aspose.threed/shaderset/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class ShaderSet implements Closeable
```

Programmi shader per ogni tipo di materiale
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ShaderSet()](#ShaderSet--) | Crea l'istanza di [ShaderSet](../../com.aspose.threed/shaderset) |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close()](#close--) | Rilascia questa istanza e libera tutti i programmi shader. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | Ottiene lo shader di fallback quando lo shader richiesto non è disponibile |
| [getLambert()](#getLambert--) | Ottiene lo shader usato per renderizzare il materiale lambert |
| [getPbr()](#getPbr--) | Ottiene lo shader usato per renderizzare il materiale PBR |
| [getPhong()](#getPhong--) | Ottiene lo shader usato per renderizzare il materiale phong |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(ShaderProgram value)](#setFallback-com.aspose.threed.ShaderProgram-) | Imposta lo shader di fallback quando lo shader richiesto non è disponibile |
| [setLambert(ShaderProgram value)](#setLambert-com.aspose.threed.ShaderProgram-) | Imposta lo shader usato per renderizzare il materiale lambert |
| [setPbr(ShaderProgram value)](#setPbr-com.aspose.threed.ShaderProgram-) | Imposta lo shader usato per renderizzare il materiale PBR |
| [setPhong(ShaderProgram value)](#setPhong-com.aspose.threed.ShaderProgram-) | Imposta lo shader usato per renderizzare il materiale phong |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderSet() {#ShaderSet--}
```
public ShaderSet()
```


Crea l'istanza di [ShaderSet](../../com.aspose.threed/shaderset)

### close() {#close--}
```
public void close()
```


Rilascia questa istanza e libera tutti i programmi shader.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Ottiene lo shader di fallback quando lo shader richiesto non è disponibile

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the fallback shader when required shader is unavailable
### getLambert() {#getLambert--}
```
public ShaderProgram getLambert()
```


Ottiene lo shader usato per renderizzare il materiale lambert

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the lambert material
### getPbr() {#getPbr--}
```
public ShaderProgram getPbr()
```


Ottiene lo shader usato per renderizzare il materiale PBR

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the PBR material
### getPhong() {#getPhong--}
```
public ShaderProgram getPhong()
```


Ottiene lo shader usato per renderizzare il materiale phong

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


Imposta lo shader di fallback quando lo shader richiesto non è disponibile

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nuovo valore |

### setLambert(ShaderProgram value) {#setLambert-com.aspose.threed.ShaderProgram-}
```
public void setLambert(ShaderProgram value)
```


Imposta lo shader usato per renderizzare il materiale lambert

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nuovo valore |

### setPbr(ShaderProgram value) {#setPbr-com.aspose.threed.ShaderProgram-}
```
public void setPbr(ShaderProgram value)
```


Imposta lo shader usato per renderizzare il materiale PBR

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nuovo valore |

### setPhong(ShaderProgram value) {#setPhong-com.aspose.threed.ShaderProgram-}
```
public void setPhong(ShaderProgram value)
```


Imposta lo shader usato per renderizzare il materiale phong

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nuovo valore |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

