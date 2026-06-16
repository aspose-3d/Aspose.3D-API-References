---
title: "ImageRenderOptions"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Options pour  et"
type: docs
weight: 83
url: /fr/java/com.aspose.threed/imagerenderoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class ImageRenderOptions extends A3DObject
```

Options pour [Scene](../../com.aspose.threed/scene) et [Scene](../../com.aspose.threed/scene)
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageRenderOptions()](#ImageRenderOptions--) | Initialiser une instance de [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getAssetDirectories()](#getAssetDirectories--) | Répertoires qui stockent des ressources externes(comme les textures) |
| [getBackgroundColor()](#getBackgroundColor--) | La couleur d'arrière-plan du résultat du rendu. |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | Obtient si les ombres doivent être rendues. |
| [getName()](#getName--) | Obtient le nom. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setAssetDirectories(ArrayList<String> value)](#setAssetDirectories-java.util.ArrayList-java.lang.String--) | Répertoires qui stockent des ressources externes(comme les textures) |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | La couleur d'arrière-plan du résultat du rendu. |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | Définit si les ombres doivent être rendues. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageRenderOptions() {#ImageRenderOptions--}
```
public ImageRenderOptions()
```


Initialiser une instance de [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions)

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
### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


Répertoires qui stockent des ressources externes(comme les textures)

**Returns:**
java.util.ArrayList<java.lang.String> - Répertoires qui stockent des ressources externes(comme les textures)
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


La couleur d'arrière-plan du résultat du rendu.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The background color of the render result.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableShadows() {#getEnableShadows--}
```
public boolean getEnableShadows()
```


Obtient si les ombres doivent être rendues.

**Returns:**
boolean - si les ombres doivent être rendues.
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
### setAssetDirectories(ArrayList<String> value) {#setAssetDirectories-java.util.ArrayList-java.lang.String--}
```
public void setAssetDirectories(ArrayList<String> value)
```


Répertoires qui stockent des ressources externes(comme les textures)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.ArrayList<java.lang.String> | Nouvelle valeur |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


La couleur d'arrière-plan du résultat du rendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


Définit si les ombres doivent être rendues.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

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

