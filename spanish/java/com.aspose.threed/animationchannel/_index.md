---
title: AnimationChannel
second_title: Referencia de API de Aspose.3D para Java
description: Un canal asigna el campo de componente de la propiedad a un conjunto de secuencias de fotogramas clave
type: docs
weight: 13
url: /es/java/com.aspose.threed/animationchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.KeyframeSequence](../../com.aspose.threed/keyframesequence)
```
public class AnimationChannel extends KeyframeSequence
```

Un canal asigna el campo de componente de la propiedad a un conjunto de secuencias de fotogramas clave.
## Métodos

| Método | Descripción |
| --- | --- |
| [add(double time, float value)](#add-double-float-) | Crea un nuevo fotograma clave con el valor especificado |
| [add(double time, float value, Interpolation interpolation)](#add-double-float-com.aspose.threed.Interpolation-) | Crea un nuevo fotograma clave con el valor especificado |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getBindPoint()](#getBindPoint--) | Obtiene el punto de enlace de la propiedad que posee esta curva |
| [getClass()](#getClass--) |  |
| [getComponentType()](#getComponentType--) | Obtiene el tipo del campo de componente |
| [getDefaultValue()](#getDefaultValue--) | Obtiene el valor predeterminado del canal. |
| [getKeyFrames()](#getKeyFrames--) | Obtiene los fotogramas clave de esta curva. |
| [getKeyframeSequence()](#getKeyframeSequence--) | Obtiene la secuencia de fotogramas clave asociada dentro de este canal |
| [getName()](#getName--) | Obtiene el nombre. |
| [getPostBehavior()](#getPostBehavior--) | Obtiene el comportamiento posterior que indica cuál debe ser el valor muestreado después del último fotograma clave. |
| [getPreBehavior()](#getPreBehavior--) | Obtiene el comportamiento previo que indica cuál debe ser el valor muestreado antes del primer fotograma clave. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Obtiene el enumerador para recorrer todos los fotogramas clave. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [reset()](#reset--) | Elimina todos los fotogramas clave y restablece los comportamientos posterior/previo. |
| [setDefaultValue(Object value)](#setDefaultValue-java.lang.Object-) | Establece el valor predeterminado del canal. |
| [setKeyframeSequence(KeyframeSequence value)](#setKeyframeSequence-com.aspose.threed.KeyframeSequence-) | Obtiene la secuencia de fotogramas clave asociada dentro de este canal |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(double time, float value) {#add-double-float-}
```
public void add(double time, float value)
```


Crea un nuevo fotograma clave con el valor especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tiempo | double | Posición de tiempo (medida en segundos) |
| valor | float | El valor en esta posición de tiempo |

### add(double time, float value, Interpolation interpolation) {#add-double-float-com.aspose.threed.Interpolation-}
```
public void add(double time, float value, Interpolation interpolation)
```


Crea un nuevo fotograma clave con el valor especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tiempo | double | Posición de tiempo (medida en segundos) |
| valor | float | El valor en esta posición de tiempo |
| interpolation | [Interpolation](../../com.aspose.threed/interpolation) | El tipo de interpolación de este fotograma clave |

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
### getBindPoint() {#getBindPoint--}
```
public BindPoint getBindPoint()
```


Obtiene el punto de enlace de la propiedad que posee esta curva

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - the property bind point which owns this curve
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComponentType() {#getComponentType--}
```
public Class<?> getComponentType()
```


Obtiene el tipo del campo de componente

**Returns:**
java.lang.Class<?> - el tipo del campo de componente
### getDefaultValue() {#getDefaultValue--}
```
public Object getDefaultValue()
```


Obtiene el valor predeterminado del canal. Si un canal no tiene secuencias de fotogramas clave conectadas, el valor predeterminado se utilizará durante la evaluación de la animación. Un escenario real: la animación solo anima la coordenada x de un nodo, las coordenadas y y z no se modifican, entonces el valor predeterminado se usará durante la evaluación completa de la traducción.

**Returns:**
java.lang.Object - el valor predeterminado del canal. Si un canal no tiene secuencias de fotogramas clave conectadas, el valor predeterminado se utilizará durante la evaluación de la animación. Un escenario real: la animación solo anima la coordenada x de un nodo, las coordenadas y y z no se modifican, entonces el valor predeterminado se usará durante la evaluación completa de la traducción.
### getKeyFrames() {#getKeyFrames--}
```
public List<KeyFrame> getKeyFrames()
```


Obtiene los fotogramas clave de esta curva.

**Returns:**
java.util.List<com.aspose.threed.KeyFrame> - los fotogramas clave de esta curva.
### getKeyframeSequence() {#getKeyframeSequence--}
```
public KeyframeSequence getKeyframeSequence()
```


Obtiene la secuencia de fotogramas clave asociada dentro de este canal

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - associated keyframe sequence inside this channel
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre.

**Returns:**
java.lang.String - el nombre.
### getPostBehavior() {#getPostBehavior--}
```
public Extrapolation getPostBehavior()
```


Obtiene el comportamiento posterior que indica cuál debe ser el valor muestreado después del último fotograma clave.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the post behavior indicates what the sampled value should be after the last key frame.
### getPreBehavior() {#getPreBehavior--}
```
public Extrapolation getPreBehavior()
```


Obtiene el comportamiento previo que indica cuál debe ser el valor muestreado antes del primer fotograma clave.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the pre behavior indicates what the sampled value should be before the first key.
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<KeyFrame> iterator()
```


Obtiene el enumerador para recorrer todos los fotogramas clave.

**Returns:**
java.util.Iterator<com.aspose.threed.KeyFrame>
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
### reset() {#reset--}
```
public void reset()
```


Elimina todos los fotogramas clave y restablece los comportamientos posterior/previo.

### setDefaultValue(Object value) {#setDefaultValue-java.lang.Object-}
```
public void setDefaultValue(Object value)
```


Establece el valor predeterminado del canal. Si un canal no tiene secuencias de fotogramas clave conectadas, el valor predeterminado se utilizará durante la evaluación de la animación. Un escenario real: la animación solo anima la coordenada x de un nodo, las coordenadas y y z no se modifican, entonces el valor predeterminado se usará durante la evaluación completa de la traducción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object | Nuevo valor |

### setKeyframeSequence(KeyframeSequence value) {#setKeyframeSequence-com.aspose.threed.KeyframeSequence-}
```
public void setKeyframeSequence(KeyframeSequence value)
```


Obtiene la secuencia de fotogramas clave asociada dentro de este canal

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Nuevo valor |

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

