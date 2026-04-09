---
title: Hueso
second_title: Referencia de API de Aspose.3D para Java
description: Un hueso define el subconjunto del punto de control de la geometría y define el peso de mezcla para cada punto de control.
type: docs
weight: 20
url: /es/java/com.aspose.threed/bone/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Bone extends A3DObject
```

Un hueso define el subconjunto del punto de control de la geometría y define el peso de mezcla para cada punto de control. El objeto [Bone](../../com.aspose.threed/bone) no puede usarse directamente, una instancia de [SkinDeformer](../../com.aspose.threed/skindeformer) se utiliza para deformar la geometría, y [SkinDeformer](../../com.aspose.threed/skindeformer) viene con un conjunto de huesos, cada hueso vinculado a un nodo. NOTA: Un punto de control de una geometría puede estar vinculado a más de un hueso.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Bone(String name)](#Bone-java.lang.String-) | Inicializa una nueva instancia de la clase [Bone](../../com.aspose.threed/bone). |
| [Bone()](#Bone--) | Inicializa una nueva instancia de la clase [Bone](../../com.aspose.threed/bone). |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [get(int index)](#get-int-) | Obtiene el peso de mezcla del punto de control especificado |
| [getBoneTransform()](#getBoneTransform--) | Obtiene la matriz de transformación del hueso. |
| [getClass()](#getClass--) |  |
| [getLinkMode()](#getLinkMode--) | El modo de enlace de un hueso se refiere a la forma en que un hueso está conectado o enlazado a su hueso padre dentro de una estructura jerárquica. |
| [getName()](#getName--) | Obtiene el nombre. |
| [getNode()](#getNode--) | Obtiene el nodo. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getTransform()](#getTransform--) | Obtiene la matriz de transformación del nodo que contiene el hueso. |
| [getWeight(int index)](#getWeight-int-) | Obtiene el peso del punto de control especificado por índice |
| [getWeightCount()](#getWeightCount--) | Obtiene la cantidad de peso, esto se amplía automáticamente mediante [setWeight](../../com.aspose.threed/bone\#setWeight) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [set(int index, double value)](#set-int-double-) | Establece el peso de mezcla del punto de control especificado |
| [setBoneTransform(Matrix4 value)](#setBoneTransform-com.aspose.threed.Matrix4-) | Establece la matriz de transformación del hueso. |
| [setLinkMode(BoneLinkMode value)](#setLinkMode-com.aspose.threed.BoneLinkMode-) | El modo de enlace de un hueso se refiere a la forma en que un hueso está conectado o enlazado a su hueso padre dentro de una estructura jerárquica. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Establece el nodo. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setTransform(Matrix4 value)](#setTransform-com.aspose.threed.Matrix4-) | Establece la matriz de transformación del nodo que contiene el hueso. |
| [setWeight(int index, double weight)](#setWeight-int-double-) | Establece el peso del punto de control especificado por índice |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bone(String name) {#Bone-java.lang.String-}
```
public Bone(String name)
```


Inicializa una nueva instancia de la clase [Bone](../../com.aspose.threed/bone).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre. |

### Bone() {#Bone--}
```
public Bone()
```


Inicializa una nueva instancia de la clase [Bone](../../com.aspose.threed/bone).

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
### get(int index) {#get-int-}
```
public double get(int index)
```


Obtiene el peso de mezcla del punto de control especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | Índice del peso |

**Returns:**
double - El peso
### getBoneTransform() {#getBoneTransform--}
```
public Matrix4 getBoneTransform()
```


Obtiene la matriz de transformación del hueso.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the bone.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLinkMode() {#getLinkMode--}
```
public BoneLinkMode getLinkMode()
```


El modo de enlace de un hueso se refiere a la forma en que un hueso está conectado o enlazado a su hueso padre dentro de una estructura jerárquica.

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode) - A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure.
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre.

**Returns:**
java.lang.String - el nombre.
### getNode() {#getNode--}
```
public Node getNode()
```


Obtiene el nodo. El nodo de hueso es el hueso al que se adjunta la piel, el [SkinDeformer](../../com.aspose.threed/skindeformer) utilizará el nodo de hueso para influir en el desplazamiento de los puntos de control. El nodo de hueso suele tener un [Skeleton](../../com.aspose.threed/skeleton) adjunto, pero no es obligatorio. El [Skeleton](../../com.aspose.threed/skeleton) adjunto suele ser utilizado por el software DCC para mostrar el esqueleto al usuario.

**Returns:**
[Node](../../com.aspose.threed/node) - the node. The bone node is the bone which skin attached to, the [SkinDeformer](../../com.aspose.threed/skindeformer) will use bone node to influence the displacement of the control points. Bone node usually has a [Skeleton](../../com.aspose.threed/skeleton) attached, but it's not required. Attached [Skeleton](../../com.aspose.threed/skeleton) is usually used by DCC software to show skeleton to user.
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
### getTransform() {#getTransform--}
```
public Matrix4 getTransform()
```


Obtiene la matriz de transformación del nodo que contiene el hueso.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node containing the bone.
### getWeight(int index) {#getWeight-int-}
```
public double getWeight(int index)
```


Obtiene el peso del punto de control especificado por índice

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | Índice del punto de control |

**Returns:**
double - el peso en el índice especificado, o 0 si el índice es inválido
### getWeightCount() {#getWeightCount--}
```
public int getWeightCount()
```


Obtiene la cantidad de peso, esto se amplía automáticamente mediante [setWeight](../../com.aspose.threed/bone\#setWeight)

**Returns:**
int - la cantidad de peso, esto se amplía automáticamente mediante [setWeight](../../com.aspose.threed/bone\#setWeight)
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
### set(int index, double value) {#set-int-double-}
```
public void set(int index, double value)
```


Establece el peso de mezcla del punto de control especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | Índice del peso |
| valor | double | Nuevo valor |

### setBoneTransform(Matrix4 value) {#setBoneTransform-com.aspose.threed.Matrix4-}
```
public void setBoneTransform(Matrix4 value)
```


Establece la matriz de transformación del hueso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nuevo valor |

### setLinkMode(BoneLinkMode value) {#setLinkMode-com.aspose.threed.BoneLinkMode-}
```
public void setLinkMode(BoneLinkMode value)
```


El modo de enlace de un hueso se refiere a la forma en que un hueso está conectado o enlazado a su hueso padre dentro de una estructura jerárquica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [BoneLinkMode](../../com.aspose.threed/bonelinkmode) | Nuevo valor |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Establece el nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Establece el nodo. El nodo de hueso es el hueso al que se adjunta la piel, el [SkinDeformer](../../com.aspose.threed/skindeformer) utilizará el nodo de hueso para influir en el desplazamiento de los puntos de control. El nodo de hueso suele tener un [Skeleton](../../com.aspose.threed/skeleton) adjunto, pero no es obligatorio. El [Skeleton](../../com.aspose.threed/skeleton) adjunto suele ser utilizado por el software DCC para mostrar el esqueleto al usuario.

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

### setTransform(Matrix4 value) {#setTransform-com.aspose.threed.Matrix4-}
```
public void setTransform(Matrix4 value)
```


Establece la matriz de transformación del nodo que contiene el hueso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nuevo valor |

### setWeight(int index, double weight) {#setWeight-int-double-}
```
public void setWeight(int index, double weight)
```


Establece el peso del punto de control especificado por índice

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | Índice del punto de control |
| peso | double | Nuevo peso |

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

