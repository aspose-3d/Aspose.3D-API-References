---
title: PushConstant
second_title: Referencia de API de Aspose.3D para Java
description: Una utilidad para proporcionar datos al shader mediante una constante push.
type: docs
weight: 141
url: /es/java/com.aspose.threed/pushconstant/
---

**Inheritance:**
java.lang.Object
```
public class PushConstant
```

Una utilidad para proporcionar datos al shader mediante una constante push.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PushConstant()](#PushConstant--) | Constructor de [PushConstant](../../com.aspose.threed/pushconstant) |
## Métodos

| Método | Descripción |
| --- | --- |
| [commit(int stage, ICommandList commandList)](#commit-int-com.aspose.threed.ICommandList-) | Confirma los datos preparados al pipeline gráfico. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(FMatrix4 mat)](#write-com.aspose.threed.FMatrix4-) | Escribe la matriz en la constante |
| [write(FVector3 vec)](#write-com.aspose.threed.FVector3-) | Escribe un vector de 3 componentes en la constante |
| [write(FVector4 vec)](#write-com.aspose.threed.FVector4-) | Escribe un vector de 4 componentes en la constante |
| [write(float f)](#write-float-) | Escribe un valor float en la constante |
| [write(float x, float y, float z, float w)](#write-float-float-float-float-) | Escribe un vector de 4 componentes en la constante |
| [write(int n)](#write-int-) | Escribe un valor int en la constante |
### PushConstant() {#PushConstant--}
```
public PushConstant()
```


Constructor de [PushConstant](../../com.aspose.threed/pushconstant)

### commit(int stage, ICommandList commandList) {#commit-int-com.aspose.threed.ICommandList-}
```
public PushConstant commit(int stage, ICommandList commandList)
```


Confirma los datos preparados al pipeline gráfico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| etapa | int |  |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(FMatrix4 mat) {#write-com.aspose.threed.FMatrix4-}
```
public PushConstant write(FMatrix4 mat)
```


Escribe la matriz en la constante

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mat | [FMatrix4](../../com.aspose.threed/fmatrix4) | La matriz a escribir |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector3 vec) {#write-com.aspose.threed.FVector3-}
```
public PushConstant write(FVector3 vec)
```


Escribe un vector de 3 componentes en la constante

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector4 vec) {#write-com.aspose.threed.FVector4-}
```
public PushConstant write(FVector4 vec)
```


Escribe un vector de 4 componentes en la constante

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float f) {#write-float-}
```
public PushConstant write(float f)
```


Escribe un valor float en la constante

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| f | float |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float x, float y, float z, float w) {#write-float-float-float-float-}
```
public PushConstant write(float x, float y, float z, float w)
```


Escribe un vector de 4 componentes en la constante

**Parameters:**
| Parámetro | Tipo | Descripción |
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


Escribe un valor int en la constante

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| n | int |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
