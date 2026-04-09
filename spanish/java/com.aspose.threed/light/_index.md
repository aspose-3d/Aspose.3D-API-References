---
title: Light
second_title: Referencia de API de Aspose.3D para Java
description: La luz ilumina la escena.
type: docs
weight: 94
url: /es/java/com.aspose.threed/light/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)
```
public class Light extends Frustum
```

La luz ilumina la escena.

La fórmula para calcular la atenuación total de la luz es:  A = ConstantAttenuation + (Dist \* LinearAttenuation) + ((Dist^2) \* QuadraticAttenuation)
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Light()](#Light--) | Inicializa una nueva instancia de la clase [Light](../../com.aspose.threed/light). |
| [Light(String name)](#Light-java.lang.String-) | Inicializa una nueva instancia de la clase [Light](../../com.aspose.threed/light). |
| [Light(String name, LightType type)](#Light-java.lang.String-com.aspose.threed.LightType-) | Inicializa una nueva instancia de la clase [Light](../../com.aspose.threed/light). |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getAspect()](#getAspect--) | Obtiene la relación de aspecto del frustum |
| [getBoundingBox()](#getBoundingBox--) | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objetos. |
| [getCastLight()](#getCastLight--) | Obtiene si la instancia actual de Light puede iluminar otros objetos. |
| [getCastShadows()](#getCastShadows--) | Obtiene si la luz puede proyectar sombras sobre otros objetos. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Obtiene el color de la luz |
| [getConstantAttenuation()](#getConstantAttenuation--) | Obtiene la atenuación constante para calcular la atenuación total de la luz |
| [getDirection()](#getDirection--) | Obtiene la dirección a la que mira la cámara. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [getExcluded()](#getExcluded--) | Obtiene si se debe excluir esta entidad durante la exportación. |
| [getFalloff()](#getFalloff--) | Obtiene el ángulo del cono de caída (en grados). |
| [getFarPlane()](#getFarPlane--) | Obtiene la distancia del plano lejano del frustum. |
| [getHotSpot()](#getHotSpot--) | Obtiene el ángulo del cono del punto caliente(en grados). |
| [getIntensity()](#getIntensity--) | Obtiene la intensidad de la luz, el valor predeterminado es 100 |
| [getLightType()](#getLightType--) | Obtiene el tipo de la luz |
| [getLinearAttenuation()](#getLinearAttenuation--) | Obtiene la atenuación lineal para calcular la atenuación total de la luz |
| [getLookAt()](#getLookAt--) | Obtiene la posición de interés a la que la cámara está mirando. |
| [getName()](#getName--) | Obtiene el nombre. |
| [getNearPlane()](#getNearPlane--) | Obtiene la distancia del plano cercano del frustum. |
| [getOrthoHeight()](#getOrthoHeight--) | Obtiene la altura cuando el frustum está en proyección ortográfica. |
| [getParentNode()](#getParentNode--) | Obtiene el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [getParentNodes()](#getParentNodes--) | Obtiene todos los nodos padres; una entidad puede estar adjunta a varios nodos padres para instanciación de geometría. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getQuadraticAttenuation()](#getQuadraticAttenuation--) | Obtiene la atenuación cuadrática para calcular la atenuación total de la luz |
| [getRotationMode()](#getRotationMode--) | Obtiene el modo de orientación del frustum. Esta propiedad solo funciona cuando el [getTarget](../../com.aspose.threed/frustum\#getTarget) es nulo. |
| [getScene()](#getScene--) | Obtiene la escena a la que pertenece este objeto. |
| [getShadowColor()](#getShadowColor--) | Obtiene el color de la sombra. |
| [getTarget()](#getTarget--) | Obtiene el objetivo al que la cámara está mirando. |
| [getUp()](#getUp--) | Obtiene la dirección ascendente de la cámara |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setAspect(double value)](#setAspect-double-) | Establece la relación de aspecto del frustum |
| [setCastLight(boolean value)](#setCastLight-boolean-) | Establece si la instancia actual de luz puede iluminar otros objetos. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Establece si la luz puede proyectar sombras sobre otros objetos. |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Establece el color de la luz |
| [setConstantAttenuation(double value)](#setConstantAttenuation-double-) | Establece la atenuación constante para calcular la atenuación total de la luz |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Establece la dirección a la que la cámara está mirando. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Establece si se debe excluir esta entidad durante la exportación. |
| [setFalloff(double value)](#setFalloff-double-) | Establece el ángulo del cono de caída (en grados). |
| [setFarPlane(double value)](#setFarPlane-double-) | Establece la distancia del plano lejano del frustum. |
| [setHotSpot(double value)](#setHotSpot-double-) | Establece el ángulo del cono del punto caliente(en grados). |
| [setIntensity(double value)](#setIntensity-double-) | Establece la intensidad de la luz, el valor predeterminado es 100 |
| [setLightType(LightType value)](#setLightType-com.aspose.threed.LightType-) | Establece el tipo de la luz |
| [setLinearAttenuation(double value)](#setLinearAttenuation-double-) | Establece la atenuación lineal para calcular la atenuación total de la luz |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Establece la posición de interés a la que la cámara está mirando. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setNearPlane(double value)](#setNearPlane-double-) | Establece la distancia del plano cercano del frustum. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Establece la altura cuando el frustum está en proyección ortográfica. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setQuadraticAttenuation(double value)](#setQuadraticAttenuation-double-) | Establece la atenuación cuadrática para calcular la atenuación total de la luz |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Establece el modo de orientación del frustum. Esta propiedad solo funciona cuando el [getTarget](../../com.aspose.threed/frustum\#getTarget) es nulo. |
| [setShadowColor(Vector3 value)](#setShadowColor-com.aspose.threed.Vector3-) | Establece el color de la sombra. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Establece el objetivo al que la cámara está mirando. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Establece la dirección superior de la cámara |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Light() {#Light--}
```
public Light()
```


Inicializa una nueva instancia de la clase [Light](../../com.aspose.threed/light).

### Light(String name) {#Light-java.lang.String-}
```
public Light(String name)
```


Inicializa una nueva instancia de la clase [Light](../../com.aspose.threed/light).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre |

### Light(String name, LightType type) {#Light-java.lang.String-com.aspose.threed.LightType-}
```
public Light(String name, LightType type)
```


Inicializa una nueva instancia de la clase [Light](../../com.aspose.threed/light).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre |
| type | [LightType](../../com.aspose.threed/lighttype) | Nuevo tipo de luz |

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
### getAspect() {#getAspect--}
```
public double getAspect()
```


Obtiene la relación de aspecto del frustum

**Returns:**
double - la relación de aspecto del frustum
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
### getCastLight() {#getCastLight--}
```
public boolean getCastLight()
```


Obtiene si la instancia actual de Light puede iluminar otros objetos.

**Returns:**
boolean - si la instancia actual de luz puede iluminar otros objetos.
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Obtiene si la luz puede proyectar sombras sobre otros objetos.

**Returns:**
boolean - si la luz puede proyectar sombras sobre otros objetos.
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


Obtiene el color de la luz

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the light's color
### getConstantAttenuation() {#getConstantAttenuation--}
```
public double getConstantAttenuation()
```


Obtiene la atenuación constante para calcular la atenuación total de la luz

**Returns:**
double - la atenuación constante para calcular la atenuación total de la luz
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
### getFalloff() {#getFalloff--}
```
public double getFalloff()
```


Obtiene el ángulo del cono de caída (en grados).

**Returns:**
double - el ángulo del cono de caída (en grados).
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Obtiene la distancia del plano lejano del frustum.

**Returns:**
double - la distancia del plano lejano del frustum.
### getHotSpot() {#getHotSpot--}
```
public double getHotSpot()
```


Obtiene el ángulo del cono del punto caliente(en grados).

**Returns:**
double - el ángulo del cono del punto caliente (en grados).
### getIntensity() {#getIntensity--}
```
public double getIntensity()
```


Obtiene la intensidad de la luz, el valor predeterminado es 100

**Returns:**
double - la intensidad de la luz, el valor predeterminado es 100
### getLightType() {#getLightType--}
```
public LightType getLightType()
```


Obtiene el tipo de la luz

**Returns:**
[LightType](../../com.aspose.threed/lighttype) - the light's type
### getLinearAttenuation() {#getLinearAttenuation--}
```
public double getLinearAttenuation()
```


Obtiene la atenuación lineal para calcular la atenuación total de la luz

**Returns:**
double - la atenuación lineal para calcular la atenuación total de la luz
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Obtiene la posición de interés a la que la cámara está mirando.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
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
### getQuadraticAttenuation() {#getQuadraticAttenuation--}
```
public double getQuadraticAttenuation()
```


Obtiene la atenuación cuadrática para calcular la atenuación total de la luz

**Returns:**
double - la atenuación cuadrática para calcular la atenuación total de la luz
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
### getShadowColor() {#getShadowColor--}
```
public Vector3 getShadowColor()
```


Obtiene el color de la sombra.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the shadow's color.
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
### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Establece la relación de aspecto del frustum

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setCastLight(boolean value) {#setCastLight-boolean-}
```
public void setCastLight(boolean value)
```


Establece si la instancia actual de luz puede iluminar otros objetos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Establece si la luz puede proyectar sombras sobre otros objetos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Establece el color de la luz

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setConstantAttenuation(double value) {#setConstantAttenuation-double-}
```
public void setConstantAttenuation(double value)
```


Establece la atenuación constante para calcular la atenuación total de la luz

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

### setFalloff(double value) {#setFalloff-double-}
```
public void setFalloff(double value)
```


Establece el ángulo del cono de caída (en grados).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Establece la distancia del plano lejano del frustum.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setHotSpot(double value) {#setHotSpot-double-}
```
public void setHotSpot(double value)
```


Establece el ángulo del cono del punto caliente(en grados).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setIntensity(double value) {#setIntensity-double-}
```
public void setIntensity(double value)
```


Establece la intensidad de la luz, el valor predeterminado es 100

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setLightType(LightType value) {#setLightType-com.aspose.threed.LightType-}
```
public void setLightType(LightType value)
```


Establece el tipo de la luz

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [LightType](../../com.aspose.threed/lighttype) | Nuevo valor |

### setLinearAttenuation(double value) {#setLinearAttenuation-double-}
```
public void setLinearAttenuation(double value)
```


Establece la atenuación lineal para calcular la atenuación total de la luz

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

### setQuadraticAttenuation(double value) {#setQuadraticAttenuation-double-}
```
public void setQuadraticAttenuation(double value)
```


Establece la atenuación cuadrática para calcular la atenuación total de la luz

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Establece el modo de orientación del frustum. Esta propiedad solo funciona cuando el [getTarget](../../com.aspose.threed/frustum\#getTarget) es nulo. Si el valor es [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), la dirección siempre se calcula mediante la propiedad [getLookAt](../../com.aspose.threed/frustum\#getLookAt). De lo contrario, el [getLookAt](../../com.aspose.threed/frustum\#getLookAt) siempre se calcula mediante el [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Nuevo valor |

### setShadowColor(Vector3 value) {#setShadowColor-com.aspose.threed.Vector3-}
```
public void setShadowColor(Vector3 value)
```


Establece el color de la sombra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

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

