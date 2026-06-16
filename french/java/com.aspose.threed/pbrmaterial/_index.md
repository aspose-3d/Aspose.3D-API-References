---
title: "PbrMaterial"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Matériau pour le rendu physiquement basé sur la couleur d'albédo/métallique/rugosité"
type: docs
weight: 121
url: /fr/java/com.aspose.threed/pbrmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrMaterial extends Material
```

Matériau pour le rendu physiquement basé sur la couleur d'albédo/métallique/rugosité
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PbrMaterial()](#PbrMaterial--) | Construire une instance de matériau PBR par défaut |
| [PbrMaterial(Vector3 albedo)](#PbrMaterial-com.aspose.threed.Vector3-) | Construire un matériau PBR par défaut avec la valeur de couleur d'albédo spécifiée. |
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
| [fromMaterial(Material material)](#fromMaterial-com.aspose.threed.Material-) | Autoriser la conversion d'autres matériaux en PbrMaterial **Example:** |
| [getAlbedo()](#getAlbedo--) | Obtient la couleur de base du matériau |
| [getAlbedoTexture()](#getAlbedoTexture--) | Obtient la texture pour l'albédo |
| [getClass()](#getClass--) |  |
| [getEmissiveColor()](#getEmissiveColor--) | Obtient la couleur émissive |
| [getEmissiveTexture()](#getEmissiveTexture--) | Obtient la texture pour l'émissif |
| [getMetallicFactor()](#getMetallicFactor--) | Obtient la métallité du matériau, une valeur de 1 signifie que le matériau est un métal et une valeur de 0 signifie que le matériau est un diélectrique. |
| [getMetallicRoughness()](#getMetallicRoughness--) | Obtient la texture pour le métallique (dans le canal R) et la rugosité (dans le canal G) |
| [getName()](#getName--) | Obtient le nom. |
| [getNormalTexture()](#getNormalTexture--) | Obtient la texture du mappage normal |
| [getOcclusionFactor()](#getOcclusionFactor--) | Obtient le facteur d'occlusion ambiante |
| [getOcclusionTexture()](#getOcclusionTexture--) | Obtient la texture pour l'occlusion ambiante |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getRoughnessFactor()](#getRoughnessFactor--) | Obtient la rugosité du matériau, une valeur de 1 signifie que le matériau est complètement rugueux et une valeur de 0 signifie que le matériau est complètement lisse |
| [getSpecularTexture()](#getSpecularTexture--) | Obtient la texture pour la couleur spéculaire |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Obtient la texture du slot spécifié, cela peut être le nom de la propriété du matériau ou le nom du paramètre du shader |
| [getTransparency()](#getTransparency--) | Obtient le facteur de transparence. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Obtient l'énumérateur pour parcourir les slots de texture internes. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setAlbedo(Vector3 value)](#setAlbedo-com.aspose.threed.Vector3-) | Définit la couleur de base du matériau |
| [setAlbedoTexture(TextureBase value)](#setAlbedoTexture-com.aspose.threed.TextureBase-) | Définit la texture pour l'albédo |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Définit la couleur émissive |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Définit la texture pour l'émissif |
| [setMetallicFactor(double value)](#setMetallicFactor-double-) | Définit la métallisation du matériau, une valeur de 1 signifie que le matériau est un métal et une valeur de 0 signifie que le matériau est un diélectrique. |
| [setMetallicRoughness(TextureBase value)](#setMetallicRoughness-com.aspose.threed.TextureBase-) | Définit la texture pour le métallique (dans le canal R) et la rugosité (dans le canal G) |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Définit la texture du mappage normal |
| [setOcclusionFactor(double value)](#setOcclusionFactor-double-) | Définit le facteur d'occlusion ambiante |
| [setOcclusionTexture(TextureBase value)](#setOcclusionTexture-com.aspose.threed.TextureBase-) | Définit la texture pour l'occlusion ambiante |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setRoughnessFactor(double value)](#setRoughnessFactor-double-) | Définit la rugosité du matériau, une valeur de 1 signifie que le matériau est complètement rugueux et une valeur de 0 signifie que le matériau est complètement lisse. |
| [setSpecularTexture(TextureBase value)](#setSpecularTexture-com.aspose.threed.TextureBase-) | Définit la texture pour la couleur spéculaire |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Définit la texture au slot spécifié |
| [setTransparency(double value)](#setTransparency-double-) | Définit le facteur de transparence. |
| [toString()](#toString--) | Formate l'objet en chaîne |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrMaterial() {#PbrMaterial--}
```
public PbrMaterial()
```


Construire une instance de matériau PBR par défaut

### PbrMaterial(Vector3 albedo) {#PbrMaterial-com.aspose.threed.Vector3-}
```
public PbrMaterial(Vector3 albedo)
```


Construire un matériau PBR par défaut avec la valeur de couleur d'albédo spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| albedo | [Vector3](../../com.aspose.threed/vector3) | La valeur de couleur d'albédo par défaut |

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
### fromMaterial(Material material) {#fromMaterial-com.aspose.threed.Material-}
```
public static PbrMaterial fromMaterial(Material material)
```


Autoriser la conversion d'autres matériaux en PbrMaterial **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     mat.setDiffuseColor(new Vector3(0.3, 0.9, 0.4));
     PbrMaterial pbr = PbrMaterial.fromMaterial(mat);
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| material | [Material](../../com.aspose.threed/material) |  |

**Returns:**
[PbrMaterial](../../com.aspose.threed/pbrmaterial)
### getAlbedo() {#getAlbedo--}
```
public Vector3 getAlbedo()
```


Obtient la couleur de base du matériau

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the base color of the material
### getAlbedoTexture() {#getAlbedoTexture--}
```
public TextureBase getAlbedoTexture()
```


Obtient la texture pour l'albédo

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


Obtient la couleur émissive

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Obtient la texture pour l'émissif

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getMetallicFactor() {#getMetallicFactor--}
```
public double getMetallicFactor()
```


Obtient la métallité du matériau, une valeur de 1 signifie que le matériau est un métal et une valeur de 0 signifie que le matériau est un diélectrique.

**Returns:**
double - la métallisation du matériau, une valeur de 1 signifie que le matériau est un métal et une valeur de 0 signifie que le matériau est un diélectrique.
### getMetallicRoughness() {#getMetallicRoughness--}
```
public TextureBase getMetallicRoughness()
```


Obtient la texture pour le métallique (dans le canal R) et la rugosité (dans le canal G)

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for metallic(in R channel) and roughness(in G channel)
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
### getOcclusionFactor() {#getOcclusionFactor--}
```
public double getOcclusionFactor()
```


Obtient le facteur d'occlusion ambiante

**Returns:**
double - le facteur d'occlusion ambiante
### getOcclusionTexture() {#getOcclusionTexture--}
```
public TextureBase getOcclusionTexture()
```


Obtient la texture pour l'occlusion ambiante

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for ambient occlusion
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
### getRoughnessFactor() {#getRoughnessFactor--}
```
public double getRoughnessFactor()
```


Obtient la rugosité du matériau, une valeur de 1 signifie que le matériau est complètement rugueux et une valeur de 0 signifie que le matériau est complètement lisse

**Returns:**
double - la rugosité du matériau, une valeur de 1 signifie que le matériau est complètement rugueux et une valeur de 0 signifie que le matériau est complètement lisse.
### getSpecularTexture() {#getSpecularTexture--}
```
public TextureBase getSpecularTexture()
```


Obtient la texture pour la couleur spéculaire

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color
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
### setAlbedo(Vector3 value) {#setAlbedo-com.aspose.threed.Vector3-}
```
public void setAlbedo(Vector3 value)
```


Définit la couleur de base du matériau

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setAlbedoTexture(TextureBase value) {#setAlbedoTexture-com.aspose.threed.TextureBase-}
```
public void setAlbedoTexture(TextureBase value)
```


Définit la texture pour l'albédo

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nouvelle valeur |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Définit la couleur émissive

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

### setMetallicFactor(double value) {#setMetallicFactor-double-}
```
public void setMetallicFactor(double value)
```


Définit la métallisation du matériau, une valeur de 1 signifie que le matériau est un métal et une valeur de 0 signifie que le matériau est un diélectrique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setMetallicRoughness(TextureBase value) {#setMetallicRoughness-com.aspose.threed.TextureBase-}
```
public void setMetallicRoughness(TextureBase value)
```


Définit la texture pour le métallique (dans le canal R) et la rugosité (dans le canal G)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nouvelle valeur |

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

### setOcclusionFactor(double value) {#setOcclusionFactor-double-}
```
public void setOcclusionFactor(double value)
```


Définit le facteur d'occlusion ambiante

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setOcclusionTexture(TextureBase value) {#setOcclusionTexture-com.aspose.threed.TextureBase-}
```
public void setOcclusionTexture(TextureBase value)
```


Définit la texture pour l'occlusion ambiante

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

### setRoughnessFactor(double value) {#setRoughnessFactor-double-}
```
public void setRoughnessFactor(double value)
```


Définit la rugosité du matériau, une valeur de 1 signifie que le matériau est complètement rugueux et une valeur de 0 signifie que le matériau est complètement lisse.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setSpecularTexture(TextureBase value) {#setSpecularTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularTexture(TextureBase value)
```


Définit la texture pour la couleur spéculaire

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

