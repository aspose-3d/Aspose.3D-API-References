---
title: Cilindro
second_title: Referencia de API de Aspose.3D para Java
description: Cilindro parametrizado.
type: docs
weight: 40
url: /es/java/com.aspose.threed/cylinder/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Cylinder extends Primitive
```

Cilindro parametrizado. También puede usarse para representar el cono cuando uno de radiusTop/radiusBottom es cero.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Cylinder()](#Cylinder--) | Inicializa una nueva instancia de la clase [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radius, double height)](#Cylinder-double-double-) | Inicializa una nueva instancia de la clase [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radiusTop, double radiusBottom, double height)](#Cylinder-double-double-double-) | Inicializa una nueva instancia de la clase [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)](#Cylinder-double-double-double-int-int-boolean-) | Inicializa una nueva instancia de la clase [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)](#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-) | Inicializa una nueva instancia de la clase [Cylinder](../../com.aspose.threed/cylinder). |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getBoundingBox()](#getBoundingBox--) | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objetos. |
| [getCastShadows()](#getCastShadows--) | Obtiene si esta geometría puede proyectar sombra |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [getExcluded()](#getExcluded--) | Obtiene si se debe excluir esta entidad durante la exportación. |
| [getGenerateFanCylinder()](#getGenerateFanCylinder--) | Obtiene si generar el cilindro estilo abanico cuando ThetaLength es menor que 2\*PI, de lo contrario el modelo no se cortará. |
| [getHeight()](#getHeight--) | Obtiene la altura del cilindro. |
| [getHeightSegments()](#getHeightSegments--) | Obtiene los segmentos de altura. |
| [getName()](#getName--) | Obtiene el nombre. |
| [getOffsetBottom()](#getOffsetBottom--) | Obtiene el desplazamiento de transformación de los vértices del lado inferior. |
| [getOffsetTop()](#getOffsetTop--) | Obtiene el desplazamiento de transformación de los vértices del lado superior. |
| [getOpenEnded()](#getOpenEnded--) | Obtiene un valor que indica si este [Cylinder](../../com.aspose.threed/cylinder) está abierto en los extremos. |
| [getParentNode()](#getParentNode--) | Obtiene el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [getParentNodes()](#getParentNodes--) | Obtiene todos los nodos padres; una entidad puede estar adjunta a varios nodos padres para instanciación de geometría. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getRadialSegments()](#getRadialSegments--) | Obtiene los segmentos radiales |
| [getRadiusBottom()](#getRadiusBottom--) | Obtiene el radio de la tapa inferior del cilindro. |
| [getRadiusTop()](#getRadiusTop--) | Obtiene el radio de la tapa superior del cilindro. |
| [getReceiveShadows()](#getReceiveShadows--) | Obtiene si esta geometría puede recibir sombra. |
| [getScene()](#getScene--) | Obtiene la escena a la que pertenece este objeto. |
| [getShearBottom()](#getShearBottom--) | Obtiene la transformación de cizallamiento del lado inferior, el vector almacena el valor de cizallamiento (eje x, eje z) medido en radianes, el valor predeterminado es (0, 0). |
| [getShearTop()](#getShearTop--) | Obtiene la transformación de cizallamiento del lado superior, el vector almacena el valor de cizallamiento (eje x, eje z) medido en radianes, el valor predeterminado es (0, 0). |
| [getThetaLength()](#getThetaLength--) | Obtiene la longitud de theta. |
| [getThetaStart()](#getThetaStart--) | Obtiene el inicio de theta. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Establece si esta geometría puede proyectar sombra |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Establece si se debe excluir esta entidad durante la exportación. |
| [setGenerateFanCylinder(boolean value)](#setGenerateFanCylinder-boolean-) | Establece si generar el cilindro estilo abanico cuando ThetaLength es menor que 2\*PI, de lo contrario el modelo no se recortará. |
| [setHeight(double value)](#setHeight-double-) | Establece la altura del cilindro. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | Establece los segmentos de altura. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setOffsetBottom(Vector3 value)](#setOffsetBottom-com.aspose.threed.Vector3-) | Establece el desplazamiento de transformación de los vértices del lado inferior. |
| [setOffsetTop(Vector3 value)](#setOffsetTop-com.aspose.threed.Vector3-) | Establece el desplazamiento de transformación de los vértices del lado superior. |
| [setOpenEnded(boolean value)](#setOpenEnded-boolean-) | Establece un valor que indica si este [Cylinder](../../com.aspose.threed/cylinder) está abierto en los extremos. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setRadialSegments(int value)](#setRadialSegments-int-) | Establece los segmentos radiales. |
| [setRadiusBottom(double value)](#setRadiusBottom-double-) | Establece el radio de la tapa inferior del cilindro. |
| [setRadiusTop(double value)](#setRadiusTop-double-) | Establece el radio de la tapa superior del cilindro. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Establece si esta geometría puede recibir sombra. |
| [setShearBottom(Vector2 value)](#setShearBottom-com.aspose.threed.Vector2-) | Establece la transformación de cizallamiento del lado inferior, el vector almacena el valor de cizallamiento (eje x, eje z) medido en radianes, el valor predeterminado es (0, 0). |
| [setShearTop(Vector2 value)](#setShearTop-com.aspose.threed.Vector2-) | Establece la transformación de cizallamiento del lado superior, el vector almacena el valor de cizallamiento (eje x, eje z) medido en radianes, el valor predeterminado es (0, 0). |
| [setThetaLength(double value)](#setThetaLength-double-) | Establece la longitud de theta. |
| [setThetaStart(double value)](#setThetaStart-double-) | Establece el inicio de theta. |
| [toMesh()](#toMesh--) | Convertir el objeto actual a malla |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cylinder() {#Cylinder--}
```
public Cylinder()
```


Inicializa una nueva instancia de la clase [Cylinder](../../com.aspose.threed/cylinder).

### Cylinder(double radius, double height) {#Cylinder-double-double-}
```
public Cylinder(double radius, double height)
```


Inicializa una nueva instancia de la clase [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| radio | double | Radio de la tapa superior e inferior. |
| altura | double | Altura. |

### Cylinder(double radiusTop, double radiusBottom, double height) {#Cylinder-double-double-double-}
```
public Cylinder(double radiusTop, double radiusBottom, double height)
```


Inicializa una nueva instancia de la clase [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| radiusTop | double | Radio superior. |
| radiusBottom | double | Radio inferior. |
| altura | double | Altura. |

### Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded) {#Cylinder-double-double-double-int-int-boolean-}
```
public Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)
```


Inicializa una nueva instancia de la clase [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| radiusTop | double | Radio de la tapa superior del cilindro. |
| radiusBottom | double | Radio de la tapa inferior del cilindro. |
| altura | double | Altura del cilindro. |
| radialSegments | int | Segmentos radiales de los círculos superior e inferior. |
| heightSegments | int | Segmentos de altura. |
| openEnded | boolean | Si se establece en  true  el cilindro no tendría tapas inferior/superior.. |

### Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength) {#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-}
```
public Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)
```


Inicializa una nueva instancia de la clase [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | El nombre de este objeto |
| radiusTop | double | Radio de la tapa superior del cilindro. |
| radiusBottom | double | Radio de la tapa inferior del cilindro. |
| altura | double | Altura del cilindro. |
| radialSegments | int | Segmentos radiales de los círculos superior e inferior. |
| heightSegments | int | Segmentos de altura. |
| openEnded | boolean | Si se establece en  true  el cilindro no tendría tapas inferior/superior.. |
| thetaStart | double | Inicio de theta. |
| thetaLength | double | Longitud de theta. |

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
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Obtiene si esta geometría puede proyectar sombra

**Returns:**
boolean - si esta geometría puede proyectar sombra
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
### getGenerateFanCylinder() {#getGenerateFanCylinder--}
```
public boolean getGenerateFanCylinder()
```


Obtiene si generar el cilindro estilo abanico cuando ThetaLength es menor que 2\*PI, de lo contrario el modelo no se cortará.

**Returns:**
boolean - si generar el cilindro tipo abanico cuando ThetaLength es menor que 2\*PI, de lo contrario el modelo no se recortará.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtiene la altura del cilindro.

**Returns:**
double - la altura del cilindro.
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


Obtiene los segmentos de altura.

**Returns:**
int - los segmentos de altura.
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre.

**Returns:**
java.lang.String - el nombre.
### getOffsetBottom() {#getOffsetBottom--}
```
public Vector3 getOffsetBottom()
```


Obtiene el desplazamiento de transformación de los vértices del lado inferior.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the bottom side.
### getOffsetTop() {#getOffsetTop--}
```
public Vector3 getOffsetTop()
```


Obtiene el desplazamiento de transformación de los vértices del lado superior.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the top side.
### getOpenEnded() {#getOpenEnded--}
```
public boolean getOpenEnded()
```


Obtiene un valor que indica si este [Cylinder](../../com.aspose.threed/cylinder) está abierto en los extremos. El valor predeterminado es false.

**Returns:**
boolean - un valor que indica si este [Cylinder](../../com.aspose.threed/cylinder) está abierto en los extremos. El valor predeterminado es false.
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


Obtiene los segmentos radiales

**Returns:**
int - los segmentos radiales.
### getRadiusBottom() {#getRadiusBottom--}
```
public double getRadiusBottom()
```


Obtiene el radio de la tapa inferior del cilindro.

**Returns:**
double - el radio de la tapa inferior del cilindro.
### getRadiusTop() {#getRadiusTop--}
```
public double getRadiusTop()
```


Obtiene el radio de la tapa superior del cilindro.

**Returns:**
double - el radio de la tapa superior del cilindro.
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Obtiene si esta geometría puede recibir sombra.

**Returns:**
boolean - si esta geometría puede recibir sombra.
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtiene la escena a la que pertenece este objeto.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShearBottom() {#getShearBottom--}
```
public Vector2 getShearBottom()
```


Obtiene la transformación de cizallamiento del lado inferior, el vector almacena el valor de cizallamiento (eje x, eje z) medido en radianes, el valor predeterminado es (0, 0).

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the bottom side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getShearTop() {#getShearTop--}
```
public Vector2 getShearTop()
```


Obtiene la transformación de cizallamiento del lado superior, el vector almacena el valor de cizallamiento (eje x, eje z) medido en radianes, el valor predeterminado es (0, 0).

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the top side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


Obtiene la longitud de theta. El valor predeterminado es 2\\u03c0.

**Returns:**
double - la longitud de theta. El valor predeterminado es 2\\u03c0.
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


Obtiene el inicio de theta. El valor predeterminado es 0.

**Returns:**
double - el inicio de theta. El valor predeterminado es 0.
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Establece si esta geometría puede proyectar sombra

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Establece si se debe excluir esta entidad durante la exportación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setGenerateFanCylinder(boolean value) {#setGenerateFanCylinder-boolean-}
```
public void setGenerateFanCylinder(boolean value)
```


Establece si generar el cilindro estilo abanico cuando ThetaLength es menor que 2\*PI, de lo contrario el modelo no se recortará.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Establece la altura del cilindro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


Establece los segmentos de altura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Establece el nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setOffsetBottom(Vector3 value) {#setOffsetBottom-com.aspose.threed.Vector3-}
```
public void setOffsetBottom(Vector3 value)
```


Establece el desplazamiento de transformación de los vértices del lado inferior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setOffsetTop(Vector3 value) {#setOffsetTop-com.aspose.threed.Vector3-}
```
public void setOffsetTop(Vector3 value)
```


Establece el desplazamiento de transformación de los vértices del lado superior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setOpenEnded(boolean value) {#setOpenEnded-boolean-}
```
public void setOpenEnded(boolean value)
```


Establece un valor que indica si este [Cylinder](../../com.aspose.threed/cylinder) está abierto en los extremos. El valor predeterminado es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


Establece los segmentos radiales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setRadiusBottom(double value) {#setRadiusBottom-double-}
```
public void setRadiusBottom(double value)
```


Establece el radio de la tapa inferior del cilindro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setRadiusTop(double value) {#setRadiusTop-double-}
```
public void setRadiusTop(double value)
```


Establece el radio de la tapa superior del cilindro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Establece si esta geometría puede recibir sombra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setShearBottom(Vector2 value) {#setShearBottom-com.aspose.threed.Vector2-}
```
public void setShearBottom(Vector2 value)
```


Establece la transformación de cizallamiento del lado inferior, el vector almacena el valor de cizallamiento (eje x, eje z) medido en radianes, el valor predeterminado es (0, 0).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuevo valor |

### setShearTop(Vector2 value) {#setShearTop-com.aspose.threed.Vector2-}
```
public void setShearTop(Vector2 value)
```


Establece la transformación de cizallamiento del lado superior, el vector almacena el valor de cizallamiento (eje x, eje z) medido en radianes, el valor predeterminado es (0, 0).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuevo valor |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


Establece la longitud de theta. El valor predeterminado es 2\\u03c0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


Establece el inicio de theta. El valor predeterminado es 0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Convertir el objeto actual a malla

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

