---
title: BindPoint
second_title: Referencia de API de Aspose.3D para Java
description: Normalmente se crea un  en la propiedad de un objeto; algunos tipos de propiedad contienen varios campos componentes, como un campo Vector3, que generará un canal para cada campo componente y conecta el campo a una o más instancias de secuencia de fotogramas clave a través de los canales.
type: docs
weight: 19
url: /es/java/com.aspose.threed/bindpoint/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class BindPoint extends A3DObject
```

Normalmente se crea un [BindPoint](../../com.aspose.threed/bindpoint) en la propiedad de un objeto; algunos tipos de propiedad contienen varios campos componentes (como un campo Vector3), [BindPoint](../../com.aspose.threed/bindpoint) generará un canal para cada campo componente y conecta el campo a una o más instancias de secuencia de fotogramas clave a través de los canales.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BindPoint(Scene scene, Property prop)](#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-) | Inicializa una nueva instancia de la clase [BindPoint](../../com.aspose.threed/bindpoint). |
## Métodos

| Método | Descripción |
| --- | --- |
| [addChannel(String name, Class<?> type, Object value)](#addChannel-java.lang.String-java.lang.Class----java.lang.Object-) | Agrega la propiedad de canal especificada. |
| [addChannel(String name, Object value)](#addChannel-java.lang.String-java.lang.Object-) | Agrega la propiedad de canal especificada. |
| [bindKeyframeSequence(String channelName, KeyframeSequence sequence)](#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-) | Vincula la secuencia de fotogramas clave al canal especificado |
| [createKeyframeSequence(String name)](#createKeyframeSequence-java.lang.String-) | Crea una nueva curva y la conecta al primer canal del mapeo de curvas |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [get(String channelName)](#get-java.lang.String-) | Obtiene el canal por el nombre dado |
| [getChannel(String channelName)](#getChannel-java.lang.String-) | Obtiene el canal por el nombre dado |
| [getChannelsCount()](#getChannelsCount--) | Obtiene el número total de canales de propiedad definidos en este mapeo de curvas de animación. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(String channelName)](#getKeyframeSequence-java.lang.String-) | Obtiene la primera secuencia de fotogramas clave en el canal especificado |
| [getName()](#getName--) | Obtiene el nombre. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty()](#getProperty--) | Obtiene la propiedad asociada con el CurveMapping |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [resetChannels()](#resetChannels--) | Vacía los canales de propiedad de este mapeo de curvas de animación. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setProperty(Property value)](#setProperty-com.aspose.threed.Property-) | Obtiene la propiedad asociada con el CurveMapping |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [toString()](#toString--) | Formatea el objeto a cadena |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BindPoint(Scene scene, Property prop) {#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-}
```
public BindPoint(Scene scene, Property prop)
```


Inicializa una nueva instancia de la clase [BindPoint](../../com.aspose.threed/bindpoint).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | La escena que contiene la animación. |
| prop | [Property](../../com.aspose.threed/property) | Propiedad. |

### addChannel(String name, Class<?> type, Object value) {#addChannel-java.lang.String-java.lang.Class----java.lang.Object-}
```
public boolean addChannel(String name, Class<?> type, Object value)
```


Agrega la propiedad de canal especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre. |
| type | java.lang.Class<?> | Tipo. |
| valor | java.lang.Object | Valor. |

**Returns:**
booleano - verdadero, si el canal fue añadido, falso en caso contrario.
### addChannel(String name, Object value) {#addChannel-java.lang.String-java.lang.Object-}
```
public boolean addChannel(String name, Object value)
```


Agrega la propiedad de canal especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre. |
| valor | java.lang.Object | Valor. |

**Returns:**
booleano - verdadero, si el canal fue añadido, falso en caso contrario.
### bindKeyframeSequence(String channelName, KeyframeSequence sequence) {#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-}
```
public void bindKeyframeSequence(String channelName, KeyframeSequence sequence)
```


Vincula la secuencia de fotogramas clave al canal especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| channelName | java.lang.String | A qué canal se vinculará la secuencia de fotogramas clave |
| sequence | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | La secuencia de fotogramas clave a vincular |

### createKeyframeSequence(String name) {#createKeyframeSequence-java.lang.String-}
```
public KeyframeSequence createKeyframeSequence(String name)
```


Crea una nueva curva y la conecta al primer canal del mapeo de curvas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | El nombre de la nueva secuencia. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### get(String channelName) {#get-java.lang.String-}
```
public AnimationChannel get(String channelName)
```


Obtiene el canal por el nombre dado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| channelName | java.lang.String | Nombre del canal |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Animation channel
### getChannel(String channelName) {#getChannel-java.lang.String-}
```
public AnimationChannel getChannel(String channelName)
```


Obtiene el canal por el nombre dado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| channelName | java.lang.String | El nombre del canal a buscar |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Channel with the name
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Obtiene el número total de canales de propiedad definidos en este mapeo de curvas de animación.

**Returns:**
int - El recuento de canales.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(String channelName) {#getKeyframeSequence-java.lang.String-}
```
public KeyframeSequence getKeyframeSequence(String channelName)
```


Obtiene la primera secuencia de fotogramas clave en el canal especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| channelName | java.lang.String | El nombre del canal a buscar |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - First keyframe sequence with the channel name
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
### getProperty() {#getProperty--}
```
public Property getProperty()
```


Obtiene la propiedad asociada con el CurveMapping

**Returns:**
[Property](../../com.aspose.threed/property) - the property associated with the CurveMapping
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
### resetChannels() {#resetChannels--}
```
public void resetChannels()
```


Vacía los canales de propiedad de este mapeo de curvas de animación.

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Establece el nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setProperty(Property value) {#setProperty-com.aspose.threed.Property-}
```
public void setProperty(Property value)
```


Obtiene la propiedad asociada con el CurveMapping

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Property](../../com.aspose.threed/property) | Nuevo valor |

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


Formatea el objeto a cadena

**Returns:**
java.lang.String - Cadena del objeto
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

