---
title: "PhongMaterial"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Matériau pour le modèle d'éclairage Blinn-Phong."
type: docs
weight: 126
url: /fr/java/com.aspose.threed/phongmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material), [com.aspose.threed.LambertMaterial](../../com.aspose.threed/lambertmaterial)
```
public class PhongMaterial extends LambertMaterial
```

Matériau pour le modèle d'éclairage Blinn-Phong.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PhongMaterial()](#PhongMaterial--) | Initialise une nouvelle instance de la classe [PhongMaterial](../../com.aspose.threed/phongmaterial). |
| [PhongMaterial(String name)](#PhongMaterial-java.lang.String-) | Initialise une nouvelle instance de la classe [PhongMaterial](../../com.aspose.threed/phongmaterial). |
## Champs

| Champ | Description |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture ambiant. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture diffus. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture émissif. |
| [MAP_NORMAL](#MAP-NORMAL) | Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture normal. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture spéculaire. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getAmbientColor()](#getAmbientColor--) | Obtient la couleur ambiante |
| [getClass()](#getClass--) |  |
| [getDiffuseColor()](#getDiffuseColor--) | Obtient la couleur diffuse |
| [getEmissiveColor()](#getEmissiveColor--) | Obtient la couleur émissive |
| [getName()](#getName--) | Obtient le nom. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getReflectionColor()](#getReflectionColor--) | Obtient la couleur de réflexion. |
| [getReflectionFactor()](#getReflectionFactor--) | Obtient l'atténuation de la couleur de réflexion. |
| [getShininess()](#getShininess--) | Obtient la brillance, cela contrôle la taille du point lumineux spéculaire. |
| [getSpecularColor()](#getSpecularColor--) | Obtient la couleur spéculaire. |
| [getSpecularFactor()](#getSpecularFactor--) | Obtient le facteur spéculaire. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Obtient la texture du slot spécifié, cela peut être le nom de la propriété du matériau ou le nom du paramètre du shader |
| [getTransparency()](#getTransparency--) | Obtient le facteur de transparence. |
| [getTransparentColor()](#getTransparentColor--) | Obtient la couleur transparente. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Obtient l'énumérateur pour parcourir les slots de texture internes. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setAmbientColor(Vector3 value)](#setAmbientColor-com.aspose.threed.Vector3-) | Définit la couleur ambiante |
| [setDiffuseColor(Vector3 value)](#setDiffuseColor-com.aspose.threed.Vector3-) | Définit la couleur diffuse |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Définit la couleur émissive |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setReflectionColor(Vector3 value)](#setReflectionColor-com.aspose.threed.Vector3-) | Définit la couleur de réflexion. |
| [setReflectionFactor(double value)](#setReflectionFactor-double-) | Définit l'atténuation de la couleur de réflexion. |
| [setShininess(double value)](#setShininess-double-) | Définit la brillance, cela contrôle la taille du point lumineux spéculaire. |
| [setSpecularColor(Vector3 value)](#setSpecularColor-com.aspose.threed.Vector3-) | Définit la couleur spéculaire. |
| [setSpecularFactor(double value)](#setSpecularFactor-double-) | Définit le facteur spéculaire. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Définit la texture au slot spécifié |
| [setTransparency(double value)](#setTransparency-double-) | Définit le facteur de transparence. |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | Définit la couleur transparente. |
| [toString()](#toString--) | Formate l'objet en chaîne |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhongMaterial() {#PhongMaterial--}
```
public PhongMaterial()
```


Initialise une nouvelle instance de la classe [PhongMaterial](../../com.aspose.threed/phongmaterial).

### PhongMaterial(String name) {#PhongMaterial-java.lang.String-}
```
public PhongMaterial(String name)
```


Initialise une nouvelle instance de la classe [PhongMaterial](../../com.aspose.threed/phongmaterial).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom |

### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture ambiant.

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture diffus.

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture émissif.

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture normal.

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture spéculaire.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | Nom de la propriété. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAmbientColor() {#getAmbientColor--}
```
public Vector3 getAmbientColor()
```


Obtient la couleur ambiante

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


Obtient la couleur diffuse

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Obtient la couleur émissive

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


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Obtient la collection de toutes les propriétés.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Obtenir la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |

**Returns:**
java.lang.Object - La valeur de la propriété trouvée
### getReflectionColor() {#getReflectionColor--}
```
public Vector3 getReflectionColor()
```


Obtient la couleur de réflexion.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the reflection color.
### getReflectionFactor() {#getReflectionFactor--}
```
public double getReflectionFactor()
```


Obtient l'atténuation de la couleur de réflexion.

**Returns:**
double - l'atténuation de la couleur de réflexion.
### getShininess() {#getShininess--}
```
public double getShininess()
```


Obtient la brillance, cela contrôle la taille du point lumineux spéculaire. La formule du spéculaire : SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - la brillance, cela contrôle la taille du point lumineux spéculaire. La formule du spéculaire : SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
### getSpecularColor() {#getSpecularColor--}
```
public Vector3 getSpecularColor()
```


Obtient la couleur spéculaire.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color.
### getSpecularFactor() {#getSpecularFactor--}
```
public double getSpecularFactor()
```


Obtient le facteur spéculaire. La formule du spéculaire : SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - le facteur spéculaire. La formule du spéculaire : SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


Obtient la texture du slot spécifié, cela peut être le nom de la propriété du matériau ou le nom du paramètre du shader

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| slotName | java.lang.String | Nom du slot. |

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


Obtient le facteur de transparence. Le facteur doit être compris entre 0 (0 %, totalement opaque) et 1 (100 %, totalement transparent). Toute valeur de facteur invalide sera tronquée.

**Returns:**
double - le facteur de transparence. Le facteur doit être compris entre 0 (0 %, totalement opaque) et 1 (100 %, totalement transparent). Toute valeur de facteur invalide sera tronquée.
### getTransparentColor() {#getTransparentColor--}
```
public Vector3 getTransparentColor()
```


Obtient la couleur transparente.

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


Obtient l'énumérateur pour parcourir les slots de texture internes.

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


Supprime une propriété dynamique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Supprime la propriété spécifiée identifiée par son nom

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### setAmbientColor(Vector3 value) {#setAmbientColor-com.aspose.threed.Vector3-}
```
public void setAmbientColor(Vector3 value)
```


Définit la couleur ambiante

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setDiffuseColor(Vector3 value) {#setDiffuseColor-com.aspose.threed.Vector3-}
```
public void setDiffuseColor(Vector3 value)
```


Définit la couleur diffuse

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Définit la couleur émissive

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur **Exemple:** |

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Définit la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |
| valeur | java.lang.Object | La valeur de la propriété |

### setReflectionColor(Vector3 value) {#setReflectionColor-com.aspose.threed.Vector3-}
```
public void setReflectionColor(Vector3 value)
```


Définit la couleur de réflexion.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setReflectionFactor(double value) {#setReflectionFactor-double-}
```
public void setReflectionFactor(double value)
```


Définit l'atténuation de la couleur de réflexion.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setShininess(double value) {#setShininess-double-}
```
public void setShininess(double value)
```


Définit la brillance, cela contrôle la taille du point lumineux spéculaire. La formule du spéculaire : SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setSpecularColor(Vector3 value) {#setSpecularColor-com.aspose.threed.Vector3-}
```
public void setSpecularColor(Vector3 value)
```


Définit la couleur spéculaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setSpecularFactor(double value) {#setSpecularFactor-double-}
```
public void setSpecularFactor(double value)
```


Définit le facteur spéculaire. La formule du spéculaire : SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


Définit la texture au slot spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| slotName | java.lang.String | Nom du slot. |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | Texture. **Exemple:** |

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


Définit le facteur de transparence. Le facteur doit être compris entre 0 (0 %, totalement opaque) et 1 (100 %, totalement transparent). Toute valeur de facteur invalide sera tronquée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setTransparentColor(Vector3 value) {#setTransparentColor-com.aspose.threed.Vector3-}
```
public void setTransparentColor(Vector3 value)
```


Définit la couleur transparente.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### toString() {#toString--}
```
public String toString()
```


Formate l'objet en chaîne

**Returns:**
java.lang.String - Chaîne d'objet
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

