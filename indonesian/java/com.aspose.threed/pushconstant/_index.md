---
title: PushConstant
second_title: Referensi API Aspose.3D untuk Java
description: Utilitas untuk menyediakan data ke shader melalui push constant.
type: docs
weight: 141
url: /id/java/com.aspose.threed/pushconstant/
---

**Inheritance:**
java.lang.Object
```
public class PushConstant
```

Utilitas untuk menyediakan data ke shader melalui push constant.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PushConstant()](#PushConstant--) | Konstruktor dari [PushConstant](../../com.aspose.threed/pushconstant). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [commit(int stage, ICommandList commandList)](#commit-int-com.aspose.threed.ICommandList-) | Menyimpan data yang dipersiapkan ke pipeline grafis. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(FMatrix4 mat)](#write-com.aspose.threed.FMatrix4-) | Menulis matriks ke konstanta |
| [write(FVector3 vec)](#write-com.aspose.threed.FVector3-) | Menulis vektor 3-komponen ke konstanta |
| [write(FVector4 vec)](#write-com.aspose.threed.FVector4-) | Menulis vektor 4-komponen ke konstanta |
| [write(float f)](#write-float-) | Menulis nilai float ke konstanta |
| [write(float x, float y, float z, float w)](#write-float-float-float-float-) | Menulis vektor 4-komponen ke konstanta |
| [write(int n)](#write-int-) | Menulis nilai int ke konstanta |
### PushConstant() {#PushConstant--}
```
public PushConstant()
```


Konstruktor dari [PushConstant](../../com.aspose.threed/pushconstant).

### commit(int stage, ICommandList commandList) {#commit-int-com.aspose.threed.ICommandList-}
```
public PushConstant commit(int stage, ICommandList commandList)
```


Menyimpan data yang dipersiapkan ke pipeline grafis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tahap | int |  |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
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

### write(FMatrix4 mat) {#write-com.aspose.threed.FMatrix4-}
```
public PushConstant write(FMatrix4 mat)
```


Menulis matriks ke konstanta

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mat | [FMatrix4](../../com.aspose.threed/fmatrix4) | Matriks yang akan ditulis |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector3 vec) {#write-com.aspose.threed.FVector3-}
```
public PushConstant write(FVector3 vec)
```


Menulis vektor 3-komponen ke konstanta

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector4 vec) {#write-com.aspose.threed.FVector4-}
```
public PushConstant write(FVector4 vec)
```


Menulis vektor 4-komponen ke konstanta

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float f) {#write-float-}
```
public PushConstant write(float f)
```


Menulis nilai float ke konstanta

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| f | float |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float x, float y, float z, float w) {#write-float-float-float-float-}
```
public PushConstant write(float x, float y, float z, float w)
```


Menulis vektor 4-komponen ke konstanta

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| z | float |  |
| w | float |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(int n) {#write-int-}
```
public PushConstant write(int n)
```


Menulis nilai int ke konstanta

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| n | int |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
