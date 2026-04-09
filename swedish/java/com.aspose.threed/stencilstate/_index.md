---
title: StencilState
second_title: Aspose.3D for Java API-referens
description: Stencil‑tillstånd per yta.
type: docs
weight: 175
url: /sv/java/com.aspose.threed/stencilstate/
---

**Inheritance:**
java.lang.Object
```
public class StencilState
```

Stencil‑tillstånd per yta.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om den här instansen är lika med ett angivet objekt. |
| [getClass()](#getClass--) |  |
| [getCompare()](#getCompare--) | Hämtar jämförelsefunktionen som används i stenciltestet |
| [getDepthFailAction()](#getDepthFailAction--) | Hämtar stencilåtgärden när stenciltestet passerar men djupstestet misslyckas. |
| [getFailAction()](#getFailAction--) | Hämtar stencilåtgärden när stenciltestet misslyckas. |
| [getPassAction()](#getPassAction--) | Hämtar stencilåtgärden när både stenciltestet och djupstestet passerar. |
| [hashCode()](#hashCode--) | Returnerar hashkoden för den här instansen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompare(CompareFunction value)](#setCompare-com.aspose.threed.CompareFunction-) | Ställer in jämförelsefunktionen som används i stenciltestet |
| [setDepthFailAction(StencilAction value)](#setDepthFailAction-com.aspose.threed.StencilAction-) | Ställer in stencilåtgärden när stenciltestet passerar men djupstestet misslyckas. |
| [setFailAction(StencilAction value)](#setFailAction-com.aspose.threed.StencilAction-) | Ställer in stencilåtgärden när stenciltestet misslyckas. |
| [setPassAction(StencilAction value)](#setPassAction-com.aspose.threed.StencilAction-) | Ställer in stencilåtgärden när både stenciltestet och djupstestet passerar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om den här instansen är lika med ett angivet objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar jämförelsefunktionen som används i stenciltestet

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in stencil test
### getDepthFailAction() {#getDepthFailAction--}
```
public StencilAction getDepthFailAction()
```


Hämtar stencilåtgärden när stenciltestet passerar men djupstestet misslyckas.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test pass but depth test fails.
### getFailAction() {#getFailAction--}
```
public StencilAction getFailAction()
```


Hämtar stencilåtgärden när stenciltestet misslyckas.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test fails.
### getPassAction() {#getPassAction--}
```
public StencilAction getPassAction()
```


Hämtar stencilåtgärden när både stenciltestet och djupstestet passerar.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when both stencil test and depth test passes.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hashkoden för den här instansen.

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


Ställer in jämförelsefunktionen som används i stenciltestet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Nytt värde |

### setDepthFailAction(StencilAction value) {#setDepthFailAction-com.aspose.threed.StencilAction-}
```
public void setDepthFailAction(StencilAction value)
```


Ställer in stencilåtgärden när stenciltestet passerar men djupstestet misslyckas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nytt värde |

### setFailAction(StencilAction value) {#setFailAction-com.aspose.threed.StencilAction-}
```
public void setFailAction(StencilAction value)
```


Ställer in stencilåtgärden när stenciltestet misslyckas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nytt värde |

### setPassAction(StencilAction value) {#setPassAction-com.aspose.threed.StencilAction-}
```
public void setPassAction(StencilAction value)
```


Ställer in stencilåtgärden när både stenciltestet och djupstestet passerar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nytt värde |

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

