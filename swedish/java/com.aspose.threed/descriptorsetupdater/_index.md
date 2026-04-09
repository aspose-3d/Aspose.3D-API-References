---
title: DescriptorSetUpdater
second_title: Aspose.3D for Java API-referens
description: Denna klass tillåter att uppdatera  i en kedjeoperation.
type: docs
weight: 42
url: /sv/java/com.aspose.threed/descriptorsetupdater/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class DescriptorSetUpdater implements Closeable
```

Denna klass tillåter att uppdatera [IDescriptorSet](../../com.aspose.threed/idescriptorset) i en kedjeoperation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [bind(IBuffer buffer)](#bind-com.aspose.threed.IBuffer-) | Binda hela bufferten till aktuellt deskriptor |
| [bind(IBuffer buffer, int offset, int size)](#bind-com.aspose.threed.IBuffer-int-int-) | Binda bufferten till aktuellt descriptor set |
| [bind(ITextureUnit texture)](#bind-com.aspose.threed.ITextureUnit-) | Binda texturenheten till aktuellt descriptor set |
| [bind(int binding, IBuffer buffer)](#bind-int-com.aspose.threed.IBuffer-) | Binda bufferten till aktuellt descriptor set vid angiven bindningsplats. |
| [bind(int binding, IBuffer buffer, int offset, int size)](#bind-int-com.aspose.threed.IBuffer-int-int-) | Binda bufferten till aktuellt descriptor set vid angiven bindningsplats. |
| [bind(int binding, ITextureUnit texture)](#bind-int-com.aspose.threed.ITextureUnit-) | Binda texturenheten till aktuellt descriptor set |
| [close()](#close--) | Disposera uppdateraren och verkställ ändringarna på hårdvaruenheten. |
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


Binda hela bufferten till aktuellt deskriptor

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) |  |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(IBuffer buffer, int offset, int size) {#bind-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(IBuffer buffer, int offset, int size)
```


Binda bufferten till aktuellt descriptor set

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Vilken buffert som ska bindas |
| offset | int | Förskjutning för bufferten som ska bindas |
| storlek | int | Storlek på bufferten som ska bindas |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(ITextureUnit texture) {#bind-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(ITextureUnit texture)
```


Binda texturenheten till aktuellt descriptor set

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | Texturenheten som ska bindas |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer) {#bind-int-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer)
```


Binda bufferten till aktuellt descriptor set vid angiven bindningsplats.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bindning | int | Bindningsplats |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Hela bufferten som ska bindas |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer, int offset, int size) {#bind-int-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer, int offset, int size)
```


Binda bufferten till aktuellt descriptor set vid angiven bindningsplats.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bindning | int | Bindningsplats |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Bufferten som ska bindas |
| offset | int | Förskjutning för bufferten som ska bindas |
| storlek | int | Storlek på bufferten som ska bindas |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, ITextureUnit texture) {#bind-int-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(int binding, ITextureUnit texture)
```


Binda texturenheten till aktuellt descriptor set

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bindning | int | Bindningsplatsen |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | Texturenheten som ska bindas |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### close() {#close--}
```
public void close()
```


Disposera uppdateraren och verkställ ändringarna på hårdvaruenheten.

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

