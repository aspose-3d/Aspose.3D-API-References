---
title: Frustum
second_title: Aspose.3D for Java API Reference
description: La classe base di  e
type: docs
weight: 69
url: /it/java/com.aspose.threed/frustum/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public abstract class Frustum extends Entity implements IOrientable
```

La classe base di [Camera](../../com.aspose.threed/camera) e [Light](../../com.aspose.threed/light)
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getAspect()](#getAspect--) | Ottiene il rapporto d'aspetto del frustum |
| [getBoundingBox()](#getBoundingBox--) | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | Ottiene la direzione verso cui la fotocamera sta guardando. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Ottiene la chiave del renderer dell'entità registrata nel renderer |
| [getExcluded()](#getExcluded--) | Ottiene se escludere questa entità durante l'esportazione. |
| [getFarPlane()](#getFarPlane--) | Ottiene la distanza del piano lontano del frustum. |
| [getLookAt()](#getLookAt--) | Restituisce la posizione di interesse verso cui la fotocamera sta guardando. |
| [getName()](#getName--) | Ottiene il nome. |
| [getNearPlane()](#getNearPlane--) | Restituisce la distanza del piano vicino del frustum. |
| [getOrthoHeight()](#getOrthoHeight--) | Restituisce l'altezza quando il frustum è in proiezione ortografica. |
| [getParentNode()](#getParentNode--) | Ottiene il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [getParentNodes()](#getParentNodes--) | Ottiene tutti i nodi genitore; un'entità può essere collegata a più nodi genitore per l'instancing della geometria. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getRotationMode()](#getRotationMode--) | Restituisce la modalità di orientamento del frustum. Questa proprietà funziona solo quando il [getTarget](../../com.aspose.threed/frustum\#getTarget) è nullo. |
| [getScene()](#getScene--) | Ottiene la scena a cui appartiene questo oggetto |
| [getTarget()](#getTarget--) | Restituisce il bersaglio verso cui la fotocamera sta guardando. |
| [getUp()](#getUp--) | Restituisce la direzione verso l'alto della fotocamera |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setAspect(double value)](#setAspect-double-) | Imposta il rapporto d'aspetto del frustum |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Imposta la direzione verso cui la fotocamera sta guardando. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Imposta se escludere questa entità durante l'esportazione. |
| [setFarPlane(double value)](#setFarPlane-double-) | Imposta la distanza del piano lontano del frustum. |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Imposta la posizione di interesse verso cui la fotocamera sta guardando. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setNearPlane(double value)](#setNearPlane-double-) | Imposta la distanza del piano vicino del frustum. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Imposta l'altezza quando il frustum è in proiezione ortografica. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Imposta la modalità di orientamento del frustum. Questa proprietà funziona solo quando il [getTarget](../../com.aspose.threed/frustum\#getTarget) è nullo. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Imposta il bersaglio verso cui la fotocamera sta guardando. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Imposta la direzione verso l'alto della fotocamera |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAspect() {#getAspect--}
```
public double getAspect()
```


Ottiene il rapporto d'aspetto del frustum

**Returns:**
double - il rapporto d'aspetto del frustum
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
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


Ottiene la direzione verso cui la fotocamera sta guardando. Le modifiche a questa proprietà influenzeranno anche il [getLookAt](../../com.aspose.threed/frustum\#getLookAt) e il [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
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
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Ottiene la distanza del piano lontano del frustum.

**Returns:**
double - la distanza del piano lontano del frustum.
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Restituisce la posizione di interesse verso cui la fotocamera sta guardando.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Restituisce la distanza del piano vicino del frustum.

**Returns:**
double - la distanza del piano vicino del frustum.
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


Restituisce l'altezza quando il frustum è in proiezione ortografica.

**Returns:**
double - l'altezza quando il frustum è in proiezione ortografica.
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
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


Ottiene la modalità di orientamento del frustum. Questa proprietà funziona solo quando il [getTarget](../../com.aspose.threed/frustum\#getTarget) è nullo. Se il valore è [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), la direzione è sempre calcolata dalla proprietà [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Altrimenti il [getLookAt](../../com.aspose.threed/frustum\#getLookAt) è sempre calcolato da [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


Ottiene la scena a cui appartiene questo oggetto

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTarget() {#getTarget--}
```
public Node getTarget()
```


Ottiene il bersaglio verso cui la fotocamera sta guardando. Se l'utente supporta questa proprietà, dovrebbe essere impostata prima della proprietà [getLookAt](../../com.aspose.threed/frustum\#getLookAt).

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


Restituisce la direzione verso l'alto della fotocamera

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up direction of the camera
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
### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Imposta il rapporto d'aspetto del frustum

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


Imposta la direzione verso cui la fotocamera sta guardando. Le modifiche a questa proprietà influenzeranno anche il [getLookAt](../../com.aspose.threed/frustum\#getLookAt) e il [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Imposta se escludere questa entità durante l'esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Imposta la distanza del piano lontano del frustum.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Imposta la posizione di interesse verso cui la fotocamera sta guardando.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Imposta la distanza del piano vicino del frustum.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


Imposta l'altezza quando il frustum è in proiezione ortografica.

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

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Imposta la modalità di orientamento del frustum. Questa proprietà funziona solo quando il [getTarget](../../com.aspose.threed/frustum\#getTarget) è nullo. Se il valore è [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), la direzione è sempre calcolata dalla proprietà [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Altrimenti il [getLookAt](../../com.aspose.threed/frustum\#getLookAt) è sempre calcolato da [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Nuovo valore |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


Imposta il bersaglio verso cui la fotocamera sta guardando. Se l'utente supporta questa proprietà, dovrebbe essere prima della proprietà [getLookAt](../../com.aspose.threed/frustum\#getLookAt).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nuovo valore |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


Imposta la direzione verso l'alto della fotocamera

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

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

