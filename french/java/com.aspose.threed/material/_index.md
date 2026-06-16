---
title: "Material"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le matériau définit les paramètres nécessaires à l'apparence visuelle de la géométrie."
type: docs
weight: 98
url: /fr/java/com.aspose.threed/material/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class Material extends A3DObject implements Iterable<TextureSlot>
```

Material définit les paramètres nécessaires à l'apparence visuelle de la géométrie. Aspose.3D fournit un modèle d'éclairage pour [LambertMaterial](../../com.aspose.threed/lambertmaterial), [PhongMaterial](../../com.aspose.threed/phongmaterial) et [ShaderMaterial](../../com.aspose.threed/shadermaterial) **Exemple:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     for(var slot : mat)
     {
         System.out.printf("Texture slot %s = %s", slot.getSlotName(), slot.getTexture());
     }
```
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
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Obtient le nom. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Obtient la texture du slot spécifié, cela peut être le nom de la propriété du matériau ou le nom du paramètre du shader |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Obtient l'énumérateur pour parcourir les slots de texture internes. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Définit la texture au slot spécifié |
| [toString()](#toString--) | Formate l'objet en chaîne |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

