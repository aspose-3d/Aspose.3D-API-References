---
title: TextureSlot
second_title: Aspose.3D for Java API Reference
description: Texture slot को सामग्री उदाहरण के माध्यम से गिना जा सकता है।
type: docs
weight: 188
url: /hi/java/com.aspose.threed/textureslot/
---

**Inheritance:**
java.lang.Object
```
public class TextureSlot
```

Texture slot को [Material](../../com.aspose.threed/material) में, सामग्री उदाहरण के माध्यम से गिना जा सकता है। **Example:**

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
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSlotName()](#getSlotName--) | स्लॉट का नाम जो दर्शाता है कि यह टेक्सचर कहाँ बंधेगा। |
| [getTexture()](#getTexture--) | टेक्सचर जो सामग्री से बंधेगा। |
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
| Parameter | Type | विवरण |
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


स्लॉट का नाम जो दर्शाता है कि यह टेक्सचर कहाँ बंधेगा।

**Returns:**
java.lang.String - स्लॉट का नाम जो दर्शाता है कि यह टेक्सचर कहाँ बंधेगा।
### getTexture() {#getTexture--}
```
public TextureBase getTexture()
```


टेक्सचर जो सामग्री से बंधेगा।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

