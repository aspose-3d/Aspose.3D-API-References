---
title: NurbsCurve
second_title: Aspose.3D for Java API Reference
description: Una curva NURBS è una curva rappresentata da NURBSNon-uniform rational basis spline  Una curva NURBS è definita da un  un insieme di punti ponderati  e un  Il componente w nel punto di controllo è usato come peso del punto di controllo, qualunque esso sia, o
type: docs
weight: 112
url: /it/java/com.aspose.threed/nurbscurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class NurbsCurve extends Curve
```

[NURBS curve][] is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [getOrder](../../com.aspose.threed/nurbscurve\#getOrder), a set of weighted [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) and a [getKnotVectors](../../com.aspose.threed/nurbscurve\#getKnotVectors) The w component in control point is used as control point's weight, whatever it is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS curve]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [NurbsCurve()](#NurbsCurve--) | Inizializza una nuova istanza della classe [NurbsCurve](../../com.aspose.threed/nurbscurve). |
| [NurbsCurve(String name)](#NurbsCurve-java.lang.String-) | Inizializza una nuova istanza della classe [NurbsCurve](../../com.aspose.threed/nurbscurve). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluate()](#evaluate--) | Valuta la curva NURBS |
| [evaluate(int steps)](#evaluate-int-) | Valuta la curva NURBS |
| [evaluateAt(double u)](#evaluateAt-double-) | Valuta il punto della curva nella posizione specificata |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getBoundingBox()](#getBoundingBox--) | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Ottiene il colore della linea, il valore predefinito è bianco(1, 1, 1) |
| [getControlPoints()](#getControlPoints--) | Restituisce tutti i punti di controllo |
| [getCurveType()](#getCurveType--) | Ottiene il tipo della curva. |
| [getDegree()](#getDegree--) | Ottiene il grado di una curva NURBS, il grado è definito come Ordine - 1 |
| [getDimension()](#getDimension--) | Ottiene la dimensione della curva. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Ottiene la chiave del renderer dell'entità registrata nel renderer |
| [getExcluded()](#getExcluded--) | Ottiene se escludere questa entità durante l'esportazione. |
| [getKnotVectors()](#getKnotVectors--) | Ottiene il vettore dei nodi, è una sequenza di valori di parametro che determina dove e come i punti di controllo influenzano la curva NURBS. |
| [getMultiplicity()](#getMultiplicity--) | Ottiene la molteplicità. |
| [getName()](#getName--) | Ottiene il nome. |
| [getOrder()](#getOrder--) | Ottiene l'ordine di una curva NURBS, definisce il numero di punti di controllo vicini che influenzano un dato punto della curva. |
| [getParentNode()](#getParentNode--) | Ottiene il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [getParentNodes()](#getParentNodes--) | Ottiene tutti i nodi genitore; un'entità può essere collegata a più nodi genitore per l'instancing della geometria. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getRational()](#getRational--) | Ottiene se è razionale, questo valore indica se questo [NurbsCurve](../../com.aspose.threed/nurbscurve) è una spline razionale o non razionale. |
| [getScene()](#getScene--) | Ottiene la scena a cui appartiene questo oggetto |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Imposta il colore della linea, il valore predefinito è bianco(1, 1, 1) |
| [setCurveType(NurbsType value)](#setCurveType-com.aspose.threed.NurbsType-) | Imposta il tipo della curva. |
| [setDegree(int value)](#setDegree-int-) | Imposta il grado di una curva NURBS, il grado è definito come Ordine - 1 |
| [setDimension(CurveDimension value)](#setDimension-com.aspose.threed.CurveDimension-) | Imposta la dimensione della curva. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Imposta se escludere questa entità durante l'esportazione. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setOrder(int value)](#setOrder-int-) | Imposta l'ordine di una curva NURBS, definisce il numero di punti di controllo vicini che influenzano un dato punto della curva. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setRational(boolean value)](#setRational-boolean-) | Imposta se è razionale, questo valore indica se questo [NurbsCurve](../../com.aspose.threed/nurbscurve) è una spline razionale o non razionale. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsCurve() {#NurbsCurve--}
```
public NurbsCurve()
```


Inizializza una nuova istanza della classe [NurbsCurve](../../com.aspose.threed/nurbscurve).

### NurbsCurve(String name) {#NurbsCurve-java.lang.String-}
```
public NurbsCurve(String name)
```


Inizializza una nuova istanza della classe [NurbsCurve](../../com.aspose.threed/nurbscurve).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome |

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
### evaluate() {#evaluate--}
```
public Vector4[] evaluate()
```


Valuta la curva NURBS

**Returns:**
com.aspose.threed.Vector4[] - Punti nella curva
### evaluate(int steps) {#evaluate-int-}
```
public Vector4[] evaluate(int steps)
```


Valuta la curva NURBS

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| passi | int | La frequenza di valutazione tra due nodi adiacenti, il valore predefinito è 20 |

**Returns:**
com.aspose.threed.Vector4[] - Punti nella curva
### evaluateAt(double u) {#evaluateAt-double-}
```
public Vector4 evaluateAt(double u)
```


Valuta il punto della curva nella posizione specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| u | double | La posizione nella curva, tra 0 e 1 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Trova la proprietà. Può essere una proprietà dinamica (creata con CreateDynamicProperty/SetProperty) o una proprietà nativa (identificata per nome).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyName | java.lang.String | Nome della proprietà. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto.

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Vector3 getColor()
```


