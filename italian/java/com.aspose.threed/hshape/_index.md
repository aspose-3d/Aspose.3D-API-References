---
title: HShape
second_title: Aspose.3D for Java API Reference
description: Il  fornisce i parametri di definizione di una forma a H o I.
type: docs
weight: 76
url: /it/java/com.aspose.threed/hshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile), [com.aspose.threed.ParameterizedProfile](../../com.aspose.threed/parameterizedprofile)
```
public class HShape extends ParameterizedProfile
```

Il [HShape](../../com.aspose.threed/hshape) fornisce i parametri di definizione di una forma 'H' o 'I'.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HShape()](#HShape--) | Costruttore di [HShape](../../com.aspose.threed/hshape) |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getBottomFlangeEdgeRadius()](#getBottomFlangeEdgeRadius--) | Restituisce il raggio dei bordi superiori della flangia inferiore. |
| [getBottomFlangeFilletRadius()](#getBottomFlangeFilletRadius--) | Ottiene il raggio del raccordo tra l'anima e la flangia inferiore. |
| [getBottomFlangeThickness()](#getBottomFlangeThickness--) | Ottiene lo spessore della flangia della sezione a H. |
| [getBottomFlangeWidth()](#getBottomFlangeWidth--) | Ottiene l'estensione della larghezza. |
| [getBoundingBox()](#getBoundingBox--) | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Ottiene la chiave del renderer dell'entità registrata nel renderer |
| [getExcluded()](#getExcluded--) | Ottiene se escludere questa entità durante l'esportazione. |
| [getExtent()](#getExtent--) | Ottiene l'estensione nelle dimensioni x e y. |
| [getName()](#getName--) | Ottiene il nome. |
| [getOverallDepth()](#getOverallDepth--) | Ottiene l'estensione della profondità. |
| [getParentNode()](#getParentNode--) | Ottiene il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [getParentNodes()](#getParentNodes--) | Ottiene tutti i nodi genitore; un'entità può essere collegata a più nodi genitore per l'instancing della geometria. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getScene()](#getScene--) | Ottiene la scena a cui appartiene questo oggetto |
| [getTopFlangeEdgeRadius()](#getTopFlangeEdgeRadius--) | Ottiene il raggio dei bordi inferiori della flangia superiore. |
| [getTopFlangeFilletRadius()](#getTopFlangeFilletRadius--) | Ottiene il raggio del raccordo tra l'anima e la flangia superiore. |
| [getTopFlangeThickness()](#getTopFlangeThickness--) | Ottiene lo spessore della flangia superiore. |
| [getTopFlangeWidth()](#getTopFlangeWidth--) | Ottiene la larghezza della flangia superiore. |
| [getWebThickness()](#getWebThickness--) | Ottiene lo spessore dell'anima della sezione a H. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setBottomFlangeEdgeRadius(double value)](#setBottomFlangeEdgeRadius-double-) | Imposta il raggio dei bordi superiori della flangia inferiore. |
| [setBottomFlangeFilletRadius(double value)](#setBottomFlangeFilletRadius-double-) | Imposta il raggio del raccordo tra l'anima e la flangia inferiore. |
| [setBottomFlangeThickness(double value)](#setBottomFlangeThickness-double-) | Imposta lo spessore della flangia della sezione a H. |
| [setBottomFlangeWidth(double value)](#setBottomFlangeWidth-double-) | Imposta l'estensione della larghezza. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Imposta se escludere questa entità durante l'esportazione. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setOverallDepth(double value)](#setOverallDepth-double-) | Imposta l'estensione della profondità. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setTopFlangeEdgeRadius(double value)](#setTopFlangeEdgeRadius-double-) | Imposta il raggio dei bordi inferiori della flangia superiore. |
| [setTopFlangeFilletRadius(double value)](#setTopFlangeFilletRadius-double-) | Imposta il raggio del raccordo tra l'anima e la flangia superiore. |
| [setTopFlangeThickness(double value)](#setTopFlangeThickness-double-) | Imposta lo spessore della flangia superiore. |
| [setTopFlangeWidth(double value)](#setTopFlangeWidth-double-) | Imposta la larghezza della flangia superiore. |
| [setWebThickness(double value)](#setWebThickness-double-) | Imposta lo spessore dell'anima della sezione a H. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HShape() {#HShape--}
```
public HShape()
```


Costruttore di [HShape](../../com.aspose.threed/hshape)

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
### getBottomFlangeEdgeRadius() {#getBottomFlangeEdgeRadius--}
```
public double getBottomFlangeEdgeRadius()
```


Restituisce il raggio dei bordi superiori della flangia inferiore.

**Returns:**
double - il raggio dei bordi superiori della flangia inferiore.
### getBottomFlangeFilletRadius() {#getBottomFlangeFilletRadius--}
```
public double getBottomFlangeFilletRadius()
```


Ottiene il raggio del raccordo tra l'anima e la flangia inferiore.

**Returns:**
double - il raggio del raccordo tra l'anima e la flangia inferiore.
### getBottomFlangeThickness() {#getBottomFlangeThickness--}
```
public double getBottomFlangeThickness()
```


Ottiene lo spessore della flangia della sezione a H.

**Returns:**
double - lo spessore della flangia della sezione a H.
### getBottomFlangeWidth() {#getBottomFlangeWidth--}
```
public double getBottomFlangeWidth()
```


Ottiene l'estensione della larghezza.

**Returns:**
double - l'estensione della larghezza.
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
### getExtent() {#getExtent--}
```
public Vector2 getExtent()
```


Ottiene l'estensione nelle dimensioni x e y.

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getOverallDepth() {#getOverallDepth--}
```
public double getOverallDepth()
```


Ottiene l'estensione della profondità.

**Returns:**
double - l'estensione della profondità.
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Ottiene la scena a cui appartiene questo oggetto

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTopFlangeEdgeRadius() {#getTopFlangeEdgeRadius--}
```
public double getTopFlangeEdgeRadius()
```


Ottiene il raggio dei bordi inferiori della flangia superiore.

**Returns:**
double - il raggio dei bordi inferiori della flangia superiore.
### getTopFlangeFilletRadius() {#getTopFlangeFilletRadius--}
```
public double getTopFlangeFilletRadius()
```


Ottiene il raggio del raccordo tra l'anima e la flangia superiore.

**Returns:**
double - il raggio del raccordo tra l'anima e l'aletta superiore.
### getTopFlangeThickness() {#getTopFlangeThickness--}
```
public double getTopFlangeThickness()
```


Ottiene lo spessore della flangia superiore.

**Returns:**
double - lo spessore dell'aletta superiore.
### getTopFlangeWidth() {#getTopFlangeWidth--}
```
public double getTopFlangeWidth()
```


Ottiene la larghezza della flangia superiore.

**Returns:**
double - la larghezza dell'aletta superiore.
### getWebThickness() {#getWebThickness--}
```
public double getWebThickness()
```


Ottiene lo spessore dell'anima della sezione a H.

**Returns:**
double - lo spessore dell'anima della sezione a H.
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
### setBottomFlangeEdgeRadius(double value) {#setBottomFlangeEdgeRadius-double-}
```
public void setBottomFlangeEdgeRadius(double value)
```


Imposta il raggio dei bordi superiori della flangia inferiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setBottomFlangeFilletRadius(double value) {#setBottomFlangeFilletRadius-double-}
```
public void setBottomFlangeFilletRadius(double value)
```


Imposta il raggio del raccordo tra l'anima e la flangia inferiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setBottomFlangeThickness(double value) {#setBottomFlangeThickness-double-}
```
public void setBottomFlangeThickness(double value)
```


Imposta lo spessore della flangia della sezione a H.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setBottomFlangeWidth(double value) {#setBottomFlangeWidth-double-}
```
public void setBottomFlangeWidth(double value)
```


Imposta l'estensione della larghezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

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

### setOverallDepth(double value) {#setOverallDepth-double-}
```
public void setOverallDepth(double value)
```


Imposta l'estensione della profondità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

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

### setTopFlangeEdgeRadius(double value) {#setTopFlangeEdgeRadius-double-}
```
public void setTopFlangeEdgeRadius(double value)
```


Imposta il raggio dei bordi inferiori della flangia superiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setTopFlangeFilletRadius(double value) {#setTopFlangeFilletRadius-double-}
```
public void setTopFlangeFilletRadius(double value)
```


Imposta il raggio del raccordo tra l'anima e la flangia superiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setTopFlangeThickness(double value) {#setTopFlangeThickness-double-}
```
public void setTopFlangeThickness(double value)
```


Imposta lo spessore della flangia superiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setTopFlangeWidth(double value) {#setTopFlangeWidth-double-}
```
public void setTopFlangeWidth(double value)
```


Imposta la larghezza della flangia superiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setWebThickness(double value) {#setWebThickness-double-}
```
public void setWebThickness(double value)
```


Imposta lo spessore dell'anima della sezione a H.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

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

