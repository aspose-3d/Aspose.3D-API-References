---
title: NurbsDirection
second_title: Aspose.3D for Java API Reference
description: Un 3D  ha due direzioni, la  e la  la  definisce i dati per ogni direzione.
type: docs
weight: 113
url: /it/java/com.aspose.threed/nurbsdirection/
---

**Inheritance:**
java.lang.Object
```
public class NurbsDirection
```

Un 3D [NurbsSurface](../../com.aspose.threed/nurbssurface) ha due direzioni, il [NurbsSurface.getU](../../com.aspose.threed/nurbssurface\#getU) e il [NurbsSurface.getV](../../com.aspose.threed/nurbssurface\#getV), il [NurbsDirection](../../com.aspose.threed/nurbsdirection) definisce i dati per ogni direzione. Una direzione è in realtà una curva NURBS, il che significa che è anche definita dal suo [getOrder](../../com.aspose.threed/nurbsdirection\#getOrder), da un [getKnotVectors](../../com.aspose.threed/nurbsdirection\#getKnotVectors), e da un insieme di punti di controllo ponderati (definiti in [NurbsSurface](../../com.aspose.threed/nurbssurface)).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [NurbsDirection()](#NurbsDirection--) | Crea una nuova istanza di [NurbsDirection](../../com.aspose.threed/nurbsdirection) |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Restituisce il conteggio dei punti di controllo nella direzione corrente. |
| [getDegree()](#getDegree--) | Ottiene il grado di una curva NURBS, il grado è definito come Ordine - 1 |
| [getDivisions()](#getDivisions--) | Restituisce il numero di divisioni tra i punti di controllo adiacenti nella direzione corrente. |
| [getKnotVectors()](#getKnotVectors--) | Ottiene il vettore dei nodi, è una sequenza di valori di parametro che determina dove e come i punti di controllo influenzano la curva NURBS. |
| [getMultiplicity()](#getMultiplicity--) | Ottiene la molteplicità. |
| [getOrder()](#getOrder--) | Ottiene l'ordine di una curva NURBS, definisce il numero di punti di controllo vicini che influenzano un dato punto della curva. |
| [getType()](#getType--) | Restituisce il tipo della direzione corrente. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | Imposta il conteggio dei punti di controllo nella direzione corrente. |
| [setDegree(int value)](#setDegree-int-) | Imposta il grado di una curva NURBS, il grado è definito come Ordine - 1 |
| [setDivisions(int value)](#setDivisions-int-) | Imposta il numero di divisioni tra i punti di controllo adiacenti nella direzione corrente. |
| [setOrder(int value)](#setOrder-int-) | Imposta l'ordine di una curva NURBS, definisce il numero di punti di controllo vicini che influenzano un dato punto della curva. |
| [setType(NurbsType value)](#setType-com.aspose.threed.NurbsType-) | Imposta il tipo della direzione corrente. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsDirection() {#NurbsDirection--}
```
public NurbsDirection()
```


Crea una nuova istanza di [NurbsDirection](../../com.aspose.threed/nurbsdirection)

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Restituisce il conteggio dei punti di controllo nella direzione corrente.

**Returns:**
int - il conteggio dei punti di controllo nella direzione corrente.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Ottiene il grado di una curva NURBS, il grado è definito come Ordine - 1

**Returns:**
int - il grado di una curva NURBS, il grado è definito come Ordine - 1
### getDivisions() {#getDivisions--}
```
public int getDivisions()
```


Restituisce il numero di divisioni tra i punti di controllo adiacenti nella direzione corrente.

**Returns:**
int - il numero di divisioni tra i punti di controllo adiacenti nella direzione corrente.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Ottiene il vettore dei nodi, è una sequenza di valori di parametro che determina dove e come i punti di controllo influenzano la curva NURBS.

**Returns:**
java.util.List<java.lang.Double> - il vettore dei nodi, è una sequenza di valori di parametro che determina dove e come i punti di controllo influenzano la curva NURBS.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Ottiene la molteplicità.

**Returns:**
java.util.List<java.lang.Integer> - la molteplicità.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Ottiene l'ordine di una curva NURBS, definisce il numero di punti di controllo vicini che influenzano un dato punto della curva.

**Returns:**
int - l'ordine di una curva NURBS, definisce il numero di punti di controllo vicini che influenzano qualsiasi punto della curva.
### getType() {#getType--}
```
public NurbsType getType()
```


Restituisce il tipo della direzione corrente.

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


Imposta il conteggio dei punti di controllo nella direzione corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Imposta il grado di una curva NURBS, il grado è definito come Ordine - 1

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setDivisions(int value) {#setDivisions-int-}
```
public void setDivisions(int value)
```


Imposta il numero di divisioni tra i punti di controllo adiacenti nella direzione corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Imposta l'ordine di una curva NURBS, definisce il numero di punti di controllo vicini che influenzano un dato punto della curva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setType(NurbsType value) {#setType-com.aspose.threed.NurbsType-}
```
public void setType(NurbsType value)
```


Imposta il tipo della direzione corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Nuovo valore |

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

