---
title: "StencilState"
second_title: "Référence d'API Aspose.3D pour Java"
description: "États de pochoir par face."
type: docs
weight: 175
url: /fr/java/com.aspose.threed/stencilstate/
---

**Inheritance:**
java.lang.Object
```
public class StencilState
```

États de pochoir par face.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à un objet spécifié. |
| [getClass()](#getClass--) |  |
| [getCompare()](#getCompare--) | Obtient la fonction de comparaison utilisée dans le test de pochoir |
| [getDepthFailAction()](#getDepthFailAction--) | Obtient l'action de pochoir lorsque le test de pochoir réussit mais que le test de profondeur échoue. |
| [getFailAction()](#getFailAction--) | Obtient l'action de pochoir lorsque le test de pochoir échoue. |
| [getPassAction()](#getPassAction--) | Obtient l'action de pochoir lorsque le test de pochoir et le test de profondeur réussissent. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompare(CompareFunction value)](#setCompare-com.aspose.threed.CompareFunction-) | Définit la fonction de comparaison utilisée dans le test de pochoir |
| [setDepthFailAction(StencilAction value)](#setDepthFailAction-com.aspose.threed.StencilAction-) | Définit l'action de pochoir lorsque le test de pochoir réussit mais que le test de profondeur échoue. |
| [setFailAction(StencilAction value)](#setFailAction-com.aspose.threed.StencilAction-) | Définit l'action de pochoir lorsque le test de pochoir échoue. |
| [setPassAction(StencilAction value)](#setPassAction-com.aspose.threed.StencilAction-) | Définit l'action de pochoir lorsque le test de pochoir et le test de profondeur réussissent. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à un objet spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompare() {#getCompare--}
```
public CompareFunction getCompare()
```


Obtient la fonction de comparaison utilisée dans le test de pochoir

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in stencil test
### getDepthFailAction() {#getDepthFailAction--}
```
public StencilAction getDepthFailAction()
```


Obtient l'action de pochoir lorsque le test de pochoir réussit mais que le test de profondeur échoue.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test pass but depth test fails.
### getFailAction() {#getFailAction--}
```
public StencilAction getFailAction()
```


Obtient l'action de pochoir lorsque le test de pochoir échoue.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test fails.
### getPassAction() {#getPassAction--}
```
public StencilAction getPassAction()
```


Obtient l'action de pochoir lorsque le test de pochoir et le test de profondeur réussissent.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when both stencil test and depth test passes.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette instance.

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




### setCompare(CompareFunction value) {#setCompare-com.aspose.threed.CompareFunction-}
```
public void setCompare(CompareFunction value)
```


Définit la fonction de comparaison utilisée dans le test de pochoir

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Nouvelle valeur |

### setDepthFailAction(StencilAction value) {#setDepthFailAction-com.aspose.threed.StencilAction-}
```
public void setDepthFailAction(StencilAction value)
```


Définit l'action de pochoir lorsque le test de pochoir réussit mais que le test de profondeur échoue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nouvelle valeur |

### setFailAction(StencilAction value) {#setFailAction-com.aspose.threed.StencilAction-}
```
public void setFailAction(StencilAction value)
```


Définit l'action de pochoir lorsque le test de pochoir échoue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nouvelle valeur |

### setPassAction(StencilAction value) {#setPassAction-com.aspose.threed.StencilAction-}
```
public void setPassAction(StencilAction value)
```


Définit l'action de pochoir lorsque le test de pochoir et le test de profondeur réussissent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nouvelle valeur |

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

