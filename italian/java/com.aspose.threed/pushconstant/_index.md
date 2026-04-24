---
title: PushConstant
second_title: Aspose.3D for Java API Reference
description: Una utility per fornire dati allo shader tramite costante push.
type: docs
weight: 141
url: /it/java/com.aspose.threed/pushconstant/
---

**Inheritance:**
java.lang.Object
```
public class PushConstant
```

Una utility per fornire dati allo shader tramite costante push.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PushConstant()](#PushConstant--) | Constructor of the [PushConstant](../../com.aspose.threed/pushconstant) |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [commit(int stage, ICommandList commandList)](#commit-int-com.aspose.threed.ICommandList-) | Commit prepared data to graphics pipeline. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(FMatrix4 mat)](#write-com.aspose.threed.FMatrix4-) | Write the matrix to the constant |
| [write(FVector3 vec)](#write-com.aspose.threed.FVector3-) | Write a 3-component vector to the constant |
| [write(FVector4 vec)](#write-com.aspose.threed.FVector4-) | Write a 4-component vector to the constant |
| [write(float f)](#write-float-) | Write a float value to the constant |
| [write(float x, float y, float z, float w)](#write-float-float-float-float-) | Write a 4-component vector to the constant |
| [write(int n)](#write-int-) | Write a int value to the constant |
### PushConstant() {#PushConstant--}
```
public PushConstant()
```


Constructor of the [PushConstant](../../com.aspose.threed/pushconstant)

### commit(int stage, ICommandList commandList) {#commit-int-com.aspose.threed.ICommandList-}
```
public PushConstant commit(int stage, ICommandList commandList)
```


Commit prepared data to graphics pipeline.

**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(FMatrix4 mat) {#write-com.aspose.threed.FMatrix4-}
```
public PushConstant write(FMatrix4 mat)
```


Write the matrix to the constant

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mat | [FMatrix4](../../com.aspose.threed/fmatrix4) | The matrix to write |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector3 vec) {#write-com.aspose.threed.FVector3-}
```
public PushConstant write(FVector3 vec)
```


Write a 3-component vector to the constant

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector4 vec) {#write-com.aspose.threed.FVector4-}
```
public PushConstant write(FVector4 vec)
```


Write a 4-component vector to the constant

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float f) {#write-float-}
```
public PushConstant write(float f)
```


Write a float value to the constant

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| f | float |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float x, float y, float z, float w) {#write-float-float-float-float-}
```
public PushConstant write(float x, float y, float z, float w)
```


Write a 4-component vector to the constant

**Parameters:**
| Parametro | Tipo | Descrizione |
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


Write a int value to the constant

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| n | int |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
