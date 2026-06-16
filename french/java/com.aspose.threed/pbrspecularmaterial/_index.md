---
title: "PbrSpecularMaterial"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Matériau pour le rendu physiquement basé sur la couleur diffuse/speculaire/brillance"
type: docs
weight: 122
url: /fr/java/com.aspose.threed/pbrspecularmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrSpecularMaterial extends Material
```

Matériau pour le rendu physiquement basé sur la couleur diffuse/speculaire/brillance
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PbrSpecularMaterial()](#PbrSpecularMaterial--) | Constructeur de la [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) |
## Champs

| Champ | Description |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture ambiant. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture diffus. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture émissif. |
| [MAP_NORMAL](#MAP-NORMAL) | Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture normal. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Utilisé dans [setTexture](../../com.aspose.threed/material\#setTexture) pour assigner un mappage de texture spéculaire. |
| [MAP_SPECULAR_GLOSSINESS](#MAP-SPECULAR-GLOSSINESS) | La carte de texture pour la brillance spéculaire |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getClass()](#getClass--) |  |
| [getDiffuse()](#getDiffuse--) | Obtient la couleur diffuse du matériau, la valeur par défaut est (1, 1, 1) |
| [getDiffuseTexture()](#getDiffuseTexture--) | Obtient la texture pour le diffuse |
| [getEmissiveColor()](#getEmissiveColor--) | Obtient la couleur émissive, la valeur par défaut est (0, 0, 0) |
| [getEmissiveTexture()](#getEmissiveTexture--) | Obtient la texture pour l'émissif |
| [getGlossinessFactor()](#getGlossinessFactor--) | Obtient la brillance (lissage) du matériau, 1 signifie parfaitement lisse et 0 signifie parfaitement rugueux, la valeur par défaut est 1, la plage est [0, 1] |
| [getName()](#getName--) | Obtient le nom. |
| [getNormalTexture()](#getNormalTexture--) | Obtient la texture du mappage normal |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getSpecular()](#getSpecular--) | Obtient la couleur spéculaire du matériau, la valeur par défaut est (1, 1, 1). |
| [getSpecularGlossinessTexture()](#getSpecularGlossinessTexture--) | Obtient la texture pour la couleur spéculaire, le canal RGB stocke la couleur spéculaire et le canal A stocke la brillance. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Obtient la texture du slot spécifié, cela peut être le nom de la propriété du matériau ou le nom du paramètre du shader |
| [getTransparency()](#getTransparency--) | Obtient le facteur de transparence. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Obtient l'énumérateur pour parcourir les slots de texture internes. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setDiffuse(Vector3 value)](#setDiffuse-com.aspose.threed.Vector3-) | Définit la couleur diffuse du matériau, la valeur par défaut est (1, 1, 1) |
| [setDiffuseTexture(TextureBase value)](#setDiffuseTexture-com.aspose.threed.TextureBase-) | Définit la texture pour le diffuse |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Définit la couleur émissive, la valeur par défaut est (0, 0, 0) |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Définit la texture pour l'émissif |
| [setGlossinessFactor(double value)](#setGlossinessFactor-double-) | Définit la brillance (lissage) du matériau, 1 signifie parfaitement lisse et 0 signifie parfaitement rugueux, la valeur par défaut est 1, la plage est [0, 1] |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Définit la texture du mappage normal |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setSpecular(Vector3 value)](#setSpecular-com.aspose.threed.Vector3-) | Définit la couleur spéculaire du matériau, la valeur par défaut est (1, 1, 1). |
| [setSpecularGlossinessTexture(TextureBase value)](#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-) | Définit la texture pour la couleur spéculaire, le canal RGB stocke la couleur spéculaire et le canal A stocke la brillance. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Définit la texture au slot spécifié |
| [setTransparency(double value)](#setTransparency-double-) | Définit le facteur de transparence. |
| [toString()](#toString--) | Formate l'objet en chaîne |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrSpecularMaterial() {#PbrSpecularMaterial--}
```
public PbrSpecularMaterial()
```


Constructeur de la [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial)

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

### MAP_SPECULAR_GLOSSINESS {#MAP-SPECULAR-GLOSSINESS}
```
public static final String MAP_SPECULAR_GLOSSINESS
```


La carte de texture pour la brillance spéculaire

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


Obtient la couleur diffuse du matériau, la valeur par défaut est (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color of the material, default value is (1, 1, 1)
### getDiffuseTexture() {#getDiffuseTexture--}
```
public TextureBase getDiffuseTexture()
```


Obtient la texture pour le diffuse

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for diffuse
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Obtient la couleur émissive, la valeur par défaut est (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color, default value is (0, 0, 0)
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Obtient la texture pour l'émissif

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getGlossinessFactor() {#getGlossinessFactor--}
```
public double getGlossinessFactor()
```


Obtient la brillance (lissage) du matériau, 1 signifie parfaitement lisse et 0 signifie parfaitement rugueux, la valeur par défaut est 1, la plage est [0, 1]

**Returns:**
double - la brillance (lissage) du matériau, 1 signifie parfaitement lisse et 0 signifie parfaitement rugueux, la valeur par défaut est 1, la plage est [0, 1]
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getNormalTexture() {#getNormalTexture--}
```
public TextureBase getNormalTexture()
```


Obtient la texture du mappage normal

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture of normal mapping
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
### getSpecular() {#getSpecular--}
```
public Vector3 getSpecular()
```


Obtient la couleur spéculaire du matériau, la valeur par défaut est (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color of the material, default value is (1, 1, 1).
### getSpecularGlossinessTexture() {#getSpecularGlossinessTexture--}
```
public TextureBase getSpecularGlossinessTexture()
```


Obtient la texture pour la couleur spéculaire, le canal RGB stocke la couleur spéculaire et le canal A stocke la brillance.

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color, channel RGB stores the specular color and channel A stores the glossiness.
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
### setDiffuse(Vector3 value) {#setDiffuse-com.aspose.threed.Vector3-}
```
public void setDiffuse(Vector3 value)
```


Définit la couleur diffuse du matériau, la valeur par défaut est (1, 1, 1)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setDiffuseTexture(TextureBase value) {#setDiffuseTexture-com.aspose.threed.TextureBase-}
```
public void setDiffuseTexture(TextureBase value)
```


Définit la texture pour le diffuse

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nouvelle valeur |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Définit la couleur émissive, la valeur par défaut est (0, 0, 0)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setEmissiveTexture(TextureBase value) {#setEmissiveTexture-com.aspose.threed.TextureBase-}
```
public void setEmissiveTexture(TextureBase value)
```


Définit la texture pour l'émissif

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nouvelle valeur |

### setGlossinessFactor(double value) {#setGlossinessFactor-double-}
```
public void setGlossinessFactor(double value)
```


Définit la brillance (lissage) du matériau, 1 signifie parfaitement lisse et 0 signifie parfaitement rugueux, la valeur par défaut est 1, la plage est [0, 1]

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setNormalTexture(TextureBase value) {#setNormalTexture-com.aspose.threed.TextureBase-}
```
public void setNormalTexture(TextureBase value)
```


Définit la texture du mappage normal

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nouvelle valeur |

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

### setSpecular(Vector3 value) {#setSpecular-com.aspose.threed.Vector3-}
```
public void setSpecular(Vector3 value)
```


Définit la couleur spéculaire du matériau, la valeur par défaut est (1, 1, 1).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setSpecularGlossinessTexture(TextureBase value) {#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularGlossinessTexture(TextureBase value)
```


Définit la texture pour la couleur spéculaire, le canal RGB stocke la couleur spéculaire et le canal A stocke la brillance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nouvelle valeur |

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

