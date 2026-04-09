---
title: LShape
second_title: Referencia de API de Aspose.3D para Java
description: Perfil en forma de L compatible con IFC definido por parámetros.
type: docs
weight: 91
url: /es/java/com.aspose.threed/lshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile), [com.aspose.threed.ParameterizedProfile](../../com.aspose.threed/parameterizedprofile)
```
public class LShape extends ParameterizedProfile
```

Perfil en forma de L compatible con IFC definido por parámetros.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LShape()](#LShape--) | Constructor de [LShape](../../com.aspose.threed/lshape) |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getBoundingBox()](#getBoundingBox--) | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objetos. |
| [getClass()](#getClass--) |  |
| [getDepth()](#getDepth--) | Obtiene la profundidad del perfil. |
| [getEdgeRadius()](#getEdgeRadius--) | Obtiene el radio del borde. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [getExcluded()](#getExcluded--) | Obtiene si se debe excluir esta entidad durante la exportación. |
| [getExtent()](#getExtent--) | Obtiene la extensión en las dimensiones x e y. |
| [getFilletRadius()](#getFilletRadius--) | Obtiene el radio del filete. |
| [getName()](#getName--) | Obtiene el nombre. |
| [getParentNode()](#getParentNode--) | Obtiene el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [getParentNodes()](#getParentNodes--) | Obtiene todos los nodos padres; una entidad puede estar adjunta a varios nodos padres para instanciación de geometría. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getScene()](#getScene--) | Obtiene la escena a la que pertenece este objeto. |
| [getThickness()](#getThickness--) | Obtiene el grosor de la pared constante. |
| [getWidth()](#getWidth--) | Obtiene el ancho del perfil. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setDepth(double value)](#setDepth-double-) | Establece la profundidad del perfil. |
| [setEdgeRadius(double value)](#setEdgeRadius-double-) | Establece el radio del borde. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Establece si se debe excluir esta entidad durante la exportación. |
| [setFilletRadius(double value)](#setFilletRadius-double-) | Establece el radio del filete. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setThickness(double value)](#setThickness-double-) | Establece el grosor de la pared constante. |
| [setWidth(double value)](#setWidth-double-) | Establece el ancho del perfil. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LShape() {#LShape--}
```
public LShape()
```


Constructor de [LShape](../../com.aspose.threed/lshape)

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDepth() {#getDepth--}
```
public double getDepth()
```


Obtiene la profundidad del perfil.

**Returns:**
double - la profundidad del perfil.
### getEdgeRadius() {#getEdgeRadius--}
```
public double getEdgeRadius()
```


Obtiene el radio del borde.

**Returns:**
double - el radio del borde.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Obtiene la clave del renderizador de entidad registrado en el renderizador

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Obtiene si se debe excluir esta entidad durante la exportación.

**Returns:**
boolean - si se debe excluir esta entidad durante la exportación.
### getExtent() {#getExtent--}
```
public Vector2 getExtent()
```


Obtiene la extensión en las dimensiones x e y.

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### getFilletRadius() {#getFilletRadius--}
```
public double getFilletRadius()
```


Obtiene el radio del filete.

**Returns:**
double - el radio del filete.
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtiene la escena a la que pertenece este objeto.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getThickness() {#getThickness--}
```
public double getThickness()
```


Obtiene el grosor de la pared constante.

**Returns:**
double - el grosor de la pared constante.
### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtiene el ancho del perfil.

**Returns:**
double - el ancho del perfil.
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
### setDepth(double value) {#setDepth-double-}
```
public void setDepth(double value)
```


Establece la profundidad del perfil.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setEdgeRadius(double value) {#setEdgeRadius-double-}
```
public void setEdgeRadius(double value)
```


Establece el radio del borde.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Establece si se debe excluir esta entidad durante la exportación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setFilletRadius(double value) {#setFilletRadius-double-}
```
public void setFilletRadius(double value)
```


Establece el radio del filete.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

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

### setThickness(double value) {#setThickness-double-}
```
public void setThickness(double value)
```


Establece el grosor de la pared constante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Establece el ancho del perfil.

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

