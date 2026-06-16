---
title: "TextureSlot"
second_title: "Aspose.3D for Java API Reference"
description: "Η θέση υφής στο  μπορεί να απαριθμηθεί μέσω του στιγμιοτύπου υλικού."
type: docs
weight: 188
url: /el/java/com.aspose.threed/textureslot/
---

**Inheritance:**
java.lang.Object
```
public class TextureSlot
```

Η θέση υφής στο [Material](../../com.aspose.threed/material), μπορεί να απαριθμηθεί μέσω του στιγμιοτύπου υλικού. **Παράδειγμα:**

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
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSlotName()](#getSlotName--) | Το όνομα της θέσης που υποδεικνύει πού θα δεσμευτεί αυτή η υφή. |
| [getTexture()](#getTexture--) | Η υφή που θα δεσμευτεί στο υλικό. |
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
| Παράμετρος | Τύπος | Περιγραφή |
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


Το όνομα της θέσης που υποδεικνύει πού θα δεσμευτεί αυτή η υφή.

**Returns:**
java.lang.String - Το όνομα της θέσης που υποδεικνύει πού θα δεσμευτεί αυτή η υφή.
### getTexture() {#getTexture--}
```
public TextureBase getTexture()
```


Η υφή που θα δεσμευτεί στο υλικό.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

