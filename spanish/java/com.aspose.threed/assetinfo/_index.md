---
title: AssetInfo
second_title: Referencia de API de Aspose.3D para Java
description: Información del activo.
type: docs
weight: 17
url: /es/java/com.aspose.threed/assetinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AssetInfo extends A3DObject
```

Información del activo. La información del activo puede adjuntarse a una [Scene](../../com.aspose.threed/scene). La [Scene](../../com.aspose.threed/scene) hija puede tener su propio [AssetInfo](../../com.aspose.threed/assetinfo) para sobrescribir la definición del padre. **Ejemplo:** El siguiente código muestra cómo leer la información del activo desde un archivo fbx:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The file is created at %s by %s %s",
          scene.getAssetInfo().getCreationTime(),
          scene.getAssetInfo().getApplicationName(),
          scene.getAssetInfo().getApplicationVersion());
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AssetInfo()](#AssetInfo--) | Inicializa una nueva instancia de la clase [AssetInfo](../../com.aspose.threed/assetinfo). |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | Inicializa una nueva instancia de la clase [AssetInfo](../../com.aspose.threed/assetinfo). |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getAmbient()](#getAmbient--) | Obtiene o establece el color ambiental predeterminado de este activo |
| [getApplicationName()](#getApplicationName--) | Obtiene la aplicación que creó este activo |
| [getApplicationVendor()](#getApplicationVendor--) | Obtiene el nombre del proveedor de la aplicación |
| [getApplicationVersion()](#getApplicationVersion--) | Obtiene la versión de la aplicación que creó este activo. |
| [getAuthor()](#getAuthor--) | Obtiene el autor de este activo |
| [getAxisSystem()](#getAxisSystem--) | Obtiene el sistema de coordenadas / vector ascendente / vector frontal de la información del activo. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Obtiene el comentario de este activo. |
| [getCoordinateSystem()](#getCoordinateSystem--) | Obtiene el sistema de coordenadas usado en este activo. |
| [getCopyright()](#getCopyright--) | Obtiene el copyright del documento |
| [getCreationTime()](#getCreationTime--) | Obtiene o establece la hora de creación de este activo |
| [getFrontVector()](#getFrontVector--) | Obtiene el vector frontal usado en este activo. |
| [getKeywords()](#getKeywords--) | Obtiene las palabras clave de este activo |
| [getModificationTime()](#getModificationTime--) | Obtiene o establece la hora de modificación de este activo |
| [getName()](#getName--) | Obtiene el nombre. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getRevision()](#getRevision--) | Obtiene el número de revisión de este activo, usualmente usado en sistemas de control de versiones. |
| [getSubject()](#getSubject--) | Obtiene el asunto de este activo |
| [getTitle()](#getTitle--) | Obtiene el título de este activo |
| [getUnitName()](#getUnitName--) | Obtiene la unidad de longitud usada en este activo. |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | Obtiene el factor de escala a metro del mundo real. |
| [getUpVector()](#getUpVector--) | Obtiene el vector ascendente usado en este activo. |
| [getUrl()](#getUrl--) | Obtiene o establece la URL de este activo. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | Obtiene o establece el color ambiental predeterminado de este activo |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | Establece la aplicación que creó este activo |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | Establece el nombre del proveedor de la aplicación |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | Establece la versión de la aplicación que creó este activo. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Establece el autor de este activo |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Establece el sistema de coordenadas/vector ascendente/vector frontal de la información del activo. |
| [setComment(String value)](#setComment-java.lang.String-) | Establece el comentario de este activo. |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | Establece el sistema de coordenadas usado en este activo. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Establece el copyright del documento |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | Obtiene o establece la hora de creación de este activo |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | Establece el vector frontal usado en este activo. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Establece las palabras clave de este activo |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | Obtiene o establece la hora de modificación de este activo |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setRevision(String value)](#setRevision-java.lang.String-) | Establece el número de revisión de este activo, usualmente usado en sistemas de control de versiones. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Establece el asunto de este activo |
| [setTitle(String value)](#setTitle-java.lang.String-) | Establece el título de este activo |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | Establece la unidad de longitud usada en este activo. |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | Establece el factor de escala a metros del mundo real. |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | Establece el vector ascendente usado en este activo. |
| [setUrl(String value)](#setUrl-java.lang.String-) | Obtiene o establece la URL de este activo. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


Inicializa una nueva instancia de la clase [AssetInfo](../../com.aspose.threed/assetinfo).

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


Inicializa una nueva instancia de la clase [AssetInfo](../../com.aspose.threed/assetinfo).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre |

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
### getAmbient() {#getAmbient--}
```
public Vector4 getAmbient()
```


Obtiene o establece el color ambiental predeterminado de este activo

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - or Sets the default ambient color of this asset
### getApplicationName() {#getApplicationName--}
```
public String getApplicationName()
```


Obtiene la aplicación que creó este activo

**Returns:**
java.lang.String - la aplicación que creó este activo
### getApplicationVendor() {#getApplicationVendor--}
```
public String getApplicationVendor()
```


Obtiene el nombre del proveedor de la aplicación

**Returns:**
java.lang.String - el nombre del proveedor de la aplicación
### getApplicationVersion() {#getApplicationVersion--}
```
public String getApplicationVersion()
```


Obtiene la versión de la aplicación que creó este activo.

**Returns:**
java.lang.String - la versión de la aplicación que creó este activo.
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Obtiene el autor de este activo

**Returns:**
java.lang.String - el autor de este activo
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Obtiene el sistema de coordenadas / vector ascendente / vector frontal de la información del activo.

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the coordinate system/up vector/front vector of the asset info.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public String getComment()
```


