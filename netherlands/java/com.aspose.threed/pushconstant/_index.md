---
title: PushConstant
second_title: Aspose.3D for Java API-referentie
description: Een hulpprogramma om gegevens aan de shader te leveren via een push-constante.
type: docs
weight: 141
url: /nl/java/com.aspose.threed/pushconstant/
---

**Inheritance:**
java.lang.Object
```
public class PushConstant
```

Een hulpprogramma om gegevens aan de shader te leveren via een push-constante.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PushConstant()](#PushConstant--) | Constructor van de [PushConstant](../../com.aspose.threed/pushconstant) |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [commit(int stage, ICommandList commandList)](#commit-int-com.aspose.threed.ICommandList-) | Commit voorbereide gegevens naar de grafische pijplijn. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(FMatrix4 mat)](#write-com.aspose.threed.FMatrix4-) | Schrijf de matrix naar de constante. |
| [write(FVector3 vec)](#write-com.aspose.threed.FVector3-) | Schrijf een 3-componenten vector naar de constante. |
| [write(FVector4 vec)](#write-com.aspose.threed.FVector4-) | Schrijf een 4-componenten vector naar de constante. |
| [write(float f)](#write-float-) | Schrijf een float-waarde naar de constante. |
| [write(float x, float y, float z, float w)](#write-float-float-float-float-) | Schrijf een 4-componenten vector naar de constante. |
| [write(int n)](#write-int-) | Schrijf een int-waarde naar de constante. |
### PushConstant() {#PushConstant--}
```
public PushConstant()
```


Constructor van de [PushConstant](../../com.aspose.threed/pushconstant)

### commit(int stage, ICommandList commandList) {#commit-int-com.aspose.threed.ICommandList-}
```
public PushConstant commit(int stage, ICommandList commandList)
```


Commit voorbereide gegevens naar de grafische pijplijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fase | int |  |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
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

### write(FMatrix4 mat) {#write-com.aspose.threed.FMatrix4-}
```
public PushConstant write(FMatrix4 mat)
```


Schrijf de matrix naar de constante.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mat | [FMatrix4](../../com.aspose.threed/fmatrix4) | De matrix om te schrijven |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector3 vec) {#write-com.aspose.threed.FVector3-}
```
public PushConstant write(FVector3 vec)
```


Schrijf een 3-componenten vector naar de constante.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector4 vec) {#write-com.aspose.threed.FVector4-}
```
public PushConstant write(FVector4 vec)
```


Schrijf een 4-componenten vector naar de constante.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float f) {#write-float-}
```
public PushConstant write(float f)
```


Schrijf een float-waarde naar de constante.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| f | float |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float x, float y, float z, float w) {#write-float-float-float-float-}
```
public PushConstant write(float x, float y, float z, float w)
```


Schrijf een 4-componenten vector naar de constante.

**Parameters:**
| Parameter | Type | Beschrijving |
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


Schrijf een int-waarde naar de constante.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| n | int |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
