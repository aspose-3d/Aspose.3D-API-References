---
title: TextureSlot
second_title: Aspose.3D for Java API 레퍼런스
description: 텍스처 슬롯은  에서 재질 인스턴스를 통해 열거할 수 있습니다.
type: docs
weight: 188
url: /ko/java/com.aspose.threed/textureslot/
---

**Inheritance:**
java.lang.Object
```
public class TextureSlot
```

[Material](../../com.aspose.threed/material)의 텍스처 슬롯은 재질 인스턴스를 통해 열거할 수 있습니다. **Example:**

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
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSlotName()](#getSlotName--) | 이 텍스처가 바인딩될 위치를 나타내는 슬롯 이름입니다. |
| [getTexture()](#getTexture--) | 재질에 바인딩될 텍스처입니다. |
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
| 매개변수 | 형식 | 설명 |
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


이 텍스처가 바인딩될 위치를 나타내는 슬롯 이름입니다.

**Returns:**
java.lang.String - 이 텍스처가 바인딩될 위치를 나타내는 슬롯 이름입니다.
### getTexture() {#getTexture--}
```
public TextureBase getTexture()
```


재질에 바인딩될 텍스처입니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

