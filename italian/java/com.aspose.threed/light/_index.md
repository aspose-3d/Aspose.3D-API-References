---
title: Light
second_title: Aspose.3D for Java API Reference
description: La luce illumina la scena.
type: docs
weight: 94
url: /it/java/com.aspose.threed/light/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)
```
public class Light extends Frustum
```

La luce illumina la scena.

La formula per calcolare l'attenuazione totale della luce è:  A = ConstantAttenuation + (Dist \* LinearAttenuation) + ((Dist^2) \* QuadraticAttenuation)
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Light()](#Light--) | Inizializza una nuova istanza della classe [Light](../../com.aspose.threed/light). |
| [Light(String name)](#Light-java.lang.String-) | Inizializza una nuova istanza della classe [Light](../../com.aspose.threed/light). |
| [Light(String name, LightType type)](#Light-java.lang.String-com.aspose.threed.LightType-) | Inizializza una nuova istanza della classe [Light](../../com.aspose.threed/light). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getAspect()](#getAspect--) | Ottiene il rapporto d'aspetto del frustum |
| [getBoundingBox()](#getBoundingBox--) | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |
| [getCastLight()](#getCastLight--) | Ottiene se l'istanza corrente di luce può illuminare altri oggetti. |
| [getCastShadows()](#getCastShadows--) | Ottiene se la luce può proiettare ombre su altri oggetti. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Ottiene il colore della luce |
| [getConstantAttenuation()](#getConstantAttenuation--) | Ottiene l'attenuazione costante per calcolare l'attenuazione totale della luce |
| [getDirection()](#getDirection--) | Ottiene la direzione verso cui la fotocamera sta guardando. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Ottiene la chiave del renderer dell'entità registrata nel renderer |
| [getExcluded()](#getExcluded--) | Ottiene se escludere questa entità durante l'esportazione. |
| [getFalloff()](#getFalloff--) | Ottiene l'angolo del cono di decadimento (in gradi). |
| [getFarPlane()](#getFarPlane--) | Ottiene la distanza del piano lontano del frustum. |
| [getHotSpot()](#getHotSpot--) | Restituisce l'angolo del cono del punto caldo (in gradi). |
| [getIntensity()](#getIntensity--) | Restituisce l'intensità della luce, il valore predefinito è 100 |
| [getLightType()](#getLightType--) | Restituisce il tipo di luce |
| [getLinearAttenuation()](#getLinearAttenuation--) | Restituisce l'attenuazione lineare per calcolare l'attenuazione totale della luce |
| [getLookAt()](#getLookAt--) | Restituisce la posizione di interesse verso cui la fotocamera sta guardando. |
| [getName()](#getName--) | Ottiene il nome. |
| [getNearPlane()](#getNearPlane--) | Restituisce la distanza del piano vicino del frustum. |
| [getOrthoHeight()](#getOrthoHeight--) | Restituisce l'altezza quando il frustum è in proiezione ortografica. |
| [getParentNode()](#getParentNode--) | Ottiene il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [getParentNodes()](#getParentNodes--) | Ottiene tutti i nodi genitore; un'entità può essere collegata a più nodi genitore per l'instancing della geometria. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getQuadraticAttenuation()](#getQuadraticAttenuation--) | Restituisce l'attenuazione quadratica per calcolare l'attenuazione totale della luce |
| [getRotationMode()](#getRotationMode--) | Restituisce la modalità di orientamento del frustum. Questa proprietà funziona solo quando il [getTarget](../../com.aspose.threed/frustum\#getTarget) è nullo. |
| [getScene()](#getScene--) | Ottiene la scena a cui appartiene questo oggetto |
| [getShadowColor()](#getShadowColor--) | Restituisce il colore dell'ombra. |
| [getTarget()](#getTarget--) | Restituisce il bersaglio verso cui la fotocamera sta guardando. |
| [getUp()](#getUp--) | Restituisce la direzione verso l'alto della fotocamera |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setAspect(double value)](#setAspect-double-) | Imposta il rapporto d'aspetto del frustum |
| [setCastLight(boolean value)](#setCastLight-boolean-) | Imposta se l'istanza corrente della luce può illuminare altri oggetti. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Imposta se la luce può proiettare ombre su altri oggetti. |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Imposta il colore della luce |
| [setConstantAttenuation(double value)](#setConstantAttenuation-double-) | Imposta l'attenuazione costante per calcolare l'attenuazione totale della luce |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Imposta la direzione verso cui la fotocamera sta guardando. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Imposta se escludere questa entità durante l'esportazione. |
| [setFalloff(double value)](#setFalloff-double-) | Imposta l'angolo del cono di decadimento (in gradi). |
| [setFarPlane(double value)](#setFarPlane-double-) | Imposta la distanza del piano lontano del frustum. |
| [setHotSpot(double value)](#setHotSpot-double-) | Imposta l'angolo del cono del punto caldo (in gradi). |
| [setIntensity(double value)](#setIntensity-double-) | Imposta l'intensità della luce, il valore predefinito è 100 |
| [setLightType(LightType value)](#setLightType-com.aspose.threed.LightType-) | Imposta il tipo di luce |
| [setLinearAttenuation(double value)](#setLinearAttenuation-double-) | Imposta l'attenuazione lineare per calcolare l'attenuazione totale della luce |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Imposta la posizione di interesse verso cui la fotocamera sta guardando. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setNearPlane(double value)](#setNearPlane-double-) | Imposta la distanza del piano vicino del frustum. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Imposta l'altezza quando il frustum è in proiezione ortografica. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setQuadraticAttenuation(double value)](#setQuadraticAttenuation-double-) | Imposta l'attenuazione quadratica per calcolare l'attenuazione totale della luce |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Imposta la modalità di orientamento del frustum. Questa proprietà funziona solo quando il [getTarget](../../com.aspose.threed/frustum\#getTarget) è nullo. |
| [setShadowColor(Vector3 value)](#setShadowColor-com.aspose.threed.Vector3-) | Imposta il colore dell'ombra. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Imposta il bersaglio verso cui la fotocamera sta guardando. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Imposta la direzione verso l'alto della fotocamera |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Light() {#Light--}
```
public Light()
```


Inizializza una nuova istanza della classe [Light](../../com.aspose.threed/light).

### Light(String name) {#Light-java.lang.String-}
```
public Light(String name)
```


Inizializza una nuova istanza della classe [Light](../../com.aspose.threed/light).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome |

### Light(String name, LightType type) {#Light-java.lang.String-com.aspose.threed.LightType-}
```
public Light(String name, LightType type)
```


Inizializza una nuova istanza della classe [Light](../../com.aspose.threed/light).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome |
| type | [LightType](../../com.aspose.threed/lighttype) | Nuovo tipo di luce |

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
### getCastLight() {#getCastLight--}
```
public boolean getCastLight()
```


Ottiene se l'istanza corrente di luce può illuminare altri oggetti.

**Returns:**
boolean - se l'istanza corrente della luce può illuminare altri oggetti.
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Ottiene se la luce può proiettare ombre su altri oggetti.

**Returns:**
boolean - se la luce può proiettare ombre su altri oggetti.
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


Ottiene il colore della luce

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the light's color
### getConstantAttenuation() {#getConstantAttenuation--}
```
public double getConstantAttenuation()
```


Ottiene l'attenuazione costante per calcolare l'attenuazione totale della luce

**Returns:**
double - l'attenuazione costante per calcolare l'attenuazione totale della luce
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
### getFalloff() {#getFalloff--}
```
public double getFalloff()
```


Ottiene l'angolo del cono di decadimento (in gradi).

**Returns:**
double - l'angolo del cono di decadimento (in gradi).
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Ottiene la distanza del piano lontano del frustum.

**Returns:**
double - la distanza del piano lontano del frustum.
### getHotSpot() {#getHotSpot--}
```
public double getHotSpot()
```


Restituisce l'angolo del cono del punto caldo (in gradi).

**Returns:**
double - l'angolo del cono hotspot (in gradi).
### getIntensity() {#getIntensity--}
```
public double getIntensity()
```


Restituisce l'intensità della luce, il valore predefinito è 100

**Returns:**
double - l'intensità della luce, il valore predefinito è 100
### getLightType() {#getLightType--}
```
public LightType getLightType()
```


Restituisce il tipo di luce

**Returns:**
[LightType](../../com.aspose.threed/lighttype) - the light's type
### getLinearAttenuation() {#getLinearAttenuation--}
```
public double getLinearAttenuation()
```


Restituisce l'attenuazione lineare per calcolare l'attenuazione totale della luce

**Returns:**
double - l'attenuazione lineare per calcolare l'attenuazione totale della luce
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
### getQuadraticAttenuation() {#getQuadraticAttenuation--}
```
public double getQuadraticAttenuation()
```


Restituisce l'attenuazione quadratica per calcolare l'attenuazione totale della luce

**Returns:**
double - l'attenuazione quadratica per calcolare l'attenuazione totale della luce
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
### getShadowColor() {#getShadowColor--}
```
public Vector3 getShadowColor()
```


Restituisce il colore dell'ombra.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the shadow's color.
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

### setCastLight(boolean value) {#setCastLight-boolean-}
```
public void setCastLight(boolean value)
```


Imposta se l'istanza corrente della luce può illuminare altri oggetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Imposta se la luce può proiettare ombre su altri oggetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Imposta il colore della luce

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setConstantAttenuation(double value) {#setConstantAttenuation-double-}
```
public void setConstantAttenuation(double value)
```


Imposta l'attenuazione costante per calcolare l'attenuazione totale della luce

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

### setFalloff(double value) {#setFalloff-double-}
```
public void setFalloff(double value)
```


Imposta l'angolo del cono di decadimento (in gradi).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Imposta la distanza del piano lontano del frustum.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setHotSpot(double value) {#setHotSpot-double-}
```
public void setHotSpot(double value)
```


Imposta l'angolo del cono del punto caldo (in gradi).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setIntensity(double value) {#setIntensity-double-}
```
public void setIntensity(double value)
```


Imposta l'intensità della luce, il valore predefinito è 100

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setLightType(LightType value) {#setLightType-com.aspose.threed.LightType-}
```
public void setLightType(LightType value)
```


Imposta il tipo di luce

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [LightType](../../com.aspose.threed/lighttype) | Nuovo valore |

### setLinearAttenuation(double value) {#setLinearAttenuation-double-}
```
public void setLinearAttenuation(double value)
```


Imposta l'attenuazione lineare per calcolare l'attenuazione totale della luce

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

### setQuadraticAttenuation(double value) {#setQuadraticAttenuation-double-}
```
public void setQuadraticAttenuation(double value)
```


Imposta l'attenuazione quadratica per calcolare l'attenuazione totale della luce

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Imposta la modalità di orientamento del frustum. Questa proprietà funziona solo quando il [getTarget](../../com.aspose.threed/frustum\#getTarget) è nullo. Se il valore è [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), la direzione è sempre calcolata dalla proprietà [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Altrimenti il [getLookAt](../../com.aspose.threed/frustum\#getLookAt) è sempre calcolato da [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Nuovo valore |

### setShadowColor(Vector3 value) {#setShadowColor-com.aspose.threed.Vector3-}
```
public void setShadowColor(Vector3 value)
```


Imposta il colore dell'ombra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

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

