---
title: StructuralMetadata.PropertyTable
second_title: Referencia de API de Aspose.3D para Java
description: Tabla de propiedades.
type: docs
weight: 14
url: /es/java/com.aspose.threed/structuralmetadata.propertytable/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.PropertyTable
```

Tabla de propiedades.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Constructor de la tabla de propiedades. |
## Métodos

| Método | Descripción |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | Agregar una nueva propiedad a la tabla de propiedades. |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | Agregar una nueva propiedad a la tabla de propiedades. |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | Adjuntar la tabla de propiedades actual a los datos de usuario especificados |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | Extraer la tabla de propiedades adjunta de los datos de usuario especificados |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | La metaclase de esta tabla de propiedades. |
| [getName()](#getName--) | Nombre de la tabla de propiedades. |
| [getValue(String name)](#getValue-java.lang.String-) | Obtiene el valor del nombre de propiedad especificado |
| [getValues()](#getValues--) | Valores de la tabla de propiedades. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PropertyTable(String name, StructuralMetadata.ClassType mclass) {#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public PropertyTable(String name, StructuralMetadata.ClassType mclass)
```


Constructor de la tabla de propiedades.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | El nombre de esta instancia de tabla. |
| mclass | [ClassType](../../com.aspose.threed/classtype) | La definición de la metaclase de esta tabla de propiedades |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


Agregar una nueva propiedad a la tabla de propiedades.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | Qué propiedad agregar con valor |
| valor | java.lang.Object | Arreglo de valores |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


Agregar una nueva propiedad a la tabla de propiedades.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propName | java.lang.String | Qué propiedad agregar con valor |
| valor | java.lang.Object | Arreglo de valores |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


Adjuntar la tabla de propiedades actual a los datos de usuario especificados

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

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
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


Extraer la tabla de propiedades adjunta de los datos de usuario especificados

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | Los datos de usuario que están asociados con una tabla de propiedades |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The associated property table instance
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMetaClass() {#getMetaClass--}
```
public StructuralMetadata.ClassType getMetaClass()
```


La metaclase de esta tabla de propiedades.

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


Nombre de la tabla de propiedades.

**Returns:**
java.lang.String - Nombre de la tabla de propiedades.
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


Obtiene el valor del nombre de propiedad especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre de la propiedad |

**Returns:**
java.lang.Object - Valor de la propiedad o null si no se encuentra
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


Valores de la tabla de propiedades.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> - Valores de la tabla de propiedades.
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

