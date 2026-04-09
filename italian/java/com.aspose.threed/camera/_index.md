---
title: Camera
second_title: Aspose.3D for Java API Reference
description: La camera descrive il punto di vista dell'osservatore che guarda la scena.
type: docs
weight: 28
url: /it/java/com.aspose.threed/camera/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public class Camera extends Frustum implements IOrientable
```

La camera descrive il punto di vista dell'osservatore che guarda la scena.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Camera()](#Camera--) | Inizializza una nuova istanza della classe [Camera](../../com.aspose.threed/camera). |
| [Camera(ProjectionType projectionType)](#Camera-com.aspose.threed.ProjectionType-) | Inizializza una nuova istanza della classe [Camera](../../com.aspose.threed/camera). |
| [Camera(String name)](#Camera-java.lang.String-) | Inizializza una nuova istanza della classe [Camera](../../com.aspose.threed/camera). |
| [Camera(String name, ProjectionType projectionType)](#Camera-java.lang.String-com.aspose.threed.ProjectionType-) | Inizializza una nuova istanza della classe [Camera](../../com.aspose.threed/camera). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getApertureMode()](#getApertureMode--) | Ottiene la modalità di apertura della fotocamera |
| [getAspect()](#getAspect--) | Ottiene il rapporto d'aspetto del frustum |
| [getAspectRatio()](#getAspectRatio--) | Ottiene il rapporto d'aspetto del piano di visualizzazione. |
| [getBoundingBox()](#getBoundingBox--) | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | Ottiene la direzione verso cui la fotocamera sta guardando. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Ottiene la chiave del renderer dell'entità registrata nel renderer |
| [getExcluded()](#getExcluded--) | Ottiene se escludere questa entità durante l'esportazione. |
| [getFarPlane()](#getFarPlane--) | Ottiene la distanza del piano lontano del frustum. |
| [getFieldOfView()](#getFieldOfView--) | Ottiene il campo visivo della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) o [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [getFieldOfViewX()](#getFieldOfViewX--) | Ottiene il campo visivo orizzontale della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getFieldOfViewY()](#getFieldOfViewY--) | Ottiene il campo visivo verticale della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getHeight()](#getHeight--) | Ottiene l'altezza del piano di visualizzazione misurata in pollici |
| [getLookAt()](#getLookAt--) | Restituisce la posizione di interesse verso cui la fotocamera sta guardando. |
| [getMagnification()](#getMagnification--) | Ottiene l'ingrandimento usato nella fotocamera ortografica |
| [getName()](#getName--) | Ottiene il nome. |
| [getNearPlane()](#getNearPlane--) | Restituisce la distanza del piano vicino del frustum. |
| [getOrthoHeight()](#getOrthoHeight--) | Restituisce l'altezza quando il frustum è in proiezione ortografica. |
| [getParentNode()](#getParentNode--) | Ottiene il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [getParentNodes()](#getParentNodes--) | Ottiene tutti i nodi genitore; un'entità può essere collegata a più nodi genitore per l'instancing della geometria. |
| [getProjectionType()](#getProjectionType--) | Ottiene il tipo di proiezione della fotocamera. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getRotationMode()](#getRotationMode--) | Restituisce la modalità di orientamento del frustum. Questa proprietà funziona solo quando il [getTarget](../../com.aspose.threed/frustum\#getTarget) è nullo. |
| [getScene()](#getScene--) | Ottiene la scena a cui appartiene questo oggetto |
| [getTarget()](#getTarget--) | Restituisce il bersaglio verso cui la fotocamera sta guardando. |
| [getUp()](#getUp--) | Restituisce la direzione verso l'alto della fotocamera |
| [getWidth()](#getWidth--) | Ottiene la larghezza del piano di visualizzazione misurata in pollici |
| [hashCode()](#hashCode--) |  |
| [moveForward(double distance)](#moveForward-double-) | Sposta la fotocamera in avanti verso la sua direzione o bersaglio. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setApertureMode(ApertureMode value)](#setApertureMode-com.aspose.threed.ApertureMode-) | Imposta la modalità di apertura della fotocamera |
| [setAspect(double value)](#setAspect-double-) | Imposta il rapporto d'aspetto del frustum |
| [setAspectRatio(double value)](#setAspectRatio-double-) | Imposta il rapporto d'aspetto del piano di visualizzazione. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Imposta la direzione verso cui la fotocamera sta guardando. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Imposta se escludere questa entità durante l'esportazione. |
| [setFarPlane(double value)](#setFarPlane-double-) | Imposta la distanza del piano lontano del frustum. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | Imposta il campo visivo della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) o [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [setFieldOfViewX(double value)](#setFieldOfViewX-double-) | Imposta il campo visivo orizzontale della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setFieldOfViewY(double value)](#setFieldOfViewY-double-) | Imposta il campo visivo verticale della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setHeight(double value)](#setHeight-double-) | Imposta l'altezza del piano di visualizzazione misurata in pollici |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Imposta la posizione di interesse verso cui la fotocamera sta guardando. |
| [setMagnification(Vector2 value)](#setMagnification-com.aspose.threed.Vector2-) | Imposta l'ingrandimento usato nella fotocamera ortografica |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setNearPlane(double value)](#setNearPlane-double-) | Imposta la distanza del piano vicino del frustum. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Imposta l'altezza quando il frustum è in proiezione ortografica. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [setProjectionType(ProjectionType value)](#setProjectionType-com.aspose.threed.ProjectionType-) | Imposta il tipo di proiezione della fotocamera. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Imposta la modalità di orientamento del frustum. Questa proprietà funziona solo quando il [getTarget](../../com.aspose.threed/frustum\#getTarget) è nullo. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Imposta il bersaglio verso cui la fotocamera sta guardando. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Imposta la direzione verso l'alto della fotocamera |
| [setWidth(double value)](#setWidth-double-) | Imposta la larghezza del piano di visualizzazione misurata in pollici |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Camera() {#Camera--}
```
public Camera()
```


Inizializza una nuova istanza della classe [Camera](../../com.aspose.threed/camera).

### Camera(ProjectionType projectionType) {#Camera-com.aspose.threed.ProjectionType-}
```
public Camera(ProjectionType projectionType)
```


Inizializza una nuova istanza della classe [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Tipo di proiezione. |

### Camera(String name) {#Camera-java.lang.String-}
```
public Camera(String name)
```


Inizializza una nuova istanza della classe [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome. |

### Camera(String name, ProjectionType projectionType) {#Camera-java.lang.String-com.aspose.threed.ProjectionType-}
```
public Camera(String name, ProjectionType projectionType)
```


Inizializza una nuova istanza della classe [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome. |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Tipo di proiezione. |

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
### getApertureMode() {#getApertureMode--}
```
public ApertureMode getApertureMode()
```


Ottiene la modalità di apertura della fotocamera

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode) - the camera's aperture mode
### getAspect() {#getAspect--}
```
public double getAspect()
```


Ottiene il rapporto d'aspetto del frustum

**Returns:**
double - il rapporto d'aspetto del frustum
### getAspectRatio() {#getAspectRatio--}
```
public double getAspectRatio()
```


Ottiene il rapporto d'aspetto del piano di visualizzazione.

**Returns:**
double - il rapporto d'aspetto del piano di visualizzazione.
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
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


Ottiene il campo visivo della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) o [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Returns:**
double - il campo visivo della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) o [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)
### getFieldOfViewX() {#getFieldOfViewX--}
```
public double getFieldOfViewX()
```


Ottiene il campo visivo orizzontale della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
double - il campo visivo orizzontale della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getFieldOfViewY() {#getFieldOfViewY--}
```
public double getFieldOfViewY()
```


Ottiene il campo visivo verticale della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
double - il campo visivo verticale della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getHeight() {#getHeight--}
```
public double getHeight()
```


Ottiene l'altezza del piano di visualizzazione misurata in pollici

**Returns:**
double - l'altezza del piano di visualizzazione misurata in pollici
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Restituisce la posizione di interesse verso cui la fotocamera sta guardando.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getMagnification() {#getMagnification--}
```
public Vector2 getMagnification()
```


Ottiene l'ingrandimento usato nella fotocamera ortografica

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the magnification used in orthographic camera
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
### getProjectionType() {#getProjectionType--}
```
public ProjectionType getProjectionType()
```


Ottiene il tipo di proiezione della fotocamera. Per impostazione predefinita viene utilizzata la proiezione prospettica.

**Returns:**
[ProjectionType](../../com.aspose.threed/projectiontype) - the camera's projection type. By default the perspective projection is used.
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
### getWidth() {#getWidth--}
```
public double getWidth()
```


Ottiene la larghezza del piano di visualizzazione misurata in pollici

**Returns:**
double - la larghezza del piano di visualizzazione misurata in pollici
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### moveForward(double distance) {#moveForward-double-}
```
public void moveForward(double distance)
```


Sposta la fotocamera in avanti verso la sua direzione o bersaglio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| distanza | double | Quanto tempo muoversi in avanti |

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
### setApertureMode(ApertureMode value) {#setApertureMode-com.aspose.threed.ApertureMode-}
```
public void setApertureMode(ApertureMode value)
```


Imposta la modalità di apertura della fotocamera

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ApertureMode](../../com.aspose.threed/aperturemode) | Nuovo valore |

### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Imposta il rapporto d'aspetto del frustum

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setAspectRatio(double value) {#setAspectRatio-double-}
```
public void setAspectRatio(double value)
```


Imposta il rapporto d'aspetto del piano di visualizzazione.

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

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


Imposta il campo visivo della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) o [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setFieldOfViewX(double value) {#setFieldOfViewX-double-}
```
public void setFieldOfViewX(double value)
```


Imposta il campo visivo orizzontale della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setFieldOfViewY(double value) {#setFieldOfViewY-double-}
```
public void setFieldOfViewY(double value)
```


Imposta il campo visivo verticale della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Imposta l'altezza del piano di visualizzazione misurata in pollici

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

### setMagnification(Vector2 value) {#setMagnification-com.aspose.threed.Vector2-}
```
public void setMagnification(Vector2 value)
```


Imposta l'ingrandimento usato nella fotocamera ortografica

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuovo valore |

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

### setProjectionType(ProjectionType value) {#setProjectionType-com.aspose.threed.ProjectionType-}
```
public void setProjectionType(ProjectionType value)
```


Imposta il tipo di proiezione della fotocamera. Per impostazione predefinita viene utilizzata la proiezione prospettica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ProjectionType](../../com.aspose.threed/projectiontype) | Nuovo valore |

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

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Imposta la larghezza del piano di visualizzazione misurata in pollici

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

