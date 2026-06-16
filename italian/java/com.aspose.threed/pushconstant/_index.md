---
title: "PushConstant"
second_title: "Aspose.3D for Java API Reference"
description: "Una utility per fornire dati allo shader tramite costante push."
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
| [PushConstant()](#PushConstant--) | Costruttore di [PushConstant](../../com.aspose.threed/pushconstant) |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [commit(int stage, ICommandList commandList)](#commit-int-com.aspose.threed.ICommandList-) | Invia i dati preparati al pipeline grafico. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(FMatrix4 mat)](#write-com.aspose.threed.FMatrix4-) | Scrivi la matrice nella costante |
| [write(FVector3 vec)](#write-com.aspose.threed.FVector3-) | Scrivi un vettore a 3 componenti nella costante |
| [write(FVector4 vec)](#write-com.aspose.threed.FVector4-) | Scrivi un vettore a 4 componenti nella costante |
| [write(float f)](#write-float-) | Scrivi un valore float nella costante |
| [write(float x, float y, float z, float w)](#write-float-float-float-float-) | Scrivi un vettore a 4 componenti nella costante |
| [write(int n)](#write-int-) | Scrivi un valore int nella costante |
### PushConstant() {#PushConstant--}
```
public PushConstant()
```


Costruttore di [PushConstant](../../com.aspose.threed/pushconstant)

### commit(int stage, ICommandList commandList) {#commit-int-com.aspose.threed.ICommandList-}
```
public PushConstant commit(int stage, ICommandList commandList)
```


Invia i dati preparati al pipeline grafico.

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


Scrivi la matrice nella costante

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mat | [FMatrix4](../../com.aspose.threed/fmatrix4) | La matrice da scrivere |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector3 vec) {#write-com.aspose.threed.FVector3-}
```
public PushConstant write(FVector3 vec)
```


Scrivi un vettore a 3 componenti nella costante

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


Scrivi un vettore a 4 componenti nella costante

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


Scrivi un valore float nella costante

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


Scrivi un vettore a 4 componenti nella costante

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


Scrivi un valore int nella costante

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| n | int |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
