---
title: VertexElementUV
second_title: Aspose.3D for Java API-referentie
description: Definieert de UV-coördinaten voor gespecificeerde componenten.
type: docs
weight: 220
url: /nl/java/com.aspose.threed/vertexelementuv/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement), [com.aspose.threed.VertexElementVector4](../../com.aspose.threed/vertexelementvector4)
```
public class VertexElementUV extends VertexElementVector4
```

Definieert de UV-coördinaten voor opgegeven componenten. Een geometrie kan meerdere [VertexElementUV](../../com.aspose.threed/vertexelementuv) elementen hebben, en elk heeft verschillende [TextureMapping](../../com.aspose.threed/texturemapping)s.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [VertexElementUV()](#VertexElementUV--) | Initialiseert een nieuw exemplaar van de [VertexElementUV](../../com.aspose.threed/vertexelementuv) klasse. |
| [VertexElementUV(TextureMapping textureMapping)](#VertexElementUV-com.aspose.threed.TextureMapping-) | Initialiseert een nieuw exemplaar van de [VertexElementUV](../../com.aspose.threed/vertexelementuv) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addData(Iterable<Vector2> data)](#addData-java.lang.Iterable-com.aspose.threed.Vector2--) | Voeg een set van [Vector2](../../com.aspose.threed/vector2) toe aan VertexElementUV.Data. |
| [addData2(Iterable<Vector3> data)](#addData2-java.lang.Iterable-com.aspose.threed.Vector3--) | Voeg een set van [Vector3](../../com.aspose.threed/vector3) toe aan VertexElementUV.Data. |
| [clear()](#clear--) | Verwijdert alle elementen uit de directe en de indexarrays. |
| [clone(boolean withData)](#clone-boolean-) | Maak een diepe kloon van het vertex-element. |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [copyTo(VertexElementVector4 target)](#copyTo-com.aspose.threed.VertexElementVector4-) | Kopieert gegevens naar het opgegeven element. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Haalt de vertex-gegevens op. |
| [getIndices()](#getIndices--) | Haalt de indexgegevens op. |
| [getMappingMode()](#getMappingMode--) | Haalt op hoe het element is gemapt. |
| [getName()](#getName--) | Haalt de naam op. |
| [getReferenceMode()](#getReferenceMode--) | Haalt op hoe het element wordt gerefereerd. |
| [getVertexElementType()](#getVertexElementType--) | Haalt het type van de [VertexElement](../../com.aspose.threed/vertexelement) op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(Vector4[] data)](#setData-com.aspose.threed.Vector4---) | Laad gegevens. |
| [setIndices(int[] data)](#setIndices-int---) | Laad indexen. |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Stelt in hoe het element is gemapt. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Stelt in hoe het element wordt gerefereerd. |
| [toString()](#toString--) | Stringrepresentatie van het vertex-element. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementUV() {#VertexElementUV--}
```
public VertexElementUV()
```


Initialiseert een nieuw exemplaar van de [VertexElementUV](../../com.aspose.threed/vertexelementuv) klasse. Het standaard textuur-mappingtype is [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE)

### VertexElementUV(TextureMapping textureMapping) {#VertexElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV(TextureMapping textureMapping)
```


Initialiseert een nieuw exemplaar van de [VertexElementUV](../../com.aspose.threed/vertexelementuv) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Het textuur-mappingtype. |

### addData(Iterable<Vector2> data) {#addData-java.lang.Iterable-com.aspose.threed.Vector2--}
```
public void addData(Iterable<Vector2> data)
```


Voeg een set van [Vector2](../../com.aspose.threed/vector2) toe aan VertexElementUV.Data. Dit is een snelkoppeling, deze methode zal de [Vector2](../../com.aspose.threed/vector2) converteren naar [Vector4](../../com.aspose.threed/vector4) met z op 0 en w op 0.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | java.lang.Iterable<com.aspose.threed.Vector2> |  |

### addData2(Iterable<Vector3> data) {#addData2-java.lang.Iterable-com.aspose.threed.Vector3--}
```
public void addData2(Iterable<Vector3> data)
```


Voeg een set van [Vector3](../../com.aspose.threed/vector3) toe aan VertexElementUV.Data. Dit is een snelkoppeling, deze methode zal de [Vector3](../../com.aspose.threed/vector3) converteren naar [Vector4](../../com.aspose.threed/vector4) met w op 0.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | java.lang.Iterable<com.aspose.threed.Vector3> |  |

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
### copyTo(VertexElementVector4 target) {#copyTo-com.aspose.threed.VertexElementVector4-}
```
public void copyTo(VertexElementVector4 target)
```


Kopieert gegevens naar het opgegeven element.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [VertexElementVector4](../../com.aspose.threed/vertexelementvector4) | Doel. |

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
### getData() {#getData--}
```
public List<Vector4> getData()
```


Haalt de vertex-gegevens op.

**Returns:**
java.util.List<com.aspose.threed.Vector4> - de vertexgegevens
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




### setData(Vector4[] data) {#setData-com.aspose.threed.Vector4---}
```
public void setData(Vector4[] data)
```


Laad gegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | [Vector4\[\]](../../com.aspose.threed/vector4) |  |

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

