---
title: PhongMaterial
second_title: Referencia de API de Aspose.3D para Java
description: Material para el modelo de sombreado Blinn-Phong.
type: docs
weight: 126
url: /es/java/com.aspose.threed/phongmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material), [com.aspose.threed.LambertMaterial](../../com.aspose.threed/lambertmaterial)
```
public class PhongMaterial extends LambertMaterial
```

Material para el modelo de sombreado Blinn-Phong.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PhongMaterial()](#PhongMaterial--) | Inicializa una nueva instancia de la clase [PhongMaterial](../../com.aspose.threed/phongmaterial). |
| [PhongMaterial(String name)](#PhongMaterial-java.lang.String-) | Inicializa una nueva instancia de la clase [PhongMaterial](../../com.aspose.threed/phongmaterial). |
## Campos

| Campo | Descripción |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura ambiental. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura difusa. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura emisiva. |
| [MAP_NORMAL](#MAP-NORMAL) | Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura normal. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura especular. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getAmbientColor()](#getAmbientColor--) | Obtiene el color ambiental |
| [getClass()](#getClass--) |  |
| [getDiffuseColor()](#getDiffuseColor--) | Obtiene el color difuso |
| [getEmissiveColor()](#getEmissiveColor--) | Obtiene el color emisivo |
| [getName()](#getName--) | Obtiene el nombre. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getReflectionColor()](#getReflectionColor--) | Obtiene el color de reflexión. |
| [getReflectionFactor()](#getReflectionFactor--) | Obtiene la atenuación del color de reflexión. |
| [getShininess()](#getShininess--) | Obtiene el brillo, esto controla el tamaño del resaltado especular. |
| [getSpecularColor()](#getSpecularColor--) | Obtiene el color especular. |
| [getSpecularFactor()](#getSpecularFactor--) | Obtiene el factor especular. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Obtiene la textura del slot especificado, puede ser el nombre de la propiedad del material o el nombre del parámetro del shader |
| [getTransparency()](#getTransparency--) | Obtiene el factor de transparencia. |
| [getTransparentColor()](#getTransparentColor--) | Obtiene el color transparente. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Obtiene el enumerador para enumerar los slots de textura internos. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setAmbientColor(Vector3 value)](#setAmbientColor-com.aspose.threed.Vector3-) | Establece el color ambiental |
| [setDiffuseColor(Vector3 value)](#setDiffuseColor-com.aspose.threed.Vector3-) | Establece el color difuso |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Establece el color emisivo |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setReflectionColor(Vector3 value)](#setReflectionColor-com.aspose.threed.Vector3-) | Establece el color de reflexión. |
| [setReflectionFactor(double value)](#setReflectionFactor-double-) | Establece la atenuación del color de reflexión. |
| [setShininess(double value)](#setShininess-double-) | Establece el brillo, esto controla el tamaño del reflejo especular. |
| [setSpecularColor(Vector3 value)](#setSpecularColor-com.aspose.threed.Vector3-) | Establece el color especular. |
| [setSpecularFactor(double value)](#setSpecularFactor-double-) | Establece el factor especular. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Establece la textura al slot especificado |
| [setTransparency(double value)](#setTransparency-double-) | Establece el factor de transparencia. |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | Establece el color transparente. |
| [toString()](#toString--) | Formatea el objeto a cadena |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhongMaterial() {#PhongMaterial--}
```
public PhongMaterial()
```


Inicializa una nueva instancia de la clase [PhongMaterial](../../com.aspose.threed/phongmaterial).

### PhongMaterial(String name) {#PhongMaterial-java.lang.String-}
```
public PhongMaterial(String name)
```


Inicializa una nueva instancia de la clase [PhongMaterial](../../com.aspose.threed/phongmaterial).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre |

### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura ambiental.

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura difusa.

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura emisiva.

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura normal.

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura especular.

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
### getAmbientColor() {#getAmbientColor--}
```
public Vector3 getAmbientColor()
```


Obtiene el color ambiental

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the ambient color
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDiffuseColor() {#getDiffuseColor--}
```
public Vector3 getDiffuseColor()
```


Obtiene el color difuso

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Obtiene el color emisivo

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color **Example:**

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
```
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
### getReflectionColor() {#getReflectionColor--}
```
public Vector3 getReflectionColor()
```


Obtiene el color de reflexión.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the reflection color.
### getReflectionFactor() {#getReflectionFactor--}
```
public double getReflectionFactor()
```


Obtiene la atenuación del color de reflexión.

**Returns:**
double - la atenuación del color de reflexión.
### getShininess() {#getShininess--}
```
public double getShininess()
```


Obtiene el brillo, esto controla el tamaño del reflejo especular. La fórmula del especular: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - el brillo, esto controla el tamaño del reflejo especular. La fórmula del especular: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
### getSpecularColor() {#getSpecularColor--}
```
public Vector3 getSpecularColor()
```


Obtiene el color especular.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color.
### getSpecularFactor() {#getSpecularFactor--}
```
public double getSpecularFactor()
```


Obtiene el factor especular. La fórmula del especular: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - el factor especular. La fórmula del especular: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


Obtiene la textura del slot especificado, puede ser el nombre de la propiedad del material o el nombre del parámetro del shader

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slotName | java.lang.String | Nombre de la ranura. |

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - The texture. **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     tex = (Texture)mat.getTexture(Material.MAP_DIFFUSE);
```
### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Obtiene el factor de transparencia. El factor debe estar en el rango entre 0(0%, totalmente opaco) y 1(100%, totalmente transparente) Cualquier valor de factor no válido será limitado.

**Returns:**
double - el factor de transparencia. El factor debe estar en el rango entre 0(0%, totalmente opaco) y 1(100%, totalmente transparente) Cualquier valor de factor no válido será limitado.
### getTransparentColor() {#getTransparentColor--}
```
public Vector3 getTransparentColor()
```


Obtiene el color transparente.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the transparent color.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<TextureSlot> iterator()
```


Obtiene el enumerador para enumerar los slots de textura internos.

**Returns:**
java.util.Iterator<com.aspose.threed.TextureSlot>
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
### setAmbientColor(Vector3 value) {#setAmbientColor-com.aspose.threed.Vector3-}
```
public void setAmbientColor(Vector3 value)
```


Establece el color ambiental

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setDiffuseColor(Vector3 value) {#setDiffuseColor-com.aspose.threed.Vector3-}
```
public void setDiffuseColor(Vector3 value)
```


Establece el color difuso

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Establece el color emisivo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor **Ejemplo:** |

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
``` |

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

### setReflectionColor(Vector3 value) {#setReflectionColor-com.aspose.threed.Vector3-}
```
public void setReflectionColor(Vector3 value)
```


Establece el color de reflexión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setReflectionFactor(double value) {#setReflectionFactor-double-}
```
public void setReflectionFactor(double value)
```


Establece la atenuación del color de reflexión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setShininess(double value) {#setShininess-double-}
```
public void setShininess(double value)
```


Establece el brillo, esto controla el tamaño del reflejo especular. La fórmula del especular: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setSpecularColor(Vector3 value) {#setSpecularColor-com.aspose.threed.Vector3-}
```
public void setSpecularColor(Vector3 value)
```


Establece el color especular.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setSpecularFactor(double value) {#setSpecularFactor-double-}
```
public void setSpecularFactor(double value)
```


Establece el factor especular. La fórmula del especular: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


Establece la textura al slot especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slotName | java.lang.String | Nombre de la ranura. |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | Textura. **Ejemplo:** |

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_NORMAL, tex);
``` |

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Establece el factor de transparencia. El factor debe estar en el rango entre 0(0%, totalmente opaco) y 1(100%, totalmente transparente) Cualquier valor de factor no válido será limitado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setTransparentColor(Vector3 value) {#setTransparentColor-com.aspose.threed.Vector3-}
```
public void setTransparentColor(Vector3 value)
```


Establece el color transparente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

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

