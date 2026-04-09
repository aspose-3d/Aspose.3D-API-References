---
title: PbrSpecularMaterial
second_title: Referencia de API de Aspose.3D para Java
description: Material para renderizado basado en la física basado en color difuso/especular/brillo
type: docs
weight: 122
url: /es/java/com.aspose.threed/pbrspecularmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrSpecularMaterial extends Material
```

Material para renderizado basado en la física basado en color difuso/especular/brillo
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PbrSpecularMaterial()](#PbrSpecularMaterial--) | Constructor de la [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) |
## Campos

| Campo | Descripción |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura ambiental. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura difusa. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura emisiva. |
| [MAP_NORMAL](#MAP-NORMAL) | Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura normal. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Usado en [setTexture](../../com.aspose.threed/material\#setTexture) para asignar un mapeo de textura especular. |
| [MAP_SPECULAR_GLOSSINESS](#MAP-SPECULAR-GLOSSINESS) | El mapa de textura para el brillo especular |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getClass()](#getClass--) |  |
| [getDiffuse()](#getDiffuse--) | Obtiene el color difuso del material, el valor predeterminado es (1, 1, 1) |
| [getDiffuseTexture()](#getDiffuseTexture--) | Obtiene la textura para difuso |
| [getEmissiveColor()](#getEmissiveColor--) | Obtiene el color emisivo, el valor predeterminado es (0, 0, 0) |
| [getEmissiveTexture()](#getEmissiveTexture--) | Obtiene la textura para emisivo |
| [getGlossinessFactor()](#getGlossinessFactor--) | Obtiene el brillo (suavidad) del material, 1 significa perfectamente liso y 0 significa perfectamente rugoso, el valor predeterminado es 1, el rango es [0, 1] |
| [getName()](#getName--) | Obtiene el nombre. |
| [getNormalTexture()](#getNormalTexture--) | Obtiene la textura del mapeo normal |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getSpecular()](#getSpecular--) | Obtiene el color especular del material, el valor predeterminado es (1, 1, 1). |
| [getSpecularGlossinessTexture()](#getSpecularGlossinessTexture--) | Obtiene la textura para el color especular, el canal RGB almacena el color especular y el canal A almacena el brillo. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Obtiene la textura del slot especificado, puede ser el nombre de la propiedad del material o el nombre del parámetro del shader |
| [getTransparency()](#getTransparency--) | Obtiene el factor de transparencia. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Obtiene el enumerador para enumerar los slots de textura internos. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setDiffuse(Vector3 value)](#setDiffuse-com.aspose.threed.Vector3-) | Establece el color difuso del material, el valor predeterminado es (1, 1, 1) |
| [setDiffuseTexture(TextureBase value)](#setDiffuseTexture-com.aspose.threed.TextureBase-) | Establece la textura para difuso |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Establece el color emisivo, el valor predeterminado es (0, 0, 0) |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Establece la textura para la emisiva |
| [setGlossinessFactor(double value)](#setGlossinessFactor-double-) | Establece el brillo (suavidad) del material, 1 significa perfectamente liso y 0 significa perfectamente rugoso, el valor predeterminado es 1, el rango es [0, 1] |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Establece la textura del mapeo normal |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setSpecular(Vector3 value)](#setSpecular-com.aspose.threed.Vector3-) | Establece el color especular del material, el valor predeterminado es (1, 1, 1). |
| [setSpecularGlossinessTexture(TextureBase value)](#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-) | Establece la textura para el color especular, el canal RGB almacena el color especular y el canal A almacena el brillo. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Establece la textura al slot especificado |
| [setTransparency(double value)](#setTransparency-double-) | Establece el factor de transparencia. |
| [toString()](#toString--) | Formatea el objeto a cadena |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrSpecularMaterial() {#PbrSpecularMaterial--}
```
public PbrSpecularMaterial()
```


Constructor de la [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial)

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

### MAP_SPECULAR_GLOSSINESS {#MAP-SPECULAR-GLOSSINESS}
```
public static final String MAP_SPECULAR_GLOSSINESS
```


El mapa de textura para el brillo especular

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDiffuse() {#getDiffuse--}
```
public Vector3 getDiffuse()
```


Obtiene el color difuso del material, el valor predeterminado es (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color of the material, default value is (1, 1, 1)
### getDiffuseTexture() {#getDiffuseTexture--}
```
public TextureBase getDiffuseTexture()
```


Obtiene la textura para difuso

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for diffuse
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Obtiene el color emisivo, el valor predeterminado es (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color, default value is (0, 0, 0)
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Obtiene la textura para emisivo

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getGlossinessFactor() {#getGlossinessFactor--}
```
public double getGlossinessFactor()
```


Obtiene el brillo (suavidad) del material, 1 significa perfectamente liso y 0 significa perfectamente rugoso, el valor predeterminado es 1, el rango es [0, 1]

**Returns:**
double - el brillo (suavidad) del material, 1 significa perfectamente liso y 0 significa perfectamente rugoso, el valor predeterminado es 1, el rango es [0, 1]
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre.

**Returns:**
java.lang.String - el nombre.
### getNormalTexture() {#getNormalTexture--}
```
public TextureBase getNormalTexture()
```


Obtiene la textura del mapeo normal

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture of normal mapping
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
### getSpecular() {#getSpecular--}
```
public Vector3 getSpecular()
```


Obtiene el color especular del material, el valor predeterminado es (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color of the material, default value is (1, 1, 1).
### getSpecularGlossinessTexture() {#getSpecularGlossinessTexture--}
```
public TextureBase getSpecularGlossinessTexture()
```


Obtiene la textura para el color especular, el canal RGB almacena el color especular y el canal A almacena el brillo.

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color, channel RGB stores the specular color and channel A stores the glossiness.
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
### setDiffuse(Vector3 value) {#setDiffuse-com.aspose.threed.Vector3-}
```
public void setDiffuse(Vector3 value)
```


Establece el color difuso del material, el valor predeterminado es (1, 1, 1)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setDiffuseTexture(TextureBase value) {#setDiffuseTexture-com.aspose.threed.TextureBase-}
```
public void setDiffuseTexture(TextureBase value)
```


Establece la textura para difuso

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nuevo valor |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Establece el color emisivo, el valor predeterminado es (0, 0, 0)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setEmissiveTexture(TextureBase value) {#setEmissiveTexture-com.aspose.threed.TextureBase-}
```
public void setEmissiveTexture(TextureBase value)
```


Establece la textura para la emisiva

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nuevo valor |

### setGlossinessFactor(double value) {#setGlossinessFactor-double-}
```
public void setGlossinessFactor(double value)
```


Establece el brillo (suavidad) del material, 1 significa perfectamente liso y 0 significa perfectamente rugoso, el valor predeterminado es 1, el rango es [0, 1]

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

### setNormalTexture(TextureBase value) {#setNormalTexture-com.aspose.threed.TextureBase-}
```
public void setNormalTexture(TextureBase value)
```


Establece la textura del mapeo normal

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nuevo valor |

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

### setSpecular(Vector3 value) {#setSpecular-com.aspose.threed.Vector3-}
```
public void setSpecular(Vector3 value)
```


Establece el color especular del material, el valor predeterminado es (1, 1, 1).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setSpecularGlossinessTexture(TextureBase value) {#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularGlossinessTexture(TextureBase value)
```


Establece la textura para el color especular, el canal RGB almacena el color especular y el canal A almacena el brillo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nuevo valor |

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

