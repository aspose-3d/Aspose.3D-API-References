---
title: "PushConstant"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un utilitaire pour fournir des données au shader via une constante push."
type: docs
weight: 141
url: /fr/java/com.aspose.threed/pushconstant/
---

**Inheritance:**
java.lang.Object
```
public class PushConstant
```

Un utilitaire pour fournir des données au shader via une constante push.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PushConstant()](#PushConstant--) | Constructeur de [PushConstant](../../com.aspose.threed/pushconstant) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [commit(int stage, ICommandList commandList)](#commit-int-com.aspose.threed.ICommandList-) | Valide les données préparées dans le pipeline graphique. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(FMatrix4 mat)](#write-com.aspose.threed.FMatrix4-) | Écrire la matrice dans la constante |
| [write(FVector3 vec)](#write-com.aspose.threed.FVector3-) | Écrire un vecteur à 3 composantes dans la constante |
| [write(FVector4 vec)](#write-com.aspose.threed.FVector4-) | Écrire un vecteur à 4 composantes dans la constante |
| [write(float f)](#write-float-) | Écrire une valeur float dans la constante |
| [write(float x, float y, float z, float w)](#write-float-float-float-float-) | Écrire un vecteur à 4 composantes dans la constante |
| [write(int n)](#write-int-) | Écrire une valeur int dans la constante |
### PushConstant() {#PushConstant--}
```
public PushConstant()
```


Constructeur de [PushConstant](../../com.aspose.threed/pushconstant)

### commit(int stage, ICommandList commandList) {#commit-int-com.aspose.threed.ICommandList-}
```
public PushConstant commit(int stage, ICommandList commandList)
```


Valide les données préparées dans le pipeline graphique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| étape | int |  |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(FMatrix4 mat) {#write-com.aspose.threed.FMatrix4-}
```
public PushConstant write(FMatrix4 mat)
```


Écrire la matrice dans la constante

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mat | [FMatrix4](../../com.aspose.threed/fmatrix4) | La matrice à écrire |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector3 vec) {#write-com.aspose.threed.FVector3-}
```
public PushConstant write(FVector3 vec)
```


Écrire un vecteur à 3 composantes dans la constante

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector4 vec) {#write-com.aspose.threed.FVector4-}
```
public PushConstant write(FVector4 vec)
```


Écrire un vecteur à 4 composantes dans la constante

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float f) {#write-float-}
```
public PushConstant write(float f)
```


Écrire une valeur float dans la constante

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| f | float |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float x, float y, float z, float w) {#write-float-float-float-float-}
```
public PushConstant write(float x, float y, float z, float w)
```


Écrire un vecteur à 4 composantes dans la constante

**Parameters:**
| Paramètre | Type | Description |
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


Écrire une valeur int dans la constante

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| n | int |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
