---
title: Esqueleto
second_title: Referencia de API de Aspose.3D para Java
description: El  se usa principalmente en software CAD para ayudar al diseñador a manipular la transformación de la estructura esquelética, suele ser inútil fuera del software CAD.
type: docs
weight: 172
url: /es/java/com.aspose.threed/skeleton/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)
```
public class Skeleton extends Entity
```

El [Skeleton](../../com.aspose.threed/skeleton) se usa principalmente en software CAD para ayudar al diseñador a manipular la transformación de la estructura esquelética, suele ser inútil fuera del software CAD. Para que la jerarquía del esqueleto actúe como un solo objeto en el software CAD, es necesario marcar el nodo superior [Skeleton](../../com.aspose.threed/skeleton) como la raíz estableciendo [getType](../../com.aspose.threed/skeleton\#getType) a [SkeletonType.SKELETON](../../com.aspose.threed/skeletontype\#SKELETON), y todos los hijos a [SkeletonType.BONE](../../com.aspose.threed/skeletontype\#BONE)
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Skeleton()](#Skeleton--) | Inicializa una nueva instancia de la clase [Skeleton](../../com.aspose.threed/skeleton). |
| [Skeleton(String name)](#Skeleton-java.lang.String-) | Inicializa una nueva instancia de la clase [Skeleton](../../com.aspose.threed/skeleton). |
| [Skeleton(String name, SkeletonType type)](#Skeleton-java.lang.String-com.aspose.threed.SkeletonType-) | Inicializa una nueva instancia de la clase [Skeleton](../../com.aspose.threed/skeleton). |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getBoundingBox()](#getBoundingBox--) | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objetos. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [getExcluded()](#getExcluded--) | Obtiene si se debe excluir esta entidad durante la exportación. |
| [getName()](#getName--) | Obtiene el nombre. |
| [getParentNode()](#getParentNode--) | Obtiene el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [getParentNodes()](#getParentNodes--) | Obtiene todos los nodos padres; una entidad puede estar adjunta a varios nodos padres para instanciación de geometría. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getScene()](#getScene--) | Obtiene la escena a la que pertenece este objeto. |
| [getSize()](#getSize--) | Obtiene el tamaño del nodo de extremidad que se usa en el software CAD para representar el tamaño del hueso. |
| [getType()](#getType--) | Obtiene el tipo del esqueleto. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Establece si se debe excluir esta entidad durante la exportación. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setSize(double value)](#setSize-double-) | Establece el tamaño del nodo de extremidad que se usa en el software CAD para representar el tamaño del hueso. |
| [setType(SkeletonType value)](#setType-com.aspose.threed.SkeletonType-) | Establece el tipo del esqueleto. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Skeleton() {#Skeleton--}
```
public Skeleton()
```


Inicializa una nueva instancia de la clase [Skeleton](../../com.aspose.threed/skeleton).

### Skeleton(String name) {#Skeleton-java.lang.String-}
```
public Skeleton(String name)
```


Inicializa una nueva instancia de la clase [Skeleton](../../com.aspose.threed/skeleton).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre. |

### Skeleton(String name, SkeletonType type) {#Skeleton-java.lang.String-com.aspose.threed.SkeletonType-}
```
public Skeleton(String name, SkeletonType type)
```


Inicializa una nueva instancia de la clase [Skeleton](../../com.aspose.threed/skeleton).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre de la entidad. |
| type | [SkeletonType](../../com.aspose.threed/skeletontype) | Tipo de esqueleto |

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
### getSize() {#getSize--}
```
public double getSize()
```


Obtiene el tamaño del nodo de extremidad que se usa en el software CAD para representar el tamaño del hueso.

**Returns:**
double - el tamaño del nodo de extremidad que se usa en el software CAD para representar el tamaño del hueso.
### getType() {#getType--}
```
public SkeletonType getType()
```


Obtiene el tipo del esqueleto.

**Returns:**
[SkeletonType](../../com.aspose.threed/skeletontype) - the type of the skeleton.
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
### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Establece si se debe excluir esta entidad durante la exportación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

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

### setSize(double value) {#setSize-double-}
```
public void setSize(double value)
```


Establece el tamaño del nodo de extremidad que se usa en el software CAD para representar el tamaño del hueso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setType(SkeletonType value) {#setType-com.aspose.threed.SkeletonType-}
```
public void setType(SkeletonType value)
```


Establece el tipo del esqueleto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SkeletonType](../../com.aspose.threed/skeletontype) | Nuevo valor |

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

