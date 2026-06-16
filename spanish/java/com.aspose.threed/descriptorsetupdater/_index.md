---
title: DescriptorSetUpdater
second_title: Referencia de API de Aspose.3D para Java
description: Esta clase permite actualizar el  en una operación en cadena.
type: docs
weight: 42
url: /es/java/com.aspose.threed/descriptorsetupdater/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class DescriptorSetUpdater implements Closeable
```

Esta clase permite actualizar el [IDescriptorSet](../../com.aspose.threed/idescriptorset) en una operación en cadena.
## Métodos

| Método | Descripción |
| --- | --- |
| [bind(IBuffer buffer)](#bind-com.aspose.threed.IBuffer-) | Vincular todo el búfer al descriptor actual |
| [bind(IBuffer buffer, int offset, int size)](#bind-com.aspose.threed.IBuffer-int-int-) | Vincular el búfer al conjunto de descriptores actual |
| [bind(ITextureUnit texture)](#bind-com.aspose.threed.ITextureUnit-) | Vincular la unidad de textura al conjunto de descriptores actual |
| [bind(int binding, IBuffer buffer)](#bind-int-com.aspose.threed.IBuffer-) | Vincular el búfer al conjunto de descriptores actual en la ubicación de enlace especificada. |
| [bind(int binding, IBuffer buffer, int offset, int size)](#bind-int-com.aspose.threed.IBuffer-int-int-) | Vincular el búfer al conjunto de descriptores actual en la ubicación de enlace especificada. |
| [bind(int binding, ITextureUnit texture)](#bind-int-com.aspose.threed.ITextureUnit-) | Vincular la unidad de textura al conjunto de descriptores actual |
| [close()](#close--) | Liberar el actualizador y confirmar los cambios en el dispositivo de hardware. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### bind(IBuffer buffer) {#bind-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(IBuffer buffer)
```


Vincular todo el búfer al descriptor actual

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) |  |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(IBuffer buffer, int offset, int size) {#bind-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(IBuffer buffer, int offset, int size)
```


Vincular el búfer al conjunto de descriptores actual

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Qué búfer enlazar |
| desplazamiento | int | Desplazamiento del búfer a enlazar |
| tamaño | int | Tamaño del búfer a enlazar |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(ITextureUnit texture) {#bind-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(ITextureUnit texture)
```


Vincular la unidad de textura al conjunto de descriptores actual

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | La unidad de textura a enlazar |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer) {#bind-int-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer)
```


Vincular el búfer al conjunto de descriptores actual en la ubicación de enlace especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enlace | int | Ubicación del enlace |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Todo el búfer a enlazar |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer, int offset, int size) {#bind-int-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer, int offset, int size)
```


Vincular el búfer al conjunto de descriptores actual en la ubicación de enlace especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enlace | int | Ubicación del enlace |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | El búfer a enlazar |
| desplazamiento | int | Desplazamiento del búfer a enlazar |
| tamaño | int | Tamaño del búfer a enlazar |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, ITextureUnit texture) {#bind-int-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(int binding, ITextureUnit texture)
```


Vincular la unidad de textura al conjunto de descriptores actual

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enlace | int | La ubicación del enlace |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | La unidad de textura a enlazar |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### close() {#close--}
```
public void close()
```


Liberar el actualizador y confirmar los cambios en el dispositivo de hardware.

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

