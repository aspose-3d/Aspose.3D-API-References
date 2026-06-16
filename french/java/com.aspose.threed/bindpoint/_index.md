---
title: "BindPoint"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un  est généralement créé sur la propriété d'un objet ; certains types de propriétés contiennent plusieurs champs composant (comme un champ Vector3) qui généreront un canal pour chaque champ composant et connecteront le champ à une ou plusieurs instances de séquence d'images clés via les canaux."
type: docs
weight: 19
url: /fr/java/com.aspose.threed/bindpoint/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class BindPoint extends A3DObject
```

Un [BindPoint](../../com.aspose.threed/bindpoint) est généralement créé sur la propriété d'un objet, certains types de propriétés contiennent plusieurs champs composant (comme un champ Vector3), [BindPoint](../../com.aspose.threed/bindpoint) générera un canal pour chaque champ composant et connectera le champ à une ou plusieurs instance(s) de séquence d'images clés via les canaux.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BindPoint(Scene scene, Property prop)](#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-) | Initialise une nouvelle instance de la classe [BindPoint](../../com.aspose.threed/bindpoint). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addChannel(String name, Class<?> type, Object value)](#addChannel-java.lang.String-java.lang.Class----java.lang.Object-) | Ajoute la propriété de canal spécifiée. |
| [addChannel(String name, Object value)](#addChannel-java.lang.String-java.lang.Object-) | Ajoute la propriété de canal spécifiée. |
| [bindKeyframeSequence(String channelName, KeyframeSequence sequence)](#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-) | Lier la séquence d'images clés au canal spécifié |
| [createKeyframeSequence(String name)](#createKeyframeSequence-java.lang.String-) | Crée une nouvelle courbe et la connecte au premier canal du mappage de courbe |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [get(String channelName)](#get-java.lang.String-) | Obtient le canal par le nom donné |
| [getChannel(String channelName)](#getChannel-java.lang.String-) | Obtient le canal par le nom donné |
| [getChannelsCount()](#getChannelsCount--) | Obtient le nombre total de canaux de propriétés définis dans ce mappage de courbe d'animation. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(String channelName)](#getKeyframeSequence-java.lang.String-) | Obtient la première séquence d'images clés dans le canal spécifié |
| [getName()](#getName--) | Obtient le nom. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty()](#getProperty--) | Obtient la propriété associée au CurveMapping |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [resetChannels()](#resetChannels--) | Vide les canaux de propriétés de ce mappage de courbe d'animation. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setProperty(Property value)](#setProperty-com.aspose.threed.Property-) | Obtient la propriété associée au CurveMapping |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [toString()](#toString--) | Formate l'objet en chaîne |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BindPoint(Scene scene, Property prop) {#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-}
```
public BindPoint(Scene scene, Property prop)
```


Initialise une nouvelle instance de la classe [BindPoint](../../com.aspose.threed/bindpoint).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | La scène qui contient l'animation. |
| prop | [Property](../../com.aspose.threed/property) | Propriété. |

### addChannel(String name, Class<?> type, Object value) {#addChannel-java.lang.String-java.lang.Class----java.lang.Object-}
```
public boolean addChannel(String name, Class<?> type, Object value)
```


Ajoute la propriété de canal spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom. |
| type | java.lang.Class<?> | Type. |
| valeur | java.lang.Object | Valeur. |

**Returns:**
booléen - true, si le canal a été ajouté, false sinon.
### addChannel(String name, Object value) {#addChannel-java.lang.String-java.lang.Object-}
```
public boolean addChannel(String name, Object value)
```


Ajoute la propriété de canal spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom. |
| valeur | java.lang.Object | Valeur. |

**Returns:**
booléen - true, si le canal a été ajouté, false sinon.
### bindKeyframeSequence(String channelName, KeyframeSequence sequence) {#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-}
```
public void bindKeyframeSequence(String channelName, KeyframeSequence sequence)
```


Lier la séquence d'images clés au canal spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| channelName | java.lang.String | Quel canal la séquence d'images clés sera liée à |
| sequence | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | La séquence d'images clés à lier |

### createKeyframeSequence(String name) {#createKeyframeSequence-java.lang.String-}
```
public KeyframeSequence createKeyframeSequence(String name)
```


Crée une nouvelle courbe et la connecte au premier canal du mappage de courbe

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom de la nouvelle séquence. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### get(String channelName) {#get-java.lang.String-}
```
public AnimationChannel get(String channelName)
```


Obtient le canal par le nom donné

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| channelName | java.lang.String | Nom du canal |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Animation channel
### getChannel(String channelName) {#getChannel-java.lang.String-}
```
public AnimationChannel getChannel(String channelName)
```


Obtient le canal par le nom donné

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| channelName | java.lang.String | Le nom du canal à rechercher |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Channel with the name
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Obtient le nombre total de canaux de propriétés définis dans ce mappage de courbe d'animation.

**Returns:**
int - Le nombre de canaux.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(String channelName) {#getKeyframeSequence-java.lang.String-}
```
public KeyframeSequence getKeyframeSequence(String channelName)
```


Obtient la première séquence d'images clés dans le canal spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| channelName | java.lang.String | Le nom du canal à rechercher |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - First keyframe sequence with the channel name
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
### getProperty() {#getProperty--}
```
public Property getProperty()
```


Obtient la propriété associée au CurveMapping

**Returns:**
[Property](../../com.aspose.threed/property) - the property associated with the CurveMapping
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
### resetChannels() {#resetChannels--}
```
public void resetChannels()
```


Vide les canaux de propriétés de ce mappage de courbe d'animation.

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setProperty(Property value) {#setProperty-com.aspose.threed.Property-}
```
public void setProperty(Property value)
```


Obtient la propriété associée au CurveMapping

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Property](../../com.aspose.threed/property) | Nouvelle valeur |

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