Obtiene el comentario de este activo.

**Returns:**
java.lang.String - el comentario de este activo.
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


Obtiene el sistema de coordenadas usado en este activo.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system used in this asset.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Obtiene el copyright del documento

**Returns:**
java.lang.String - el copyright del documento
### getCreationTime() {#getCreationTime--}
```
public Calendar getCreationTime()
```


Obtiene o establece la hora de creación de este activo

**Returns:**
java.util.Calendar - o Establece la hora de creación de este activo
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


Obtiene el vector frontal usado en este activo.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Obtiene las palabras clave de este activo

**Returns:**
java.lang.String - las palabras clave de este activo
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


Obtiene o establece la hora de modificación de este activo

**Returns:**
java.util.Calendar - o Establece la hora de modificación de este activo
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
### getRevision() {#getRevision--}
```
public String getRevision()
```


Obtiene el número de revisión de este activo, usualmente usado en sistemas de control de versiones.

**Returns:**
java.lang.String - el número de revisión de este activo, usualmente usado en sistemas de control de versiones.
### getSubject() {#getSubject--}
```
public String getSubject()
```


Obtiene el asunto de este activo

**Returns:**
java.lang.String - el asunto de este activo
### getTitle() {#getTitle--}
```
public String getTitle()
```


Obtiene el título de este activo

**Returns:**
java.lang.String - el título de este activo
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


Obtiene la unidad de longitud usada en este activo. p. ej. cm/m/km/pulgada/pies

**Returns:**
java.lang.String - la unidad de longitud usada en este activo. p. ej. cm/m/km/pulgada/pies
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


Obtiene el factor de escala a metro del mundo real.

**Returns:**
double - el factor de escala a metros del mundo real. **Observaciones:** Esto se ignora durante la serialización si el nombre de la unidad es nulo.
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


Obtiene el vector ascendente usado en este activo.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


Obtiene o establece la URL de este activo.

**Returns:**
java.lang.String - o Establece la URL de este activo.
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
### setAmbient(Vector4 value) {#setAmbient-com.aspose.threed.Vector4-}
```
public void setAmbient(Vector4 value)
```


Obtiene o establece el color ambiental predeterminado de este activo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector4](../../com.aspose.threed/vector4) | Nuevo valor |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


Establece la aplicación que creó este activo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


Establece el nombre del proveedor de la aplicación

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


Establece la versión de la aplicación que creó este activo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Establece el autor de este activo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


Establece el sistema de coordenadas/vector ascendente/vector frontal de la información del activo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Nuevo valor |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Establece el comentario de este activo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


Establece el sistema de coordenadas usado en este activo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Nuevo valor |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Establece el copyright del documento

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


Obtiene o establece la hora de creación de este activo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Calendar | Nuevo valor |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


Establece el vector frontal usado en este activo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Nuevo valor |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Establece las palabras clave de este activo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


Obtiene o establece la hora de modificación de este activo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Calendar | Nuevo valor |

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

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


Establece el número de revisión de este activo, usualmente usado en sistemas de control de versiones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Establece el asunto de este activo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Establece el título de este activo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


Establece la unidad de longitud usada en este activo. p. ej. cm/m/km/pulgada/pies

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


Establece el factor de escala a metros del mundo real.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor **Observaciones:** Esto se ignora durante la serialización si el nombre de la unidad es nulo. |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


Establece el vector ascendente usado en este activo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Nuevo valor |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


Obtiene o establece la URL de este activo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

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

