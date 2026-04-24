---
title: DescriptorSetUpdater
second_title: Referensi API Aspose.3D untuk Java
description: Kelas ini memungkinkan memperbarui dalam operasi berantai.
type: docs
weight: 42
url: /id/java/com.aspose.threed/descriptorsetupdater/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class DescriptorSetUpdater implements Closeable
```

Kelas ini memungkinkan memperbarui [IDescriptorSet](../../com.aspose.threed/idescriptorset) dalam operasi berantai.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [bind(IBuffer buffer)](#bind-com.aspose.threed.IBuffer-) | Mengikat seluruh buffer ke deskriptor saat ini |
| [bind(IBuffer buffer, int offset, int size)](#bind-com.aspose.threed.IBuffer-int-int-) | Mengikat buffer ke set deskriptor saat ini |
| [bind(ITextureUnit texture)](#bind-com.aspose.threed.ITextureUnit-) | Mengikat unit tekstur ke set deskriptor saat ini |
| [bind(int binding, IBuffer buffer)](#bind-int-com.aspose.threed.IBuffer-) | Mengikat buffer ke set deskriptor saat ini pada lokasi pengikatan yang ditentukan. |
| [bind(int binding, IBuffer buffer, int offset, int size)](#bind-int-com.aspose.threed.IBuffer-int-int-) | Mengikat buffer ke set deskriptor saat ini pada lokasi pengikatan yang ditentukan. |
| [bind(int binding, ITextureUnit texture)](#bind-int-com.aspose.threed.ITextureUnit-) | Mengikat unit tekstur ke set deskriptor saat ini |
| [close()](#close--) | Membuang updater dan mengkomit perubahan ke perangkat keras. |
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


Mengikat seluruh buffer ke deskriptor saat ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) |  |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(IBuffer buffer, int offset, int size) {#bind-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(IBuffer buffer, int offset, int size)
```


Mengikat buffer ke set deskriptor saat ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Buffer mana yang akan diikat |
| offset | int | Offset buffer yang akan diikat |
| ukuran | int | Ukuran buffer yang akan diikat |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(ITextureUnit texture) {#bind-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(ITextureUnit texture)
```


Mengikat unit tekstur ke set deskriptor saat ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | Unit tekstur yang akan diikat |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer) {#bind-int-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer)
```


Mengikat buffer ke set deskriptor saat ini pada lokasi pengikatan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pengikatan | int | Lokasi pengikatan |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Seluruh buffer yang akan diikat |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer, int offset, int size) {#bind-int-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer, int offset, int size)
```


Mengikat buffer ke set deskriptor saat ini pada lokasi pengikatan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pengikatan | int | Lokasi pengikatan |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Buffer yang akan diikat |
| offset | int | Offset buffer yang akan diikat |
| ukuran | int | Ukuran buffer yang akan diikat |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, ITextureUnit texture) {#bind-int-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(int binding, ITextureUnit texture)
```


Mengikat unit tekstur ke set deskriptor saat ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pengikatan | int | Lokasi pengikatan |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | Unit tekstur yang akan diikat |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### close() {#close--}
```
public void close()
```


Membuang updater dan mengkomit perubahan ke perangkat keras.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

