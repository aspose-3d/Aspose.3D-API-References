---
title: PbrMaterial
second_title: Referencia de API de Aspose.3D para Java
description: Material para renderizado basado en la física basado en color albedo/metallic/roughness
type: docs
weight: 121
url: /es/java/com.aspose.threed/pbrmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrMaterial extends Material
```

Material para renderizado basado en la física basado en color albedo/metallic/roughness
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PbrMaterial()](#PbrMaterial--) | Construir una instancia de material PBR predeterminada |
| [PbrMaterial(Vector3 albedo)](#PbrMaterial-com.aspose.threed.Vector3-) | Construir un material PBR predeterminado con el valor de color albedo especificado |
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
| [fromMaterial(Material material)](#fromMaterial-com.aspose.threed.Material-) | Permitir convertir otro material a PbrMaterial **Ejemplo:** |
| [getAlbedo()](#getAlbedo--) | Obtiene el color base del material |
| [getAlbedoTexture()](#getAlbedoTexture--) | Obtiene la textura para albedo |
| [getClass()](#getClass--) |  |
| [getEmissiveColor()](#getEmissiveColor--) | Obtiene el color emisivo |
| [getEmissiveTexture()](#getEmissiveTexture--) | Obtiene la textura para emisivo |
| [getMetallicFactor()](#getMetallicFactor--) | Obtiene la metalicidad del material, un valor de 1 indica que el material es un metal y un valor de 0 indica que el material es un dieléctrico. |
| [getMetallicRoughness()](#getMetallicRoughness--) | Obtiene la textura para metalicidad (en el canal R) y rugosidad (en el canal G) |
| [getName()](#getName--) | Obtiene el nombre. |
| [getNormalTexture()](#getNormalTexture--) | Obtiene la textura del mapeo normal |
| [getOcclusionFactor()](#getOcclusionFactor--) | Obtiene el factor de oclusión ambiental |
| [getOcclusionTexture()](#getOcclusionTexture--) | Obtiene la textura para oclusión ambiental |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getRoughnessFactor()](#getRoughnessFactor--) | Obtiene la rugosidad del material, un valor de 1 indica que el material es completamente rugoso y un valor de 0 indica que el material es completamente liso. |
| [getSpecularTexture()](#getSpecularTexture--) | Obtiene la textura para color especular |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Obtiene la textura del slot especificado, puede ser el nombre de la propiedad del material o el nombre del parámetro del shader |
| [getTransparency()](#getTransparency--) | Obtiene el factor de transparencia. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Obtiene el enumerador para enumerar los slots de textura internos. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setAlbedo(Vector3 value)](#setAlbedo-com.aspose.threed.Vector3-) | Establece el color base del material |
| [setAlbedoTexture(TextureBase value)](#setAlbedoTexture-com.aspose.threed.TextureBase-) | Establece la textura para albedo |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Establece el color emisivo |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Establece la textura para la emisiva |
| [setMetallicFactor(double value)](#setMetallicFactor-double-) | Establece la metalicidad del material, un valor de 1 indica que el material es un metal y un valor de 0 indica que el material es un dieléctrico. |
| [setMetallicRoughness(TextureBase value)](#setMetallicRoughness-com.aspose.threed.TextureBase-) | Establece la textura para metalicidad (en el canal R) y rugosidad (en el canal G) |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Establece la textura del mapeo normal |
| [setOcclusionFactor(double value)](#setOcclusionFactor-double-) | Establece el factor de oclusión ambiental |
| [setOcclusionTexture(TextureBase value)](#setOcclusionTexture-com.aspose.threed.TextureBase-) | Establece la textura para oclusión ambiental |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setRoughnessFactor(double value)](#setRoughnessFactor-double-) | Establece la rugosidad del material, un valor de 1 indica que el material es completamente rugoso y un valor de 0 indica que el material es completamente liso |
| [setSpecularTexture(TextureBase value)](#setSpecularTexture-com.aspose.threed.TextureBase-) | Establece la textura para el color especular |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Establece la textura al slot especificado |
| [setTransparency(double value)](#setTransparency-double-) | Establece el factor de transparencia. |
| [toString()](#toString--) | Formatea el objeto a cadena |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrMaterial() {#PbrMaterial--}
```
public PbrMaterial()
```


Construir una instancia de material PBR predeterminada

### PbrMaterial(Vector3 albedo) {#PbrMaterial-com.aspose.threed.Vector3-}
```
public PbrMaterial(Vector3 albedo)
```


Construir un material PBR predeterminado con el valor de color albedo especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| albedo | [Vector3](../../com.aspose.threed/vector3) | El valor predeterminado del color albedo |

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
### fromMaterial(Material material) {#fromMaterial-com.aspose.threed.Material-}
```
public static PbrMaterial fromMaterial(Material material)
```


Permitir convertir otro material a PbrMaterial **Ejemplo:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     mat.setDiffuseColor(new Vector3(0.3, 0.9, 0.4));
     PbrMaterial pbr = PbrMaterial.fromMaterial(mat);
```

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| material | [Material](../../com.aspose.threed/material) |  |