Ottiene il colore della linea, il valore predefinito è bianco(1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Restituisce tutti i punti di controllo

**Returns:**
java.util.List<com.aspose.threed.Vector4> - tutti i punti di controllo
### getCurveType() {#getCurveType--}
```
public NurbsType getCurveType()
```


Ottiene il tipo della curva.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the curve.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Ottiene il grado di una curva NURBS, il grado è definito come Ordine - 1

**Returns:**
int - il grado di una curva NURBS, il grado è definito come Ordine - 1
### getDimension() {#getDimension--}
```
public CurveDimension getDimension()
```


Ottiene la dimensione della curva.

**Returns:**
[CurveDimension](../../com.aspose.threed/curvedimension) - the curve's dimension. **Remarks:** For a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve, the z component in control point is unused.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Ottiene la chiave del renderer dell'entità registrata nel renderer

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Ottiene se escludere questa entità durante l'esportazione.

**Returns:**
boolean - se escludere questa entità durante l'esportazione.
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
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Ottiene l'ordine di una curva NURBS, definisce il numero di punti di controllo vicini che influenzano un dato punto della curva.

**Returns:**
int - l'ordine di una curva NURBS, definisce il numero di punti di controllo vicini che influenzano qualsiasi punto della curva.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Ottiene il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Ottiene tutti i nodi genitore; un'entità può essere collegata a più nodi genitore per l'instancing della geometria.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - tutti i nodi genitore, un'entità può essere collegata a più nodi genitore per l'instanziazione della geometria
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Ottiene la collezione di tutte le proprietà.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Ottieni il valore della proprietà specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Nome della proprietà |

**Returns:**
java.lang.Object - Il valore della proprietà trovata
### getRational() {#getRational--}
```
public boolean getRational()
```


Ottiene se è razionale, questo valore indica se questo [NurbsCurve](../../com.aspose.threed/nurbscurve) è una spline razionale o non razionale. La B-spline non razionale è un caso speciale di B-spline razionali.

**Returns:**
boolean - se è razionale, questo valore indica se questo [NurbsCurve](../../com.aspose.threed/nurbscurve) è una spline razionale o non razionale. La B-spline non razionale è un caso speciale di B-spline razionali.
### getScene() {#getScene--}
```
public Scene getScene()
```


Ottiene la scena a cui appartiene questo oggetto

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
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




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Rimuove una proprietà dinamica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Quale proprietà rimuovere |

**Returns:**
boolean - true se la proprietà è stata rimossa con successo
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Rimuove la proprietà specificata identificata per nome

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Quale proprietà rimuovere |

**Returns:**
boolean - true se la proprietà è stata rimossa con successo
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Imposta il colore della linea, il valore predefinito è bianco(1, 1, 1)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setCurveType(NurbsType value) {#setCurveType-com.aspose.threed.NurbsType-}
```
public void setCurveType(NurbsType value)
```


Imposta il tipo della curva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Nuovo valore |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Imposta il grado di una curva NURBS, il grado è definito come Ordine - 1

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setDimension(CurveDimension value) {#setDimension-com.aspose.threed.CurveDimension-}
```
public void setDimension(CurveDimension value)
```


Imposta la dimensione della curva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CurveDimension](../../com.aspose.threed/curvedimension) | Nuovo valore **Osservazioni:** Per una curva [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL), la componente z nel punto di controllo non è utilizzata. |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Imposta se escludere questa entità durante l'esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Imposta l'ordine di una curva NURBS, definisce il numero di punti di controllo vicini che influenzano un dato punto della curva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nuovo valore |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Imposta il valore della proprietà specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Nome della proprietà |
| valore | java.lang.Object | Il valore della proprietà |

### setRational(boolean value) {#setRational-boolean-}
```
public void setRational(boolean value)
```


Imposta se è razionale, questo valore indica se questo [NurbsCurve](../../com.aspose.threed/nurbscurve) è una spline razionale o non razionale. La B-spline non razionale è un caso speciale di B-spline razionali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

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

