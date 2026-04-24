---
title: NurbsDirection
second_title: Aspose.3D for Java API-referentie
description: Een 3D  heeft twee richtingen, de  en  de  definieert gegevens voor elke richting.
type: docs
weight: 113
url: /nl/java/com.aspose.threed/nurbsdirection/
---

**Inheritance:**
java.lang.Object
```
public class NurbsDirection
```

Een 3D [NurbsSurface](../../com.aspose.threed/nurbssurface) heeft twee richtingen, de [NurbsSurface.getU](../../com.aspose.threed/nurbssurface\#getU) en [NurbsSurface.getV](../../com.aspose.threed/nurbssurface\#getV), de [NurbsDirection](../../com.aspose.threed/nurbsdirection) definieert gegevens voor elke richting. Een richting is eigenlijk een NURBS-curve, wat betekent dat deze ook wordt gedefinieerd door zijn [getOrder](../../com.aspose.threed/nurbsdirection\#getOrder), een [getKnotVectors](../../com.aspose.threed/nurbsdirection\#getKnotVectors), en een set gewogen controlepunten (gedefinieerd in [NurbsSurface](../../com.aspose.threed/nurbssurface)).
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [NurbsDirection()](#NurbsDirection--) | Maak een nieuw exemplaar van [NurbsDirection](../../com.aspose.threed/nurbsdirection) |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Haalt het aantal controlepunten op in de huidige richting. |
| [getDegree()](#getDegree--) | Haalt de graad van een NURBS-curve op, de graad wordt gedefinieerd als Order - 1 |
| [getDivisions()](#getDivisions--) | Haalt het aantal delingen tussen aangrenzende controlepunten op in de huidige richting. |
| [getKnotVectors()](#getKnotVectors--) | Haalt de knoopvector op, dit is een reeks parameterwaarden die bepalen waar en hoe de controlepunten de NURBS-curve beïnvloeden. |
| [getMultiplicity()](#getMultiplicity--) | Haalt de multipliciteit op. |
| [getOrder()](#getOrder--) | Haalt de orde van een NURBS-curve op, dit definieert het aantal naburige controlepunten die elk punt op de curve beïnvloeden. |
| [getType()](#getType--) | Haalt het type van de huidige richting op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | Stelt het aantal controlepunten in de huidige richting in. |
| [setDegree(int value)](#setDegree-int-) | Stelt de graad van een NURBS-curve in, de graad wordt gedefinieerd als Order - 1 |
| [setDivisions(int value)](#setDivisions-int-) | Stelt het aantal delingen tussen aangrenzende controlepunten in de huidige richting in. |
| [setOrder(int value)](#setOrder-int-) | Stelt de orde van een NURBS-curve in, dit definieert het aantal naburige controlepunten die elk punt op de curve beïnvloeden. |
| [setType(NurbsType value)](#setType-com.aspose.threed.NurbsType-) | Stelt het type van de huidige richting in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsDirection() {#NurbsDirection--}
```
public NurbsDirection()
```


Maak een nieuw exemplaar van [NurbsDirection](../../com.aspose.threed/nurbsdirection)

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
### getCount() {#getCount--}
```
public int getCount()
```


Haalt het aantal controlepunten op in de huidige richting.

**Returns:**
int - het aantal controlepunten in de huidige richting.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Haalt de graad van een NURBS-curve op, de graad wordt gedefinieerd als Order - 1

**Returns:**
int - de graad van een NURBS-curve, de graad wordt gedefinieerd als Order - 1
### getDivisions() {#getDivisions--}
```
public int getDivisions()
```


Haalt het aantal delingen tussen aangrenzende controlepunten op in de huidige richting.

**Returns:**
int - het aantal delingen tussen aangrenzende controlepunten in de huidige richting.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Haalt de knoopvector op, dit is een reeks parameterwaarden die bepalen waar en hoe de controlepunten de NURBS-curve beïnvloeden.

**Returns:**
java.util.List<java.lang.Double> - de knoopvector, dit is een reeks parameterwaarden die bepalen waar en hoe de controlepunten de NURBS-curve beïnvloeden.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Haalt de multipliciteit op.

**Returns:**
java.util.List<java.lang.Integer> - de multipliciteit.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Haalt de orde van een NURBS-curve op, dit definieert het aantal naburige controlepunten die elk punt op de curve beïnvloeden.

**Returns:**
int - de orde van een NURBS-curve, deze definieert het aantal nabije controlepunten die elk punt op de curve beïnvloeden.
### getType() {#getType--}
```
public NurbsType getType()
```


Haalt het type van de huidige richting op.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the current direction.
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




### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


Stelt het aantal controlepunten in de huidige richting in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Stelt de graad van een NURBS-curve in, de graad wordt gedefinieerd als Order - 1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setDivisions(int value) {#setDivisions-int-}
```
public void setDivisions(int value)
```


Stelt het aantal delingen tussen aangrenzende controlepunten in de huidige richting in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Stelt de orde van een NURBS-curve in, dit definieert het aantal naburige controlepunten die elk punt op de curve beïnvloeden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setType(NurbsType value) {#setType-com.aspose.threed.NurbsType-}
```
public void setType(NurbsType value)
```


Stelt het type van de huidige richting in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Nieuwe waarde |

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

