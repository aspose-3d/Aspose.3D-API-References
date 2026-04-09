---
title: StencilState
second_title: Aspose.3D for Java API Reference
description: Stati stencil per faccia.
type: docs
weight: 175
url: /it/java/com.aspose.threed/stencilstate/
---

**Inheritance:**
java.lang.Object
```
public class StencilState
```

Stati stencil per faccia.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un oggetto specificato. |
| [getClass()](#getClass--) |  |
| [getCompare()](#getCompare--) | Ottiene la funzione di confronto utilizzata nel test stencil. |
| [getDepthFailAction()](#getDepthFailAction--) | Ottiene l'azione stencil quando il test stencil supera ma il test di profondità fallisce. |
| [getFailAction()](#getFailAction--) | Ottiene l'azione stencil quando il test stencil fallisce. |
| [getPassAction()](#getPassAction--) | Ottiene l'azione stencil quando sia il test stencil sia il test di profondità hanno successo. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompare(CompareFunction value)](#setCompare-com.aspose.threed.CompareFunction-) | Imposta la funzione di confronto utilizzata nel test stencil. |
| [setDepthFailAction(StencilAction value)](#setDepthFailAction-com.aspose.threed.StencilAction-) | Imposta l'azione stencil quando il test stencil supera ma il test di profondità fallisce. |
| [setFailAction(StencilAction value)](#setFailAction-com.aspose.threed.StencilAction-) | Imposta l'azione stencil quando il test stencil fallisce. |
| [setPassAction(StencilAction value)](#setPassAction-com.aspose.threed.StencilAction-) | Imposta l'azione stencil quando sia il test stencil sia il test di profondità hanno successo. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un oggetto specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
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


Ottiene la funzione di confronto utilizzata nel test stencil.

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in stencil test
### getDepthFailAction() {#getDepthFailAction--}
```
public StencilAction getDepthFailAction()
```


Ottiene l'azione stencil quando il test stencil supera ma il test di profondità fallisce.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test pass but depth test fails.
### getFailAction() {#getFailAction--}
```
public StencilAction getFailAction()
```


Ottiene l'azione stencil quando il test stencil fallisce.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test fails.
### getPassAction() {#getPassAction--}
```
public StencilAction getPassAction()
```


Ottiene l'azione stencil quando sia il test stencil sia il test di profondità hanno successo.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when both stencil test and depth test passes.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa istanza.

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


Imposta la funzione di confronto utilizzata nel test stencil.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Nuovo valore |

### setDepthFailAction(StencilAction value) {#setDepthFailAction-com.aspose.threed.StencilAction-}
```
public void setDepthFailAction(StencilAction value)
```


Imposta l'azione stencil quando il test stencil supera ma il test di profondità fallisce.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nuovo valore |

### setFailAction(StencilAction value) {#setFailAction-com.aspose.threed.StencilAction-}
```
public void setFailAction(StencilAction value)
```


Imposta l'azione stencil quando il test stencil fallisce.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nuovo valore |

### setPassAction(StencilAction value) {#setPassAction-com.aspose.threed.StencilAction-}
```
public void setPassAction(StencilAction value)
```


Imposta l'azione stencil quando sia il test stencil sia il test di profondità hanno successo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nuovo valore |

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

