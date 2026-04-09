---
title: VertexElementMaterial
second_title: Aspose.3D for Java API-referentie
description: Definieert materiaalindex voor gespecificeerde componenten.
type: docs
weight: 213
url: /nl/java/com.aspose.threed/vertexelementmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement)
```
public class VertexElementMaterial extends VertexElement
```

Definieert materiaalindex voor opgegeven componenten. Een knooppunt kan meerdere materialen hebben; de [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) wordt gebruikt om verschillende delen van de geometrie in verschillende materialen te renderen. **Example:** De volgende code laat zien hoe je verschillende materialen toewijst aan verschillende vlakken van een doos.

```
// Create a mesh of box(A box is composed by 6 planes)
             Mesh box = (new Box()).ToMesh();
             // Create a material element on this mesh
             VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
             // And specify different material index for each plane
             mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [VertexElementMaterial()](#VertexElementMaterial--) | Initialiseert een nieuw exemplaar van de [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clear()](#clear--) | Verwijdert alle elementen uit de directe en de indexarrays. |
| [clone(boolean withData)](#clone-boolean-) | Maak een diepe kloon van het vertex-element. |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIndices()](#getIndices--) | Haalt de indexgegevens op. |
| [getMappingMode()](#getMappingMode--) | Haalt op hoe het element is gemapt. |
| [getName()](#getName--) | Haalt de naam op. |
| [getReferenceMode()](#getReferenceMode--) | Haalt op hoe het element wordt gerefereerd. |
| [getVertexElementType()](#getVertexElementType--) | Haalt het type van de [VertexElement](../../com.aspose.threed/vertexelement) op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setIndices(int[] data)](#setIndices-int---) | Laad indexen. |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Stelt in hoe het element is gemapt. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Stelt in hoe het element wordt gerefereerd. |
| [toString()](#toString--) | Stringrepresentatie van het vertex-element. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementMaterial() {#VertexElementMaterial--}
```
public VertexElementMaterial()
```


Initialiseert een nieuw exemplaar van de [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) klasse.

### clear() {#clear--}
```
public void clear()
```


Verwijdert alle elementen uit de directe en de indexarrays.

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


Maak een diepe kloon van het vertex-element.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| withData | boolean | Kloon het vertex met directe en indexarray. |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### clone(boolean withDirect, boolean withIndice) {#clone-boolean-boolean-}
```
public VertexElement clone(boolean withDirect, boolean withIndice)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


Haalt de indexgegevens op.

**Returns:**
java.util.List<java.lang.Integer> - de indexgegevens
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


Haalt op hoe het element is gemapt.

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode) - how the element is mapped.
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
### getReferenceMode() {#getReferenceMode--}
```
public ReferenceMode getReferenceMode()
```


Haalt op hoe het element wordt gerefereerd.

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


Haalt het type van de [VertexElement](../../com.aspose.threed/vertexelement) op.

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




### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


Laad indexen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


Stelt in hoe het element is gemapt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | Nieuwe waarde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Stelt de naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


Stelt in hoe het element wordt gerefereerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | Nieuwe waarde |

### toString() {#toString--}
```
public String toString()
```


Stringrepresentatie van het vertex-element.

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

