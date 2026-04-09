---
title: AnimationClip
second_title: Referencia de API de Aspose.3D para Java
description: El clip de animación es una colección de animaciones.
type: docs
weight: 14
url: /es/java/com.aspose.threed/animationclip/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class AnimationClip extends SceneObject
```

El clip de animación es una colección de animaciones. La escena puede tener uno o más clips de animación.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AnimationClip()](#AnimationClip--) | Inicializa una nueva instancia de la clase [AnimationClip](../../com.aspose.threed/animationclip). |
| [AnimationClip(String name)](#AnimationClip-java.lang.String-) | Inicializa una nueva instancia de la clase [AnimationClip](../../com.aspose.threed/animationclip). |
## Métodos

| Método | Descripción |
| --- | --- |
| [createAnimationNode(String nodeName)](#createAnimationNode-java.lang.String-) | Una función abreviada para crear y registrar el nodo de animación en el clip actual. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getAnimations()](#getAnimations--) | Obtiene las animaciones contenidas dentro del clip. |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Obtiene la descripción de este clip de animación |
| [getName()](#getName--) | Obtiene el nombre. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getScene()](#getScene--) | Obtiene la escena a la que pertenece este objeto. |
| [getStart()](#getStart--) | Obtiene el tiempo en segundos del inicio del clip. |
| [getStop()](#getStop--) | Obtiene el tiempo en segundos del final del clip. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Establece la descripción de este clip de animación |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setStart(double value)](#setStart-double-) | Establece el tiempo en segundos del comienzo del clip. |
| [setStop(double value)](#setStop-double-) | Establece el tiempo en segundos del final del clip. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationClip() {#AnimationClip--}
```
public AnimationClip()
```


Inicializa una nueva instancia de la clase [AnimationClip](../../com.aspose.threed/animationclip).

### AnimationClip(String name) {#AnimationClip-java.lang.String-}
```
public AnimationClip(String name)
```


Inicializa una nueva instancia de la clase [AnimationClip](../../com.aspose.threed/animationclip).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre |

### createAnimationNode(String nodeName) {#createAnimationNode-java.lang.String-}
```
public AnimationNode createAnimationNode(String nodeName)
```


Una función abreviada para crear y registrar el nodo de animación en el clip actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodeName | java.lang.String | Nombre del nuevo nodo de animación |

**Returns:**
[AnimationNode](../../com.aspose.threed/animationnode) - A new instance of [AnimationNode](../../com.aspose.threed/animationnode) with given name.
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
### getAnimations() {#getAnimations--}
```
public List<AnimationNode> getAnimations()
```


Obtiene las animaciones contenidas dentro del clip.

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - las animaciones contenidas dentro del clip.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public String getDescription()
```


Obtiene la descripción de este clip de animación

**Returns:**
java.lang.String - la descripción de este clip de animación
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtiene la escena a la que pertenece este objeto.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getStart() {#getStart--}
```
public double getStart()
```


Obtiene el tiempo en segundos del inicio del clip.

**Returns:**
double - el tiempo en segundos del comienzo del clip.
### getStop() {#getStop--}
```
public double getStop()
```


Obtiene el tiempo en segundos del final del clip.

**Returns:**
double - el tiempo en segundos del final del clip.
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
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Establece la descripción de este clip de animación

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

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

### setStart(double value) {#setStart-double-}
```
public void setStart(double value)
```


Establece el tiempo en segundos del comienzo del clip.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setStop(double value) {#setStop-double-}
```
public void setStop(double value)
```


Establece el tiempo en segundos del final del clip.

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

