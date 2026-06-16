---
title: BooleanOperator
second_title: Referencia de API de Aspose.3D para Java
description: El operador booleano le permite aplicar una operación booleana a dos instancias.
type: docs
weight: 23
url: /es/java/com.aspose.threed/booleanoperator/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class BooleanOperator extends Entity implements IMeshConvertible
```

El operador booleano le permite aplicar una operación booleana a dos instancias de [IMeshConvertible](../../com.aspose.threed/imeshconvertible).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BooleanOperator()](#BooleanOperator--) | Constructor de [BooleanOperator](../../com.aspose.threed/booleanoperator) |
| [BooleanOperator(BooleanOperation operation, A3DObject first, A3DObject second)](#BooleanOperator-com.aspose.threed.BooleanOperation-com.aspose.threed.A3DObject-com.aspose.threed.A3DObject-) | Construye una nueva instancia de [BooleanOperator](../../com.aspose.threed/booleanoperator) con dos operandos |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getBoundingBox()](#getBoundingBox--) | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objetos. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [getExcluded()](#getExcluded--) | Obtiene si se debe excluir esta entidad durante la exportación. |
| [getFirst()](#getFirst--) | El primer operando del operador booleano |
| [getName()](#getName--) | Obtiene el nombre. |
| [getOperator()](#getOperator--) | El operador booleano utilizado en la operación para crear la malla resultante. |
| [getParentNode()](#getParentNode--) | Obtiene el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [getParentNodes()](#getParentNodes--) | Obtiene todos los nodos padres; una entidad puede estar adjunta a varios nodos padres para instanciación de geometría. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getScene()](#getScene--) | Obtiene la escena a la que pertenece este objeto. |
| [getSecond()](#getSecond--) | El segundo operando del operador booleano |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Establece si se debe excluir esta entidad durante la exportación. |
| [setFirst(BooleanOperand value)](#setFirst-com.aspose.threed.BooleanOperand-) | El primer operando del operador booleano |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setOperator(BooleanOperation value)](#setOperator-com.aspose.threed.BooleanOperation-) | El operador booleano utilizado en la operación para crear la malla resultante. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setSecond(BooleanOperand value)](#setSecond-com.aspose.threed.BooleanOperand-) | El segundo operando del operador booleano |
| [toMesh()](#toMesh--) | Ejecute la operación booleana sobre dos operandos |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BooleanOperator() {#BooleanOperator--}
```
public BooleanOperator()
```


Constructor de [BooleanOperator](../../com.aspose.threed/booleanoperator)

### BooleanOperator(BooleanOperation operation, A3DObject first, A3DObject second) {#BooleanOperator-com.aspose.threed.BooleanOperation-com.aspose.threed.A3DObject-com.aspose.threed.A3DObject-}
```
public BooleanOperator(BooleanOperation operation, A3DObject first, A3DObject second)
```


Construye una nueva instancia de [BooleanOperator](../../com.aspose.threed/booleanoperator) con dos operandos

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| operation | [BooleanOperation](../../com.aspose.threed/booleanoperation) | Tipo de operación booleana |
| first | [A3DObject](../../com.aspose.threed/a3dobject) | Instancia de [IMeshConvertible](../../com.aspose.threed/imeshconvertible), [HalfSpace](../../com.aspose.threed/halfspace) o [Node](../../com.aspose.threed/node) |
| second | [A3DObject](../../com.aspose.threed/a3dobject) | Instancia de [IMeshConvertible](../../com.aspose.threed/imeshconvertible), [HalfSpace](../../com.aspose.threed/halfspace) o [Node](../../com.aspose.threed/node) |

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
### getFirst() {#getFirst--}
```
public BooleanOperand getFirst()
```


El primer operando del operador booleano

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - The first operand of the Boolean operator
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre.

**Returns:**
java.lang.String - el nombre.
### getOperator() {#getOperator--}
```
public BooleanOperation getOperator()
```


El operador booleano utilizado en la operación para crear la malla resultante.

**Returns:**
[BooleanOperation](../../com.aspose.threed/booleanoperation) - The Boolean operator used in the operation to create the result mesh.
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
### getSecond() {#getSecond--}
```
public BooleanOperand getSecond()
```


El segundo operando del operador booleano

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - The second operand of the Boolean operator
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

### setFirst(BooleanOperand value) {#setFirst-com.aspose.threed.BooleanOperand-}
```
public void setFirst(BooleanOperand value)
```


El primer operando del operador booleano

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [BooleanOperand](../../com.aspose.threed/booleanoperand) | Nuevo valor |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Establece el nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setOperator(BooleanOperation value) {#setOperator-com.aspose.threed.BooleanOperation-}
```
public void setOperator(BooleanOperation value)
```


El operador booleano utilizado en la operación para crear la malla resultante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [BooleanOperation](../../com.aspose.threed/booleanoperation) | Nuevo valor |

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

### setSecond(BooleanOperand value) {#setSecond-com.aspose.threed.BooleanOperand-}
```
public void setSecond(BooleanOperand value)
```


El segundo operando del operador booleano

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [BooleanOperand](../../com.aspose.threed/booleanoperand) | Nuevo valor |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Ejecute la operación booleana sobre dos operandos

**Returns:**
[Mesh](../../com.aspose.threed/mesh)
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

