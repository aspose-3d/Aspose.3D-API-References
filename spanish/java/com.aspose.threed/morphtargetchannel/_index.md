---
title: MorphTargetChannel
second_title: Referencia de API de Aspose.3D para Java
description: Un MorphTargetChannel se usa por  para organizar las geometrías objetivo.
type: docs
weight: 107
url: /es/java/com.aspose.threed/morphtargetchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class MorphTargetChannel extends A3DObject
```

Un MorphTargetChannel se usa por [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) para organizar las geometrías objetivo. Algunos formatos de archivo como FBX admiten múltiples canales en paralelo. **Observaciones:** El peso está entre 0 y 1.0, y el peso predeterminado para el objetivo es 0.0;
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MorphTargetChannel(String name)](#MorphTargetChannel-java.lang.String-) | Inicializa una nueva instancia de la clase [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel). |
| [MorphTargetChannel()](#MorphTargetChannel--) | Inicializa una nueva instancia de la clase [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel). |
## Campos

| Campo | Descripción |
| --- | --- |
| [DEFAULT_WEIGHT](#DEFAULT-WEIGHT) | Peso predeterminado para morph target. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | Obtiene el peso para la geometría especificada |
| [getChannelWeight()](#getChannelWeight--) | Obtiene el peso del deformador de este canal. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Obtiene el nombre. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getTargets()](#getTargets--) | Obtiene todos los objetivos asociados con el canal. |
| [getWeight(Shape target)](#getWeight-com.aspose.threed.Shape-) | Obtiene el peso para el objetivo especificado, si el objetivo no pertenece a este canal, se devuelve el valor predeterminado 0. |
| [getWeights()](#getWeights--) | Obtiene los valores completos de peso de las geometrías objetivo. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | Establece el peso para la geometría especificada |
| [setChannelWeight(double value)](#setChannelWeight-double-) | Establece el peso del deformador de este canal. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setWeight(Shape target)](#setWeight-com.aspose.threed.Shape-) | Establece el peso para el objetivo especificado, el valor predeterminado es 1, el rango debe estar entre 0~1 |
| [setWeight(Shape target, double weight)](#setWeight-com.aspose.threed.Shape-double-) | Establece el peso para el objetivo especificado, el valor predeterminado es 1, el rango debe estar entre 0~1 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetChannel(String name) {#MorphTargetChannel-java.lang.String-}
```
public MorphTargetChannel(String name)
```


Inicializa una nueva instancia de la clase [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre. |

### MorphTargetChannel() {#MorphTargetChannel--}
```
public MorphTargetChannel()
```


Inicializa una nueva instancia de la clase [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel).

### DEFAULT_WEIGHT {#DEFAULT-WEIGHT}
```
public static final double DEFAULT_WEIGHT
```


Peso predeterminado para morph target.

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


Obtiene el peso para la geometría especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Geometría objetivo. |

**Returns:**
double - Peso
### getChannelWeight() {#getChannelWeight--}
```
public double getChannelWeight()
```


Obtiene el peso del deformador de este canal. El peso está entre 0.0 y 1.0

**Returns:**
double - el peso del deformador de este canal. El peso está entre 0.0 y 1.0
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getTargets() {#getTargets--}
```
public List<Shape> getTargets()
```


Obtiene todos los objetivos asociados con el canal.

**Returns:**
java.util.List<com.aspose.threed.Shape> - todos los objetivos asociados con el canal.
### getWeight(Shape target) {#getWeight-com.aspose.threed.Shape-}
```
public double getWeight(Shape target)
```


Obtiene el peso para el objetivo especificado, si el objetivo no pertenece a este canal, se devuelve el valor predeterminado 0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

**Returns:**
double
### getWeights() {#getWeights--}
```
public List<Double> getWeights()
```


Obtiene los valores completos de peso de las geometrías objetivo.

**Returns:**
java.util.List<java.lang.Double> - los valores completos de peso de las geometrías objetivo.
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


Establece el peso para la geometría especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Geometría objetivo. |
| valor | double | Nuevo valor |

### setChannelWeight(double value) {#setChannelWeight-double-}
```
public void setChannelWeight(double value)
```


Establece el peso del deformador de este canal. El peso está entre 0.0 y 1.0

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

### setWeight(Shape target) {#setWeight-com.aspose.threed.Shape-}
```
public void setWeight(Shape target)
```


Establece el peso para el objetivo especificado, el valor predeterminado es 1, el rango debe estar entre 0~1

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

### setWeight(Shape target, double weight) {#setWeight-com.aspose.threed.Shape-double-}
```
public void setWeight(Shape target, double weight)
```


Establece el peso para el objetivo especificado, el valor predeterminado es 1, el rango debe estar entre 0~1

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |
| peso | double |  |

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

