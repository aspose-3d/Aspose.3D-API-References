---
title: HollowRectangleShape
second_title: Aspose.3D for Java API Reference
description: Forma rettangolare cava compatibile con IFC con angoli arrotondati sia interni che esterni.
type: docs
weight: 79
url: /it/java/com.aspose.threed/hollowrectangleshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile), [com.aspose.threed.ParameterizedProfile](../../com.aspose.threed/parameterizedprofile), [com.aspose.threed.RectangleShape](../../com.aspose.threed/rectangleshape)
```
public class HollowRectangleShape extends RectangleShape
```

Forma rettangolare cava compatibile con IFC con angoli arrotondati sia interni che esterni.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HollowRectangleShape()](#HollowRectangleShape--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getBoundingBox()](#getBoundingBox--) | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Ottiene la chiave del renderer dell'entità registrata nel renderer |
| [getExcluded()](#getExcluded--) | Ottiene se escludere questa entità durante l'esportazione. |
| [getExtent()](#getExtent--) | Ottiene l'estensione nelle dimensioni x e y. |
| [getInnerFilletRadius()](#getInnerFilletRadius--) | Il raggio interno del raccordo del rettangolo interno. |
| [getName()](#getName--) | Ottiene il nome. |
| [getParentNode()](#getParentNode--) | Ottiene il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [getParentNodes()](#getParentNodes--) | Ottiene tutti i nodi genitore; un'entità può essere collegata a più nodi genitore per l'instancing della geometria. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getRoundingRadius()](#getRoundingRadius--) | Restituisce il raggio degli archi circolari di tutti e quattro gli angoli, misurato in gradi. |
| [getScene()](#getScene--) | Ottiene la scena a cui appartiene questo oggetto |
| [getWallThickness()](#getWallThickness--) | Lo spessore tra il contorno del rettangolo e il foro interno. |
| [getXDim()](#getXDim--) | Restituisce l'estensione del rettangolo nella direzione dell'asse x. Il valore predefinito è 2.0 |
| [getYDim()](#getYDim--) | Restituisce l'estensione del rettangolo nella direzione dell'asse y. Il valore predefinito è 2.0 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Imposta se escludere questa entità durante l'esportazione. |
| [setInnerFilletRadius(double value)](#setInnerFilletRadius-double-) | Il raggio interno del raccordo del rettangolo interno. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setRoundingRadius(double value)](#setRoundingRadius-double-) | Imposta il raggio degli archi circolari di tutti e quattro gli angoli, misurato in gradi. |
| [setWallThickness(double value)](#setWallThickness-double-) | Lo spessore tra il contorno del rettangolo e il foro interno. |
| [setXDim(double value)](#setXDim-double-) | Imposta l'estensione del rettangolo nella direzione dell'asse x. Il valore predefinito è 2.0 |
| [setYDim(double value)](#setYDim-double-) | Imposta l'estensione del rettangolo nella direzione dell'asse y. Il valore predefinito è 2.0 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HollowRectangleShape() {#HollowRectangleShape--}
```
public HollowRectangleShape()
```


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
### getInnerFilletRadius() {#getInnerFilletRadius--}
```
public double getInnerFilletRadius()
```


Il raggio interno del raccordo del rettangolo interno.

**Returns:**
double - Il raggio interno del raccordo del rettangolo interno.
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
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
### getRoundingRadius() {#getRoundingRadius--}
```
public double getRoundingRadius()
```


Restituisce il raggio degli archi circolari di tutti e quattro gli angoli, misurato in gradi. Il valore predefinito è 0.0

**Returns:**
double - il raggio degli archi circolari di tutti e quattro gli angoli, misurato in gradi. Il valore predefinito è 0.0
### getScene() {#getScene--}
```
public Scene getScene()
```


Ottiene la scena a cui appartiene questo oggetto

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getWallThickness() {#getWallThickness--}
```
public double getWallThickness()
```


Lo spessore tra il contorno del rettangolo e il foro interno.

**Returns:**
double - Lo spessore tra il contorno del rettangolo e il foro interno
### getXDim() {#getXDim--}
```
public double getXDim()
```


Restituisce l'estensione del rettangolo nella direzione dell'asse x. Il valore predefinito è 2.0

**Returns:**
double - l'estensione del rettangolo nella direzione dell'asse x. Il valore predefinito è 2.0
### getYDim() {#getYDim--}
```
public double getYDim()
```


Restituisce l'estensione del rettangolo nella direzione dell'asse y. Il valore predefinito è 2.0

**Returns:**
double - l'estensione del rettangolo nella direzione dell'asse y. Il valore predefinito è 2.0
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
### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Imposta se escludere questa entità durante l'esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setInnerFilletRadius(double value) {#setInnerFilletRadius-double-}
```
public void setInnerFilletRadius(double value)
```


Il raggio interno del raccordo del rettangolo interno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

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

### setRoundingRadius(double value) {#setRoundingRadius-double-}
```
public void setRoundingRadius(double value)
```


Imposta il raggio degli archi circolari di tutti e quattro gli angoli, misurato in gradi. Il valore predefinito è 0.0

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setWallThickness(double value) {#setWallThickness-double-}
```
public void setWallThickness(double value)
```


Lo spessore tra il contorno del rettangolo e il foro interno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setXDim(double value) {#setXDim-double-}
```
public void setXDim(double value)
```


Imposta l'estensione del rettangolo nella direzione dell'asse x. Il valore predefinito è 2.0

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setYDim(double value) {#setYDim-double-}
```
public void setYDim(double value)
```


Imposta l'estensione del rettangolo nella direzione dell'asse y. Il valore predefinito è 2.0

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

