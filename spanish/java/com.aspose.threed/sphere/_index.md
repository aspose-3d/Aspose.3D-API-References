---
title: Sphere
second_title: Referencia de API de Aspose.3D para Java
description: Esfera parametrizada.
type: docs
weight: 174
url: /es/java/com.aspose.threed/sphere/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Sphere extends Primitive
```

Esfera parametrizada.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Sphere()](#Sphere--) | Inicializa una nueva instancia de [Sphere](../../com.aspose.threed/sphere) con radio predeterminado 1. |
| [Sphere(double radius)](#Sphere-double-) | Inicializa una nueva instancia de la clase [Sphere](../../com.aspose.threed/sphere) con el radio especificado. |
| [Sphere(double radius, int widthSegments, int heightSegments)](#Sphere-double-int-int-) | Inicializa una nueva instancia de la clase [Sphere](../../com.aspose.threed/sphere) con el radio especificado, segmentos de ancho y segmentos de altura. |
| [Sphere(String name, double radius, int widthSegments, int heightSegments, double phiStart, double phiLength, double thetaStart, double thetaLength)](#Sphere-java.lang.String-double-int-int-double-double-double-double-) | Inicializa una nueva instancia de la clase [Sphere](../../com.aspose.threed/sphere). |
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
| [getHeightSegments()](#getHeightSegments--) | Obtiene los segmentos de altura. |
| [getName()](#getName--) | Obtiene el nombre. |
| [getParentNode()](#getParentNode--) | Obtiene el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [getParentNodes()](#getParentNodes--) | Obtiene todos los nodos padres; una entidad puede estar adjunta a varios nodos padres para instanciación de geometría. |
| [getPhiLength()](#getPhiLength--) | Obtiene la longitud de phi. |
| [getPhiStart()](#getPhiStart--) | Obtiene el inicio de phi. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getRadius()](#getRadius--) | Obtiene el radio de la esfera. |
| [getReceiveShadows()](#getReceiveShadows--) | Obtiene si esta geometría puede recibir sombra. |
| [getScene()](#getScene--) | Obtiene la escena a la que pertenece este objeto. |
| [getThetaLength()](#getThetaLength--) | Obtiene la longitud de theta. |
| [getThetaStart()](#getThetaStart--) | Obtiene el inicio de theta. |
| [getWidthSegments()](#getWidthSegments--) | Obtiene los segmentos de ancho. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Establece si esta geometría puede proyectar sombra |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Establece si se debe excluir esta entidad durante la exportación. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | Establece los segmentos de altura. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [setPhiLength(double value)](#setPhiLength-double-) | Establece la longitud de phi. |
| [setPhiStart(double value)](#setPhiStart-double-) | Establece el inicio de phi. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setRadius(double value)](#setRadius-double-) | Establece el radio de la esfera. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Establece si esta geometría puede recibir sombra. |
| [setThetaLength(double value)](#setThetaLength-double-) | Establece la longitud de theta. |
| [setThetaStart(double value)](#setThetaStart-double-) | Establece el inicio de theta. |
| [setWidthSegments(int value)](#setWidthSegments-int-) | Establece los segmentos de ancho. |
| [toMesh()](#toMesh--) | Convertir el objeto actual a malla |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Sphere() {#Sphere--}
```
public Sphere()
```


Inicializa una nueva instancia de [Sphere](../../com.aspose.threed/sphere) con radio predeterminado 1.

### Sphere(double radius) {#Sphere-double-}
```
public Sphere(double radius)
```


Inicializa una nueva instancia de la clase [Sphere](../../com.aspose.threed/sphere) con el radio especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| radio | double | Radio. |

### Sphere(double radius, int widthSegments, int heightSegments) {#Sphere-double-int-int-}
```
public Sphere(double radius, int widthSegments, int heightSegments)
```


Inicializa una nueva instancia de la clase [Sphere](../../com.aspose.threed/sphere) con el radio especificado, segmentos de ancho y segmentos de altura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| radio | double | Radio de la esfera. |
| widthSegments | int | Segmentos de ancho. |
| heightSegments | int | Segmentos de altura. |

### Sphere(String name, double radius, int widthSegments, int heightSegments, double phiStart, double phiLength, double thetaStart, double thetaLength) {#Sphere-java.lang.String-double-int-int-double-double-double-double-}
```
public Sphere(String name, double radius, int widthSegments, int heightSegments, double phiStart, double phiLength, double thetaStart, double thetaLength)
```


Inicializa una nueva instancia de la clase [Sphere](../../com.aspose.threed/sphere).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre. |
| radio | double | Radio de la esfera. |
| widthSegments | int | Segmentos de ancho. |
| heightSegments | int | Segmentos de altura. |
| phiStart | double | Inicio de phi. |
| phiLength | double | Longitud de phi. |
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
### getPhiLength() {#getPhiLength--}
```
public double getPhiLength()
```


Obtiene la longitud de phi.

**Returns:**
double - la longitud de phi.
### getPhiStart() {#getPhiStart--}
```
public double getPhiStart()
```


Obtiene el inicio de phi.

**Returns:**
double - el inicio de phi.
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
### getRadius() {#getRadius--}
```
public double getRadius()
```


Obtiene el radio de la esfera.

**Returns:**
double - el radio de la esfera.
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
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


Obtiene la longitud de theta.

**Returns:**
double - la longitud de theta.
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


Obtiene el inicio de theta.

**Returns:**
double - el inicio de theta.
### getWidthSegments() {#getWidthSegments--}
```
public int getWidthSegments()
```


Obtiene los segmentos de ancho.

**Returns:**
int - los segmentos de ancho.
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

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nuevo valor |

### setPhiLength(double value) {#setPhiLength-double-}
```
public void setPhiLength(double value)
```


Establece la longitud de phi.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setPhiStart(double value) {#setPhiStart-double-}
```
public void setPhiStart(double value)
```


Establece el inicio de phi.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

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

### setRadius(double value) {#setRadius-double-}
```
public void setRadius(double value)
```


Establece el radio de la esfera.

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

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


Establece la longitud de theta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


Establece el inicio de theta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setWidthSegments(int value) {#setWidthSegments-int-}
```
public void setWidthSegments(int value)
```


Establece los segmentos de ancho.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

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

