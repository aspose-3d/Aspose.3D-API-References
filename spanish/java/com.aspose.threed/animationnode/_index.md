---
title: AnimationNode
second_title: Referencia de API de Aspose.3D para Java
description: Aspose.3Ds soporta una jerarquía de animación; cada animación puede estar compuesta por varias animaciones y la definición de fotogramas clave.
type: docs
weight: 15
url: /es/java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

Aspose.3D soporta una jerarquía de animación, cada animación puede estar compuesta por varias animaciones y la definición de fotogramas clave de la animación. [AnimationNode](../../com.aspose.threed/animationnode) define la transformación de un valor de propiedad a lo largo del tiempo; por ejemplo, el nodo de animación puede usarse para controlar la transformación de un nodo o las propiedades numéricas de otro objeto [A3DObject](../../com.aspose.threed/a3dobject).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | Inicializa una nueva instancia de la clase [AnimationNode](../../com.aspose.threed/animationnode). |
| [AnimationNode()](#AnimationNode--) | Inicializa una nueva instancia de la clase [AnimationNode](../../com.aspose.threed/animationnode). |
## Métodos

| Método | Descripción |
| --- | --- |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Crea un BindPoint basado en el tipo de datos de la propiedad. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findBindPoint(A3DObject target, String name)](#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Busca el punto de enlace por objetivo y nombre. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Obtiene el punto de enlace de animación en la propiedad dada. |
| [getBindPoints()](#getBindPoints--) | Obtiene los puntos de enlace de propiedad actuales |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Obtiene la secuencia de fotogramas clave en la propiedad dada. |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | Obtiene la secuencia de fotogramas clave en la propiedad y canal dados. |
| [getName()](#getName--) | Obtiene el nombre. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getSubAnimations()](#getSubAnimations--) | Obtiene los nodos de subanimación bajo las animaciones actuales. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


Inicializa una nueva instancia de la clase [AnimationNode](../../com.aspose.threed/animationnode).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


Inicializa una nueva instancia de la clase [AnimationNode](../../com.aspose.threed/animationnode).

### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


Crea un BindPoint basado en el tipo de datos de la propiedad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | Objeto. |
| propName | java.lang.String | Nombre de la propiedad. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
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
### findBindPoint(A3DObject target, String name) {#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint findBindPoint(A3DObject target, String name)
```


Busca el punto de enlace por objetivo y nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Objetivo del punto de enlace a buscar. |
| nombre | java.lang.String | Nombre del punto de enlace a buscar. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
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
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


Obtiene el punto de enlace de animación en la propiedad dada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | En qué objeto crear el punto de enlace. |
| propName | java.lang.String | El nombre de la propiedad. |
| crear | boolean | Si se establece en  true  crear el punto de enlace si no existe. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


Obtiene los puntos de enlace de propiedad actuales

**Returns:**
java.util.List<com.aspose.threed.BindPoint> - los puntos de enlace de la propiedad actual
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(A3DObject target, String propName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, boolean create)
```


Obtiene la secuencia de fotogramas clave en la propiedad dada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | En qué instancia crear la secuencia de fotogramas clave. |
| propName | java.lang.String | El nombre de la propiedad. |
| crear | boolean | Si se establece en  true , crear la secuencia si no existe. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


Obtiene la secuencia de fotogramas clave en la propiedad y canal dados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | En qué instancia crear la secuencia de fotogramas clave. |
| propName | java.lang.String | El nombre de la propiedad. |
| channelName | java.lang.String | El nombre del canal. |
| crear | boolean | Si se establece en  true  crear la secuencia de animación si no existe. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre.

**Returns:**
java.lang.String - el nombre.
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
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


Obtiene los nodos de subanimación bajo las animaciones actuales.

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - los nodos de subanimación bajo las animaciones actuales
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
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Establece el nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

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

