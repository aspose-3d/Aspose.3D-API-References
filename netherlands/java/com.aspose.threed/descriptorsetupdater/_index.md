---
title: DescriptorSetUpdater
second_title: Aspose.3D for Java API-referentie
description: Deze klasse maakt het mogelijk om de  bij te werken in een ketenoperatie.
type: docs
weight: 42
url: /nl/java/com.aspose.threed/descriptorsetupdater/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class DescriptorSetUpdater implements Closeable
```

Deze klasse maakt het mogelijk om de [IDescriptorSet](../../com.aspose.threed/idescriptorset) bij te werken in een ketenoperatie.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [bind(IBuffer buffer)](#bind-com.aspose.threed.IBuffer-) | Koppel de volledige buffer aan de huidige descriptor |
| [bind(IBuffer buffer, int offset, int size)](#bind-com.aspose.threed.IBuffer-int-int-) | Koppel de buffer aan de huidige descriptorset |
| [bind(ITextureUnit texture)](#bind-com.aspose.threed.ITextureUnit-) | Koppel de texture-eenheid aan de huidige descriptorset |
| [bind(int binding, IBuffer buffer)](#bind-int-com.aspose.threed.IBuffer-) | Koppel de buffer aan de huidige descriptorset op de opgegeven bindlocatie. |
| [bind(int binding, IBuffer buffer, int offset, int size)](#bind-int-com.aspose.threed.IBuffer-int-int-) | Koppel de buffer aan de huidige descriptorset op de opgegeven bindlocatie. |
| [bind(int binding, ITextureUnit texture)](#bind-int-com.aspose.threed.ITextureUnit-) | Koppel de texture-eenheid aan de huidige descriptorset |
| [close()](#close--) | Maak de updater vrij en voer de wijzigingen door naar het hardwareapparaat. |
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


Koppel de volledige buffer aan de huidige descriptor

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) |  |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(IBuffer buffer, int offset, int size) {#bind-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(IBuffer buffer, int offset, int size)
```


Koppel de buffer aan de huidige descriptorset

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Welke buffer moet worden gebonden |
| offset | int | Offset van de te binden buffer |
| grootte | int | Grootte van de te binden buffer |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(ITextureUnit texture) {#bind-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(ITextureUnit texture)
```


Koppel de texture-eenheid aan de huidige descriptorset

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | De texture-eenheid om te binden |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer) {#bind-int-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer)
```


Koppel de buffer aan de huidige descriptorset op de opgegeven bindlocatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| binding | int | Bindinglocatie |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | De volledige buffer om te binden |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer, int offset, int size) {#bind-int-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer, int offset, int size)
```


Koppel de buffer aan de huidige descriptorset op de opgegeven bindlocatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| binding | int | Bindinglocatie |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | De buffer om te binden |
| offset | int | Offset van de te binden buffer |
| grootte | int | Grootte van de te binden buffer |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, ITextureUnit texture) {#bind-int-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(int binding, ITextureUnit texture)
```


Koppel de texture-eenheid aan de huidige descriptorset

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| binding | int | De bindinglocatie |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | De texture-eenheid om te binden |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### close() {#close--}
```
public void close()
```


Maak de updater vrij en voer de wijzigingen door naar het hardwareapparaat.

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

