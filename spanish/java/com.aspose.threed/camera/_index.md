---
title: Camera
second_title: Referencia de API de Aspose.3D para Java
description: La cámara describe el punto de vista del espectador que observa la escena.
type: docs
weight: 28
url: /es/java/com.aspose.threed/camera/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public class Camera extends Frustum implements IOrientable
```

La cámara describe el punto de vista del espectador que observa la escena.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Camera()](#Camera--) | Inicializa una nueva instancia de la clase [Camera](../../com.aspose.threed/camera). |
| [Camera(ProjectionType projectionType)](#Camera-com.aspose.threed.ProjectionType-) | Inicializa una nueva instancia de la clase [Camera](../../com.aspose.threed/camera). |
| [Camera(String name)](#Camera-java.lang.String-) | Inicializa una nueva instancia de la clase [Camera](../../com.aspose.threed/camera). |
| [Camera(String name, ProjectionType projectionType)](#Camera-java.lang.String-com.aspose.threed.ProjectionType-) | Inicializa una nueva instancia de la clase [Camera](../../com.aspose.threed/camera). |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getApertureMode()](#getApertureMode--) | Obtiene el modo de apertura de la cámara |
| [getAspect()](#getAspect--) | Obtiene la relación de aspecto del frustum |
| [getAspectRatio()](#getAspectRatio--) | Obtiene la relación de aspecto del plano de vista. |
| [getBoundingBox()](#getBoundingBox--) | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objetos. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | Obtiene la dirección a la que mira la cámara. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [getExcluded()](#getExcluded--) | Obtiene si se debe excluir esta entidad durante la exportación. |
| [getFarPlane()](#getFarPlane--) | Obtiene la distancia del plano lejano del frustum. |
| [getFieldOfView()](#getFieldOfView--) | Obtiene el campo de visión de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) o [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [getFieldOfViewX()](#getFieldOfViewX--) | Obtiene el campo de visión horizontal de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getFieldOfViewY()](#getFieldOfViewY--) | Obtiene el campo de visión vertical de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getHeight()](#getHeight--) | Obtiene la altura del plano de vista medida en pulgadas |
| [getLookAt()](#getLookAt--) | Obtiene la posición de interés a la que la cámara está mirando. |
| [getMagnification()](#getMagnification--) | Obtiene la ampliación usada en la cámara ortográfica |
| [getName()](#getName--) | Obtiene el nombre. |
| [getNearPlane()](#getNearPlane--) | Obtiene la distancia del plano cercano del frustum. |
| [getOrthoHeight()](#getOrthoHeight--) | Obtiene la altura cuando el frustum está en proyección ortográfica. |
| [getParentNode()](#getParentNode--) | Obtiene el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [getParentNodes()](#getParentNodes--) | Obtiene todos los nodos padres; una entidad puede estar adjunta a varios nodos padres para instanciación de geometría. |
| [getProjectionType()](#getProjectionType--) | Obtiene el tipo de proyección de la cámara. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getRotationMode()](#getRotationMode--) | Obtiene el modo de orientación del frustum. Esta propiedad solo funciona cuando el [getTarget](../../com.aspose.threed/frustum\#getTarget) es nulo. |
| [getScene()](#getScene--) | Obtiene la escena a la que pertenece este objeto. |
| [getTarget()](#getTarget--) | Obtiene el objetivo al que la cámara está mirando. |
| [getUp()](#getUp--) | Obtiene la dirección ascendente de la cámara |
| [getWidth()](#getWidth--) | Obtiene el ancho del plano de vista medido en pulgadas |
| [hashCode()](#hashCode--) |  |
| [moveForward(double distance)](#moveForward-double-) | Mueve la cámara hacia adelante en la dirección o objetivo. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setApertureMode(ApertureMode value)](#setApertureMode-com.aspose.threed.ApertureMode-) | Establece el modo de apertura de la cámara |
| [setAspect(double value)](#setAspect-double-) | Establece la relación de aspecto del frustum |
| [setAspectRatio(double value)](#setAspectRatio-double-) | Establece la relación de aspecto del plano de vista. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Establece la dirección a la que la cámara está mirando. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Establece si se debe excluir esta entidad durante la exportación. |
| [setFarPlane(double value)](#setFarPlane-double-) | Establece la distancia del plano lejano del frustum. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | Establece el campo de visión de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) o [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [setFieldOfViewX(double value)](#setFieldOfViewX-double-) | Establece el campo de visión horizontal de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setFieldOfViewY(double value)](#setFieldOfViewY-double-) | Establece el campo de visión vertical de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setHeight(double value)](#setHeight-double-) | Establece la altura del plano de vista medida en pulgadas |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Establece la posición de interés a la que la cámara está mirando. |
| [setMagnification(Vector2 value)](#setMagnification-com.aspose.threed.Vector2-) | Establece la ampliación usada en la cámara ortográfica |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setNearPlane(double value)](#setNearPlane-double-) | Establece la distancia del plano cercano del frustum. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Establece la altura cuando el frustum está en proyección ortográfica. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [setProjectionType(ProjectionType value)](#setProjectionType-com.aspose.threed.ProjectionType-) | Establece el tipo de proyección de la cámara. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Establece el modo de orientación del frustum. Esta propiedad solo funciona cuando el [getTarget](../../com.aspose.threed/frustum\#getTarget) es nulo. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Establece el objetivo al que la cámara está mirando. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Establece la dirección superior de la cámara |
| [setWidth(double value)](#setWidth-double-) | Establece el ancho del plano de vista medido en pulgadas |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Camera() {#Camera--}
```
public Camera()
```


Inicializa una nueva instancia de la clase [Camera](../../com.aspose.threed/camera).

### Camera(ProjectionType projectionType) {#Camera-com.aspose.threed.ProjectionType-}
```
public Camera(ProjectionType projectionType)
```


Inicializa una nueva instancia de la clase [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Tipo de proyección. |

### Camera(String name) {#Camera-java.lang.String-}
```
public Camera(String name)
```


Inicializa una nueva instancia de la clase [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre. |

### Camera(String name, ProjectionType projectionType) {#Camera-java.lang.String-com.aspose.threed.ProjectionType-}
```
public Camera(String name, ProjectionType projectionType)
```


Inicializa una nueva instancia de la clase [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre. |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Tipo de proyección. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Busca la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyName | java.lang.String | Nombre de la propiedad. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getApertureMode() {#getApertureMode--}
```
public ApertureMode getApertureMode()
```


Obtiene el modo de apertura de la cámara

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode) - the camera's aperture mode
### getAspect() {#getAspect--}
```
public double getAspect()
```


Obtiene la relación de aspecto del frustum

**Returns:**
double - la relación de aspecto del frustum
### getAspectRatio() {#getAspectRatio--}
```
public double getAspectRatio()
```


Obtiene la relación de aspecto del plano de vista.

**Returns:**
double - la relación de aspecto del plano de vista.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objetos.

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


Obtiene la dirección a la que la cámara está mirando. Los cambios en esta propiedad también afectarán a [getLookAt](../../com.aspose.threed/frustum\#getLookAt) y [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Obtiene la clave del renderizador de entidad registrado en el renderizador

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Obtiene si se debe excluir esta entidad durante la exportación.

**Returns:**
boolean - si se debe excluir esta entidad durante la exportación.
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Obtiene la distancia del plano lejano del frustum.

**Returns:**
double - la distancia del plano lejano del frustum.
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


Obtiene el campo de visión de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) o [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Returns:**
double - el campo de visión de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) o [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)
### getFieldOfViewX() {#getFieldOfViewX--}
```
public double getFieldOfViewX()
```


Obtiene el campo de visión horizontal de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
double - el campo de visión horizontal de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getFieldOfViewY() {#getFieldOfViewY--}
```
public double getFieldOfViewY()
```


Obtiene el campo de visión vertical de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
double - el campo de visión vertical de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtiene la altura del plano de vista medida en pulgadas

**Returns:**
double - la altura del plano de vista medida en pulgadas
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Obtiene la posición de interés a la que la cámara está mirando.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getMagnification() {#getMagnification--}
```
public Vector2 getMagnification()
```


Obtiene la ampliación usada en la cámara ortográfica

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the magnification used in orthographic camera
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre.

**Returns:**
java.lang.String - el nombre.
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Obtiene la distancia del plano cercano del frustum.

**Returns:**
double - la distancia del plano cercano del frustum.
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


Obtiene la altura cuando el frustum está en proyección ortográfica.

**Returns:**
double - la altura cuando el frustum está en proyección ortográfica.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Obtiene el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Obtiene todos los nodos padres; una entidad puede estar adjunta a varios nodos padres para instanciación de geometría.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para instanciación de geometría
### getProjectionType() {#getProjectionType--}
```
public ProjectionType getProjectionType()
```


Obtiene el tipo de proyección de la cámara. Por defecto se usa la proyección en perspectiva.

**Returns:**
[ProjectionType](../../com.aspose.threed/projectiontype) - the camera's projection type. By default the perspective projection is used.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Obtiene la colección de todas las propiedades.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Obtiene el valor de la propiedad especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Nombre de la propiedad |

**Returns:**
java.lang.Object - El valor de la propiedad encontrada
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


Obtiene el modo de orientación del frustum. Esta propiedad solo funciona cuando el [getTarget](../../com.aspose.threed/frustum\#getTarget) es nulo. Si el valor es [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), la dirección siempre se calcula mediante la propiedad [getLookAt](../../com.aspose.threed/frustum\#getLookAt). De lo contrario, el [getLookAt](../../com.aspose.threed/frustum\#getLookAt) siempre se calcula mediante el [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtiene la escena a la que pertenece este objeto.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTarget() {#getTarget--}
```
public Node getTarget()
```


Obtiene el objetivo al que la cámara está mirando. Si el usuario admite esta propiedad, debe preceder a la propiedad [getLookAt](../../com.aspose.threed/frustum\#getLookAt).

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


Obtiene la dirección ascendente de la cámara

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up direction of the camera
### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtiene el ancho del plano de vista medido en pulgadas

**Returns:**
double - el ancho del plano de vista medido en pulgadas
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


Mueve la cámara hacia adelante en la dirección o objetivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| distancia | double | Cuánto tiempo mover hacia adelante |

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


Elimina una propiedad dinámica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Qué propiedad eliminar |

**Returns:**
boolean - verdadero si la propiedad se elimina correctamente
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Elimina la propiedad especificada identificada por nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Qué propiedad eliminar |

**Returns:**
boolean - verdadero si la propiedad se elimina correctamente
### setApertureMode(ApertureMode value) {#setApertureMode-com.aspose.threed.ApertureMode-}
```
public void setApertureMode(ApertureMode value)
```


Establece el modo de apertura de la cámara

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ApertureMode](../../com.aspose.threed/aperturemode) | Nuevo valor |

### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Establece la relación de aspecto del frustum

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setAspectRatio(double value) {#setAspectRatio-double-}
```
public void setAspectRatio(double value)
```


Establece la relación de aspecto del plano de vista.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


Establece la dirección a la que la cámara está mirando. Los cambios en esta propiedad también afectarán a [getLookAt](../../com.aspose.threed/frustum\#getLookAt) y [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Establece si se debe excluir esta entidad durante la exportación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Establece la distancia del plano lejano del frustum.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


Establece el campo de visión de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) o [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setFieldOfViewX(double value) {#setFieldOfViewX-double-}
```
public void setFieldOfViewX(double value)
```


Establece el campo de visión horizontal de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setFieldOfViewY(double value) {#setFieldOfViewY-double-}
```
public void setFieldOfViewY(double value)
```


Establece el campo de visión vertical de la cámara en grados, esta propiedad se usa solo cuando ApertureMode es [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Establece la altura del plano de vista medida en pulgadas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Establece la posición de interés a la que la cámara está mirando.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setMagnification(Vector2 value) {#setMagnification-com.aspose.threed.Vector2-}
```
public void setMagnification(Vector2 value)
```


Establece la ampliación usada en la cámara ortográfica

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuevo valor |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Establece el nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Establece la distancia del plano cercano del frustum.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


Establece la altura cuando el frustum está en proyección ortográfica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nuevo valor |

### setProjectionType(ProjectionType value) {#setProjectionType-com.aspose.threed.ProjectionType-}
```
public void setProjectionType(ProjectionType value)
```


Establece el tipo de proyección de la cámara. Por defecto se usa la proyección en perspectiva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ProjectionType](../../com.aspose.threed/projectiontype) | Nuevo valor |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Establece el valor de la propiedad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Nombre de la propiedad |
| valor | java.lang.Object | El valor de la propiedad |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Establece el modo de orientación del frustum. Esta propiedad solo funciona cuando el [getTarget](../../com.aspose.threed/frustum\#getTarget) es nulo. Si el valor es [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), la dirección siempre se calcula mediante la propiedad [getLookAt](../../com.aspose.threed/frustum\#getLookAt). De lo contrario, el [getLookAt](../../com.aspose.threed/frustum\#getLookAt) siempre se calcula mediante el [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Nuevo valor |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


Establece el objetivo al que la cámara está mirando. Si el usuario admite esta propiedad, debe ser antes de la propiedad [getLookAt](../../com.aspose.threed/frustum\#getLookAt).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nuevo valor |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


Establece la dirección superior de la cámara

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Establece el ancho del plano de vista medido en pulgadas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

