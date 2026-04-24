---
title: TextureSlot
second_title: Referensi API Aspose.3D untuk Java
description: Slot tekstur dalam  dapat dienumerasi melalui instance material.
type: docs
weight: 188
url: /id/java/com.aspose.threed/textureslot/
---

**Inheritance:**
java.lang.Object
```
public class TextureSlot
```

Slot tekstur dalam [Material](../../com.aspose.threed/material), dapat dienumerasi melalui instance material. **Contoh:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     for(var slot : mat)
     {
         System.out.printf("Texture slot %s = %s", slot.getSlotName(), slot.getTexture());
     }
```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSlotName()](#getSlotName--) | Nama slot yang menunjukkan ke mana tekstur ini akan terikat. |
| [getTexture()](#getTexture--) | Tekstur yang akan terikat ke material. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getSlotName() {#getSlotName--}
```
public String getSlotName()
```


Nama slot yang menunjukkan ke mana tekstur ini akan terikat.

**Returns:**
java.lang.String - Nama slot yang menunjukkan ke mana tekstur ini akan terikat.
### getTexture() {#getTexture--}
```
public TextureBase getTexture()
```


Tekstur yang akan terikat ke material.

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - The texture that will be bounded to the material.
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

