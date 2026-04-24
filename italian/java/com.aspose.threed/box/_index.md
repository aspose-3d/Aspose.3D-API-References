---
title: Box
second_title: Aspose.3D for Java API Reference
description: Scatola.
type: docs
weight: 26
url: /it/java/com.aspose.threed/box/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Box extends Primitive
```

Scatola.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Box()](#Box--) | Inizializza una nuova istanza della classe [Box](../../com.aspose.threed/box). |
| [Box(double length, double width, double height)](#Box-double-double-double-) | Inizializza una nuova istanza della classe [Box](../../com.aspose.threed/box). |
| [Box(String name, double length, double width, double height, int lengthSegments, int widthSegments, int heightSegments)](#Box-java.lang.String-double-double-double-int-int-int-) | Inizializza una nuova istanza della classe [Box](../../com.aspose.threed/box). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getBoundingBox()](#getBoundingBox--) | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |
| [getCastShadows()](#getCastShadows--) | Restituisce se questa geometria può proiettare ombra |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Ottiene la chiave del renderer dell'entità registrata nel renderer |
| [getExcluded()](#getExcluded--) | Ottiene se escludere questa entità durante l'esportazione. |
| [getHeight()](#getHeight--) | Restituisce l'altezza della scatola allineata sull'asse y. |
| [getHeightSegments()](#getHeightSegments--) | Ottiene o imposta i segmenti di altezza. |
| [getLength()](#getLength--) | Restituisce la lunghezza della scatola allineata sull'asse z. |
| [getLengthSegments()](#getLengthSegments--) | Ottiene i segmenti di lunghezza. |
| [getName()](#getName--) | Ottiene il nome. |
| [getParentNode()](#getParentNode--) | Ottiene il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [getParentNodes()](#getParentNodes--) | Ottiene tutti i nodi genitore; un'entità può essere collegata a più nodi genitore per l'instancing della geometria. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getReceiveShadows()](#getReceiveShadows--) | Restituisce se questa geometria può ricevere ombra. |
| [getScene()](#getScene--) | Ottiene la scena a cui appartiene questo oggetto |
| [getWidth()](#getWidth--) | Restituisce la larghezza della scatola allineata sull'asse x. |
| [getWidthSegments()](#getWidthSegments--) | Restituisce i segmenti di larghezza |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Imposta se questa geometria può proiettare ombra |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Imposta se escludere questa entità durante l'esportazione. |
| [setHeight(double value)](#setHeight-double-) | Imposta l'altezza della scatola allineata sull'asse y. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | Ottiene o imposta i segmenti di altezza. |
| [setLength(double value)](#setLength-double-) | Imposta la lunghezza della scatola allineata sull'asse z. |
| [setLengthSegments(int value)](#setLengthSegments-int-) | Imposta i segmenti di lunghezza. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Imposta se questa geometria può ricevere ombra. |
| [setWidth(double value)](#setWidth-double-) | Imposta la larghezza della scatola allineata sull'asse x. |
| [setWidthSegments(int value)](#setWidthSegments-int-) | Imposta i segmenti di larghezza |
| [toMesh()](#toMesh--) | Converti l'oggetto corrente in mesh |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Box() {#Box--}
```
public Box()
```


Inizializza una nuova istanza della classe [Box](../../com.aspose.threed/box).

### Box(double length, double width, double height) {#Box-double-double-double-}
```
public Box(double length, double width, double height)
```


Inizializza una nuova istanza della classe [Box](../../com.aspose.threed/box).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lunghezza | double | Lunghezza della scatola allineata sull'asse z. |
| larghezza | double | Larghezza della scatola allineata sull'asse x. |
| altezza | double | Altezza della scatola allineata sull'asse y. |

### Box(String name, double length, double width, double height, int lengthSegments, int widthSegments, int heightSegments) {#Box-java.lang.String-double-double-double-int-int-int-}
```
public Box(String name, double length, double width, double height, int lengthSegments, int widthSegments, int heightSegments)
```


Inizializza una nuova istanza della classe [Box](../../com.aspose.threed/box).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome della scatola. |
| lunghezza | double | Lunghezza della scatola allineata sull'asse z. |
| larghezza | double | Larghezza della scatola allineata sull'asse x. |
| altezza | double | Altezza della scatola allineata sull'asse y. |
| lengthSegments | int | Segmenti di lunghezza. |
| widthSegments | int | Segmenti di larghezza. |
| heightSegments | int | Segmenti di altezza. |

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
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Restituisce se questa geometria può proiettare ombra

**Returns:**
boolean - se questa geometria può proiettare ombra
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
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Ottiene se escludere questa entità durante l'esportazione.

**Returns:**
boolean - se escludere questa entità durante l'esportazione.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Restituisce l'altezza della scatola allineata sull'asse y.

**Returns:**
double - l'altezza della scatola allineata sull'asse y.
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


Ottiene o imposta i segmenti di altezza.

**Returns:**
int - ottiene o imposta i segmenti di altezza.
### getLength() {#getLength--}
```
public double getLength()
```


Restituisce la lunghezza della scatola allineata sull'asse z.

**Returns:**
double - la lunghezza della scatola allineata sull'asse z.
### getLengthSegments() {#getLengthSegments--}
```
public int getLengthSegments()
```


Ottiene i segmenti di lunghezza.

**Returns:**
int - i segmenti di lunghezza.
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
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Restituisce se questa geometria può ricevere ombra.

**Returns:**
boolean - se questa geometria può ricevere ombra.
### getScene() {#getScene--}
```
public Scene getScene()
```


Ottiene la scena a cui appartiene questo oggetto

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getWidth() {#getWidth--}
```
public double getWidth()
```


Restituisce la larghezza della scatola allineata sull'asse x.

**Returns:**
double - la larghezza della scatola allineata sull'asse x.
### getWidthSegments() {#getWidthSegments--}
```
public int getWidthSegments()
```


Restituisce i segmenti di larghezza

**Returns:**
int - i segmenti di larghezza
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Imposta se questa geometria può proiettare ombra

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Imposta se escludere questa entità durante l'esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Imposta l'altezza della scatola allineata sull'asse y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


Ottiene o imposta i segmenti di altezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setLength(double value) {#setLength-double-}
```
public void setLength(double value)
```


Imposta la lunghezza della scatola allineata sull'asse z.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setLengthSegments(int value) {#setLengthSegments-int-}
```
public void setLengthSegments(int value)
```


Imposta i segmenti di lunghezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Imposta se questa geometria può ricevere ombra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Imposta la larghezza della scatola allineata sull'asse x.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setWidthSegments(int value) {#setWidthSegments-int-}
```
public void setWidthSegments(int value)
```


Imposta i segmenti di larghezza

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Converti l'oggetto corrente in mesh

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The mesh.
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

