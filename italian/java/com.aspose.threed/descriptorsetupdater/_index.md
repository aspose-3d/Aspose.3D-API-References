---
title: DescriptorSetUpdater
second_title: Aspose.3D for Java API Reference
description: Questa classe consente di aggiornare il  in un'operazione a catena.
type: docs
weight: 42
url: /it/java/com.aspose.threed/descriptorsetupdater/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class DescriptorSetUpdater implements Closeable
```

Questa classe consente di aggiornare il [IDescriptorSet](../../com.aspose.threed/idescriptorset) in un'operazione a catena.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [bind(IBuffer buffer)](#bind-com.aspose.threed.IBuffer-) | Associa l'intero buffer al descrittore corrente |
| [bind(IBuffer buffer, int offset, int size)](#bind-com.aspose.threed.IBuffer-int-int-) | Associa il buffer al set di descrittori corrente |
| [bind(ITextureUnit texture)](#bind-com.aspose.threed.ITextureUnit-) | Associa l'unità di texture al set di descrittori corrente |
| [bind(int binding, IBuffer buffer)](#bind-int-com.aspose.threed.IBuffer-) | Associa il buffer al set di descrittori corrente nella posizione di binding specificata. |
| [bind(int binding, IBuffer buffer, int offset, int size)](#bind-int-com.aspose.threed.IBuffer-int-int-) | Associa il buffer al set di descrittori corrente nella posizione di binding specificata. |
| [bind(int binding, ITextureUnit texture)](#bind-int-com.aspose.threed.ITextureUnit-) | Associa l'unità di texture al set di descrittori corrente |
| [close()](#close--) | Rilascia l'aggiornatore e conferma le modifiche al dispositivo hardware. |
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


Associa l'intero buffer al descrittore corrente

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) |  |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(IBuffer buffer, int offset, int size) {#bind-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(IBuffer buffer, int offset, int size)
```


Associa il buffer al set di descrittori corrente

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Quale buffer collegare |
| offset | int | Offset del buffer da collegare |
| dimensione | int | Dimensione del buffer da collegare |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(ITextureUnit texture) {#bind-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(ITextureUnit texture)
```


Associa l'unità di texture al set di descrittori corrente

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | L'unità di texture da collegare |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer) {#bind-int-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer)
```


Associa il buffer al set di descrittori corrente nella posizione di binding specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| collegamento | int | Posizione di collegamento |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | L'intero buffer da collegare |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer, int offset, int size) {#bind-int-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer, int offset, int size)
```


Associa il buffer al set di descrittori corrente nella posizione di binding specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| collegamento | int | Posizione di collegamento |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Il buffer da collegare |
| offset | int | Offset del buffer da collegare |
| dimensione | int | Dimensione del buffer da collegare |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, ITextureUnit texture) {#bind-int-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(int binding, ITextureUnit texture)
```


Associa l'unità di texture al set di descrittori corrente

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| collegamento | int | La posizione di collegamento |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | L'unità di texture da collegare |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### close() {#close--}
```
public void close()
```


Rilascia l'aggiornatore e conferma le modifiche al dispositivo hardware.

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

