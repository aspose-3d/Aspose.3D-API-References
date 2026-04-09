---
title: NurbsDirection
second_title: Aspose.3D for Java API-referens
description: En 3D  har två riktningar, den  och  , den  definierar data för varje riktning.
type: docs
weight: 113
url: /sv/java/com.aspose.threed/nurbsdirection/
---

**Inheritance:**
java.lang.Object
```
public class NurbsDirection
```

En 3D [NurbsSurface](../../com.aspose.threed/nurbssurface) har två riktningar, [NurbsSurface.getU](../../com.aspose.threed/nurbssurface\#getU) och [NurbsSurface.getV](../../com.aspose.threed/nurbssurface\#getV), [NurbsDirection](../../com.aspose.threed/nurbsdirection) definierar data för varje riktning. En riktning är faktiskt en NURBS-kurva, vilket betyder att den också definieras av dess [getOrder](../../com.aspose.threed/nurbsdirection\#getOrder), en [getKnotVectors](../../com.aspose.threed/nurbsdirection\#getKnotVectors), och en uppsättning viktade kontrollpunkter (definierade i [NurbsSurface](../../com.aspose.threed/nurbssurface)).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [NurbsDirection()](#NurbsDirection--) | Skapa en ny instans av [NurbsDirection](../../com.aspose.threed/nurbsdirection) |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Hämtar antalet kontrollpunkter i aktuell riktning. |
| [getDegree()](#getDegree--) | Hämtar graden för en NURBS‑kurva, graden definieras som Order - 1 |
| [getDivisions()](#getDivisions--) | Hämtar antalet delningar mellan intilliggande kontrollpunkter i aktuell riktning. |
| [getKnotVectors()](#getKnotVectors--) | Hämtar knutvektorn, den är en sekvens av parametervärden som bestämmer var och hur kontrollpunkterna påverkar NURBS‑kurvan. |
| [getMultiplicity()](#getMultiplicity--) | Hämtar multipliciteten. |
| [getOrder()](#getOrder--) | Hämtar ordningen för en NURBS‑kurva, den definierar antalet närliggande kontrollpunkter som påverkar en given punkt på kurvan. |
| [getType()](#getType--) | Hämtar typen av den aktuella riktningen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | Ställer in antalet kontrollpunkter i aktuell riktning. |
| [setDegree(int value)](#setDegree-int-) | Ställer in graden för en NURBS‑kurva, graden definieras som Order - 1 |
| [setDivisions(int value)](#setDivisions-int-) | Ställer in antalet delningar mellan intilliggande kontrollpunkter i aktuell riktning. |
| [setOrder(int value)](#setOrder-int-) | Ställer in ordningen för en NURBS‑kurva, den definierar antalet närliggande kontrollpunkter som påverkar en given punkt på kurvan. |
| [setType(NurbsType value)](#setType-com.aspose.threed.NurbsType-) | Ställer in typen av den aktuella riktningen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsDirection() {#NurbsDirection--}
```
public NurbsDirection()
```


Skapa en ny instans av [NurbsDirection](../../com.aspose.threed/nurbsdirection)

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
### getCount() {#getCount--}
```
public int getCount()
```


Hämtar antalet kontrollpunkter i aktuell riktning.

**Returns:**
int - antalet kontrollpunkter i aktuell riktning.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Hämtar graden för en NURBS‑kurva, graden definieras som Order - 1

**Returns:**
int - graden för en NURBS‑kurva, graden definieras som Order - 1
### getDivisions() {#getDivisions--}
```
public int getDivisions()
```


Hämtar antalet delningar mellan intilliggande kontrollpunkter i aktuell riktning.

**Returns:**
int - antalet delningar mellan intilliggande kontrollpunkter i aktuell riktning.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Hämtar knutvektorn, den är en sekvens av parametervärden som bestämmer var och hur kontrollpunkterna påverkar NURBS‑kurvan.

**Returns:**
java.util.List<java.lang.Double> - knutvektorn, den är en sekvens av parametervärden som bestämmer var och hur kontrollpunkterna påverkar NURBS‑kurvan.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Hämtar multipliciteten.

**Returns:**
java.util.List<java.lang.Integer> - multipliciteten.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Hämtar ordningen för en NURBS‑kurva, den definierar antalet närliggande kontrollpunkter som påverkar en given punkt på kurvan.

**Returns:**
int - ordningen för en NURBS-kurva, den definierar antalet närliggande kontrollpunkter som påverkar varje given punkt på kurvan.
### getType() {#getType--}
```
public NurbsType getType()
```


Hämtar typen av den aktuella riktningen.

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


Ställer in antalet kontrollpunkter i aktuell riktning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Ställer in graden för en NURBS‑kurva, graden definieras som Order - 1

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setDivisions(int value) {#setDivisions-int-}
```
public void setDivisions(int value)
```


Ställer in antalet delningar mellan intilliggande kontrollpunkter i aktuell riktning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Ställer in ordningen för en NURBS‑kurva, den definierar antalet närliggande kontrollpunkter som påverkar en given punkt på kurvan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setType(NurbsType value) {#setType-com.aspose.threed.NurbsType-}
```
public void setType(NurbsType value)
```


Ställer in typen av den aktuella riktningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Nytt värde |

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

