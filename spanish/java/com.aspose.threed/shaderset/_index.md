---
title: ShaderSet
second_title: Referencia de API de Aspose.3D para Java
description: Programas de shader para cada tipo de material.
type: docs
weight: 166
url: /es/java/com.aspose.threed/shaderset/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class ShaderSet implements Closeable
```

Programas de shader para cada tipo de material.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ShaderSet()](#ShaderSet--) | Construye la instancia de [ShaderSet](../../com.aspose.threed/shaderset) |
## Métodos

| Método | Descripción |
| --- | --- |
| [close()](#close--) | Descarta esta instancia y libera todos los programas de sombreado. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | Obtiene el shader de reserva cuando el shader requerido no está disponible. |
| [getLambert()](#getLambert--) | Obtiene el shader que se usa para renderizar el material lambert. |
| [getPbr()](#getPbr--) | Obtiene el shader que se usa para renderizar el material PBR. |
| [getPhong()](#getPhong--) | Obtiene el shader que se usa para renderizar el material phong. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(ShaderProgram value)](#setFallback-com.aspose.threed.ShaderProgram-) | Establece el shader de reserva cuando el shader requerido no está disponible. |
| [setLambert(ShaderProgram value)](#setLambert-com.aspose.threed.ShaderProgram-) | Establece el shader que se usa para renderizar el material lambert. |
| [setPbr(ShaderProgram value)](#setPbr-com.aspose.threed.ShaderProgram-) | Establece el shader que se usa para renderizar el material PBR. |
| [setPhong(ShaderProgram value)](#setPhong-com.aspose.threed.ShaderProgram-) | Establece el shader que se usa para renderizar el material phong. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderSet() {#ShaderSet--}
```
public ShaderSet()
```


Construye la instancia de [ShaderSet](../../com.aspose.threed/shaderset)

### close() {#close--}
```
public void close()
```


Descarta esta instancia y libera todos los programas de sombreado.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Obtiene el shader de reserva cuando el shader requerido no está disponible.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the fallback shader when required shader is unavailable
### getLambert() {#getLambert--}
```
public ShaderProgram getLambert()
```


Obtiene el shader que se usa para renderizar el material lambert.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the lambert material
### getPbr() {#getPbr--}
```
public ShaderProgram getPbr()
```


Obtiene el shader que se usa para renderizar el material PBR.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the PBR material
### getPhong() {#getPhong--}
```
public ShaderProgram getPhong()
```


Obtiene el shader que se usa para renderizar el material phong.

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


Establece el shader de reserva cuando el shader requerido no está disponible.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nuevo valor |

### setLambert(ShaderProgram value) {#setLambert-com.aspose.threed.ShaderProgram-}
```
public void setLambert(ShaderProgram value)
```


Establece el shader que se usa para renderizar el material lambert.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nuevo valor |

### setPbr(ShaderProgram value) {#setPbr-com.aspose.threed.ShaderProgram-}
```
public void setPbr(ShaderProgram value)
```


Establece el shader que se usa para renderizar el material PBR.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nuevo valor |

### setPhong(ShaderProgram value) {#setPhong-com.aspose.threed.ShaderProgram-}
```
public void setPhong(ShaderProgram value)
```


Establece el shader que se usa para renderizar el material phong.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nuevo valor |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

