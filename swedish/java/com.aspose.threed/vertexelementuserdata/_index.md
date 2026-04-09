---
title: VertexElementUserData
second_title: Aspose.3D for Java API-referens
description: Definierar anpassad användardata för angivna komponenter.
type: docs
weight: 221
url: /sv/java/com.aspose.threed/vertexelementuserdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement)
```
public class VertexElementUserData extends VertexElement
```

Definierar anpassad användardata för specificerade komponenter. Vanligtvis är det applikationsspecifik data för särskilt ändamål.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [VertexElementUserData()](#VertexElementUserData--) | Initierar en ny instans av klassen [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clear()](#clear--) | Rensar all data från detta vertex‑element. |
| [clone(boolean withData)](#clone-boolean-) | Skapa en djup klon av vertex‑elementet. |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Användardatan som är bifogad i detta element |
| [getIndices()](#getIndices--) | Hämtar index‑data. |
| [getMappingMode()](#getMappingMode--) | Hämtar hur elementet är mappat. |
| [getName()](#getName--) | Hämtar namnet. |
| [getReferenceMode()](#getReferenceMode--) | Hämtar hur elementet refereras. |
| [getVertexElementType()](#getVertexElementType--) | Hämtar typen av [VertexElement](../../com.aspose.threed/vertexelement). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(Object value)](#setData-java.lang.Object-) | Användardatan som är bifogad i detta element |
| [setIndices(int[] data)](#setIndices-int---) | Läs in index. |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Ställer in hur elementet är mappat. |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Ställer in hur elementet refereras. |
| [toString()](#toString--) | Strängrepresentation av vertex‑elementet. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementUserData() {#VertexElementUserData--}
```
public VertexElementUserData()
```


Initierar en ny instans av klassen [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata).

### clear() {#clear--}
```
public void clear()
```


Rensar all data från detta vertex‑element.

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


Skapa en djup klon av vertex‑elementet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| withData | boolean | Klona vertexen med direkt‑ och index‑array. |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### clone(boolean withDirect, boolean withIndice) {#clone-boolean-boolean-}
```
public VertexElement clone(boolean withDirect, boolean withIndice)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| withDirect | boolean |  |
| withIndice | boolean |  |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
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
### getData() {#getData--}
```
public Object getData()
```


Användardatan som är bifogad i detta element

**Returns:**
java.lang.Object - Användardatan som är bifogad i detta element
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


Hämtar index‑data.

**Returns:**
java.util.List<java.lang.Integer> - index‑data
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


Hämtar hur elementet är mappat.

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode) - how the element is mapped.
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getReferenceMode() {#getReferenceMode--}
```
public ReferenceMode getReferenceMode()
```


Hämtar hur elementet refereras.

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


Hämtar typen av [VertexElement](../../com.aspose.threed/vertexelement).

**Returns:**
[VertexElementType](../../com.aspose.threed/vertexelementtype) - the type of the [VertexElement](../../com.aspose.threed/vertexelement)
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




### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Användardatan som är bifogad i detta element

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object | Nytt värde |

### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


Läs in index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


Ställer in hur elementet är mappat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | Nytt värde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ställer in namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


Ställer in hur elementet refereras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | Nytt värde |

### toString() {#toString--}
```
public String toString()
```


Strängrepresentation av vertex‑elementet.

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

