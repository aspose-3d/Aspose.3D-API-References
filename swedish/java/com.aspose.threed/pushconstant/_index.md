---
title: PushConstant
second_title: Aspose.3D for Java API-referens
description: Ett verktyg för att tillhandahålla data till shadern via push‑konstant.
type: docs
weight: 141
url: /sv/java/com.aspose.threed/pushconstant/
---

**Inheritance:**
java.lang.Object
```
public class PushConstant
```

Ett verktyg för att tillhandahålla data till shadern via push‑konstant.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PushConstant()](#PushConstant--) | Konstruktor för [PushConstant](../../com.aspose.threed/pushconstant) |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [commit(int stage, ICommandList commandList)](#commit-int-com.aspose.threed.ICommandList-) | Skicka förberedd data till grafikpipeline. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(FMatrix4 mat)](#write-com.aspose.threed.FMatrix4-) | Skriv matrisen till konstanten |
| [write(FVector3 vec)](#write-com.aspose.threed.FVector3-) | Skriv en 3-komponentsvektor till konstanten |
| [write(FVector4 vec)](#write-com.aspose.threed.FVector4-) | Skriv en 4-komponentsvektor till konstanten |
| [write(float f)](#write-float-) | Skriv ett flyttalsvärde till konstanten |
| [write(float x, float y, float z, float w)](#write-float-float-float-float-) | Skriv en 4-komponentsvektor till konstanten |
| [write(int n)](#write-int-) | Skriv ett heltalsvärde till konstanten |
### PushConstant() {#PushConstant--}
```
public PushConstant()
```


Konstruktor för [PushConstant](../../com.aspose.threed/pushconstant)

### commit(int stage, ICommandList commandList) {#commit-int-com.aspose.threed.ICommandList-}
```
public PushConstant commit(int stage, ICommandList commandList)
```


Skicka förberedd data till grafikpipeline.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| steg | int |  |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
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

### write(FMatrix4 mat) {#write-com.aspose.threed.FMatrix4-}
```
public PushConstant write(FMatrix4 mat)
```


Skriv matrisen till konstanten

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mat | [FMatrix4](../../com.aspose.threed/fmatrix4) | Matrisen att skriva |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector3 vec) {#write-com.aspose.threed.FVector3-}
```
public PushConstant write(FVector3 vec)
```


Skriv en 3-komponentsvektor till konstanten

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector4 vec) {#write-com.aspose.threed.FVector4-}
```
public PushConstant write(FVector4 vec)
```


Skriv en 4-komponentsvektor till konstanten

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float f) {#write-float-}
```
public PushConstant write(float f)
```


Skriv ett flyttalsvärde till konstanten

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| f | float |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float x, float y, float z, float w) {#write-float-float-float-float-}
```
public PushConstant write(float x, float y, float z, float w)
```


Skriv en 4-komponentsvektor till konstanten

**Parameters:**
| Parameter | Typ | Beskrivning |
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


Skriv ett heltalsvärde till konstanten

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| n | int |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
