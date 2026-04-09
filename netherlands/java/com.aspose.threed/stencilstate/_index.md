---
title: StencilState
second_title: Aspose.3D for Java API-referentie
description: Stencil-toestanden per vlak.
type: docs
weight: 175
url: /nl/java/com.aspose.threed/stencilstate/
---

**Inheritance:**
java.lang.Object
```
public class StencilState
```

Stencil-toestanden per vlak.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven object. |
| [getClass()](#getClass--) |  |
| [getCompare()](#getCompare--) | Haalt de vergelijkingsfunctie op die wordt gebruikt in de stenciltest |
| [getDepthFailAction()](#getDepthFailAction--) | Haalt de stencilactie op wanneer de stenciltest slaagt maar de dieptest faalt. |
| [getFailAction()](#getFailAction--) | Haalt de stencilactie op wanneer de stenciltest faalt. |
| [getPassAction()](#getPassAction--) | Haalt de stencilactie op wanneer zowel de stenciltest als de dieptest slagen. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompare(CompareFunction value)](#setCompare-com.aspose.threed.CompareFunction-) | Stelt de vergelijkingsfunctie in die wordt gebruikt in de stenciltest |
| [setDepthFailAction(StencilAction value)](#setDepthFailAction-com.aspose.threed.StencilAction-) | Stelt de stencilactie in wanneer de stenciltest slaagt maar de dieptest faalt. |
| [setFailAction(StencilAction value)](#setFailAction-com.aspose.threed.StencilAction-) | Stelt de stencilactie in wanneer de stenciltest faalt. |
| [setPassAction(StencilAction value)](#setPassAction-com.aspose.threed.StencilAction-) | Stelt de stencilactie in wanneer zowel de stenciltest als de dieptest slagen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven object.

**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de vergelijkingsfunctie op die wordt gebruikt in de stenciltest

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in stencil test
### getDepthFailAction() {#getDepthFailAction--}
```
public StencilAction getDepthFailAction()
```


Haalt de stencilactie op wanneer de stenciltest slaagt maar de dieptest faalt.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test pass but depth test fails.
### getFailAction() {#getFailAction--}
```
public StencilAction getFailAction()
```


Haalt de stencilactie op wanneer de stenciltest faalt.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test fails.
### getPassAction() {#getPassAction--}
```
public StencilAction getPassAction()
```


Haalt de stencilactie op wanneer zowel de stenciltest als de dieptest slagen.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when both stencil test and depth test passes.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

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


Stelt de vergelijkingsfunctie in die wordt gebruikt in de stenciltest

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Nieuwe waarde |

### setDepthFailAction(StencilAction value) {#setDepthFailAction-com.aspose.threed.StencilAction-}
```
public void setDepthFailAction(StencilAction value)
```


Stelt de stencilactie in wanneer de stenciltest slaagt maar de dieptest faalt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nieuwe waarde |

### setFailAction(StencilAction value) {#setFailAction-com.aspose.threed.StencilAction-}
```
public void setFailAction(StencilAction value)
```


Stelt de stencilactie in wanneer de stenciltest faalt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nieuwe waarde |

### setPassAction(StencilAction value) {#setPassAction-com.aspose.threed.StencilAction-}
```
public void setPassAction(StencilAction value)
```


Stelt de stencilactie in wanneer zowel de stenciltest als de dieptest slagen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nieuwe waarde |

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

