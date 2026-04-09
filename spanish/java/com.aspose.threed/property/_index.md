---
title: StructuralMetadata.Property
second_title: Referencia de API de Aspose.3D para Java
description: La definición de la propiedad en las clases de metadatos.
type: docs
weight: 13
url: /es/java/com.aspose.threed/structuralmetadata.property/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.Property
```

La definición de la propiedad en las clases de metadatos
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) | Constructor de la propiedad de metadatos. |
| [Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) | Constructor de la propiedad de metadatos. |
| [Property(String name, Class<?> type)](#Property-java.lang.String-java.lang.Class----) | Constructor de la propiedad de metadatos. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Cantidad de los datos para una matriz de tamaño fijo. |
| [getDescription()](#getDescription--) | La descripción de la propiedad. |
| [getDisplayName()](#getDisplayName--) | El nombre de la propiedad, utilizado por la UI para su representación. |
| [getEnumType()](#getEnumType--) | El tipo de enumeración. |
| [getName()](#getName--) | El nombre único de la propiedad. |
| [getNormalized()](#getNormalized--) | Indica si los datos están normalizados. |
| [getType()](#getType--) | El tipo de datos de la propiedad. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(Integer value)](#setCount-java.lang.Integer-) | Cantidad de los datos para una matriz de tamaño fijo. |
| [setDescription(String value)](#setDescription-java.lang.String-) | La descripción de la propiedad. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | El nombre de la propiedad, utilizado por la UI para su representación. |
| [setEnumType(StructuralMetadata.EnumType value)](#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-) | El tipo de enumeración. |
| [setNormalized(boolean value)](#setNormalized-boolean-) | Indica si los datos están normalizados. |
| [toString()](#toString--) | Obtiene la representación en cadena de esta instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```


Constructor de la propiedad de metadatos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | El nombre único de la propiedad. |
| displayName | java.lang.String | El nombre de la propiedad, utilizado por la UI para su representación. |
| description | java.lang.String | La descripción de la propiedad. |
| type | java.lang.Class<?> | Tipo de datos de la propiedad. |
| normalized | boolean | Los datos están normalizados. |
| conteo | java.lang.Integer | Cantidad de los datos para una matriz de tamaño fijo |

### Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```


Constructor de la propiedad de metadatos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | El nombre único de la propiedad. |
| displayName | java.lang.String | El nombre de la propiedad, utilizado por la UI para su representación. |
| description | java.lang.String | La descripción de la propiedad. |
| type | [EnumType](../../com.aspose.threed/enumtype) | Tipo de datos de la propiedad. |
| matriz | boolean | ¿Es cada valor de propiedad una matriz o escalar? |
| conteo | java.lang.Integer | Cantidad de los datos para una matriz de tamaño fijo |

### Property(String name, Class<?> type) {#Property-java.lang.String-java.lang.Class----}
```
public Property(String name, Class<?> type)
```


Constructor de la propiedad de metadatos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | El nombre único de la propiedad. |
| type | java.lang.Class<?> | Tipo de datos de la propiedad. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public Integer getCount()
```


Cantidad de los datos para una matriz de tamaño fijo.

**Returns:**
java.lang.Integer - Cantidad de los datos para una matriz de tamaño fijo.
### getDescription() {#getDescription--}
```
public String getDescription()
```


La descripción de la propiedad.

**Returns:**
java.lang.String - La descripción de la propiedad
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


El nombre de la propiedad, utilizado por la UI para su representación.

**Returns:**
java.lang.String - El nombre de la propiedad, usado por la UI para su representación.
### getEnumType() {#getEnumType--}
```
public StructuralMetadata.EnumType getEnumType()
```


El tipo de enumeración.

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - The enum type
### getName() {#getName--}
```
public String getName()
```


El nombre único de la propiedad.

**Returns:**
java.lang.String - El nombre único de la propiedad
### getNormalized() {#getNormalized--}
```
public boolean getNormalized()
```


Indica si los datos están normalizados.

**Returns:**
boolean - ¿Los datos están normalizados.
### getType() {#getType--}
```
public Class<?> getType()
```


El tipo de datos de la propiedad.

**Returns:**
java.lang.Class<?> - El tipo de datos de la propiedad
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




### setCount(Integer value) {#setCount-java.lang.Integer-}
```
public void setCount(Integer value)
```


Cantidad de los datos para una matriz de tamaño fijo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Integer | Nuevo valor |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


La descripción de la propiedad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


El nombre de la propiedad, utilizado por la UI para su representación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setEnumType(StructuralMetadata.EnumType value) {#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-}
```
public void setEnumType(StructuralMetadata.EnumType value)
```


El tipo de enumeración.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EnumType](../../com.aspose.threed/enumtype) | Nuevo valor |

### setNormalized(boolean value) {#setNormalized-boolean-}
```
public void setNormalized(boolean value)
```


Indica si los datos están normalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### toString() {#toString--}
```
public String toString()
```


Obtiene la representación en cadena de esta instancia.

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

