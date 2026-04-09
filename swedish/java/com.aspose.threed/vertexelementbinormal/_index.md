---
title: VertexElementBinormal
second_title: Aspose.3D for Java API-referens
description: Definierar binormala vektorer för angivna komponenter.
type: docs
weight: 208
url: /sv/java/com.aspose.threed/vertexelementbinormal/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement), [com.aspose.threed.VertexElementVector4](../../com.aspose.threed/vertexelementvector4)
```
public class VertexElementBinormal extends VertexElementVector4
```

Definierar binormala vektorer för angivna komponenter.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [VertexElementBinormal()](#VertexElementBinormal--) | Initierar en ny instans av klassen [VertexElementBinormal](../../com.aspose.threed/vertexelementbinormal). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clear()](#clear--) | Tar bort alla element från de direkta och indexarrayerna. |
| [clone(boolean withData)](#clone-boolean-) | Skapa en djup klon av vertex‑elementet. |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [copyTo(VertexElementVector4 target)](#copyTo-com.aspose.threed.VertexElementVector4-) | Kopierar data till angivet element. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Hämtar vertex‑data. |
| [getIndices()](#getIndices--) | Hämtar index‑data. |
| [getMappingMode()](#getMappingMode--) | Hämtar hur elementet är mappat. |
| [getName()](#getName--) | Hämtar namnet. |
| [getReferenceMode()](#getReferenceMode--) | Hämtar hur elementet refereras. |
| [getVertexElementType()](#getVertexElementType--) | Hämtar typen av [VertexElement](../../com.aspose.threed/vertexelement). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(Vector4[] data)](#setData-com.aspose.threed.Vector4---) | Läs in data. |
| [setIndices(int[] data)](#setIndices-int---) | Läs in index. |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Ställer in hur elementet är mappat. |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Ställer in hur elementet refereras. |
| [toString()](#toString--) | Strängrepresentation av vertex‑elementet. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementBinormal() {#VertexElementBinormal--}
```
public VertexElementBinormal()
```


Initierar en ny instans av klassen [VertexElementBinormal](../../com.aspose.threed/vertexelementbinormal).

### clear() {#clear--}
```
public void clear()
```


Tar bort alla element från de direkta och indexarrayerna.

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
### copyTo(VertexElementVector4 target) {#copyTo-com.aspose.threed.VertexElementVector4-}
```
public void copyTo(VertexElementVector4 target)
```


Kopierar data till angivet element.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | [VertexElementVector4](../../com.aspose.threed/vertexelementvector4) | Mål. |

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
public List<Vector4> getData()
```


Hämtar vertex‑data.

**Returns:**
java.util.List<com.aspose.threed.Vector4> - vertexdata
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




### setData(Vector4[] data) {#setData-com.aspose.threed.Vector4---}
```
public void setData(Vector4[] data)
```


Läs in data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | [Vector4\[\]](../../com.aspose.threed/vector4) |  |

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