**Returns:**
[PbrMaterial](../../com.aspose.threed/pbrmaterial)
### getAlbedo() {#getAlbedo--}
```
public Vector3 getAlbedo()
```


Obtiene el color base del material

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the base color of the material
### getAlbedoTexture() {#getAlbedoTexture--}
```
public TextureBase getAlbedoTexture()
```


Obtiene la textura para albedo

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for albedo
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Obtiene el color emisivo

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Obtiene la textura para emisivo

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getMetallicFactor() {#getMetallicFactor--}
```
public double getMetallicFactor()
```


Obtiene la metalicidad del material, un valor de 1 indica que el material es un metal y un valor de 0 indica que el material es un dieléctrico.

**Returns:**
double - la metalicidad del material, un valor de 1 indica que el material es un metal y un valor de 0 indica que el material es un dieléctrico.
### getMetallicRoughness() {#getMetallicRoughness--}
```
public TextureBase getMetallicRoughness()
```


Obtiene la textura para metalicidad (en el canal R) y rugosidad (en el canal G)

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for metallic(in R channel) and roughness(in G channel)
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
### getOcclusionFactor() {#getOcclusionFactor--}
```
public double getOcclusionFactor()
```


Obtiene el factor de oclusión ambiental

**Returns:**
double - el factor de oclusión ambiental
### getOcclusionTexture() {#getOcclusionTexture--}
```
public TextureBase getOcclusionTexture()
```


Obtiene la textura para oclusión ambiental

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for ambient occlusion
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
### getRoughnessFactor() {#getRoughnessFactor--}
```
public double getRoughnessFactor()
```


Obtiene la rugosidad del material, un valor de 1 indica que el material es completamente rugoso y un valor de 0 indica que el material es completamente liso.

**Returns:**
double - la rugosidad del material, un valor de 1 indica que el material es completamente rugoso y un valor de 0 indica que el material es completamente liso
### getSpecularTexture() {#getSpecularTexture--}
```
public TextureBase getSpecularTexture()
```


Obtiene la textura para color especular

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color
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
### setAlbedo(Vector3 value) {#setAlbedo-com.aspose.threed.Vector3-}
```
public void setAlbedo(Vector3 value)
```


Establece el color base del material

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setAlbedoTexture(TextureBase value) {#setAlbedoTexture-com.aspose.threed.TextureBase-}
```
public void setAlbedoTexture(TextureBase value)
```


Establece la textura para albedo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nuevo valor |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Establece el color emisivo

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

### setMetallicFactor(double value) {#setMetallicFactor-double-}
```
public void setMetallicFactor(double value)
```


Establece la metalicidad del material, un valor de 1 indica que el material es un metal y un valor de 0 indica que el material es un dieléctrico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setMetallicRoughness(TextureBase value) {#setMetallicRoughness-com.aspose.threed.TextureBase-}
```
public void setMetallicRoughness(TextureBase value)
```


Establece la textura para metalicidad (en el canal R) y rugosidad (en el canal G)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nuevo valor |

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

### setOcclusionFactor(double value) {#setOcclusionFactor-double-}
```
public void setOcclusionFactor(double value)
```


Establece el factor de oclusión ambiental

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setOcclusionTexture(TextureBase value) {#setOcclusionTexture-com.aspose.threed.TextureBase-}
```
public void setOcclusionTexture(TextureBase value)
```


Establece la textura para oclusión ambiental

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

### setRoughnessFactor(double value) {#setRoughnessFactor-double-}
```
public void setRoughnessFactor(double value)
```


Establece la rugosidad del material, un valor de 1 indica que el material es completamente rugoso y un valor de 0 indica que el material es completamente liso

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setSpecularTexture(TextureBase value) {#setSpecularTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularTexture(TextureBase value)
```


Establece la textura para el color especular

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

