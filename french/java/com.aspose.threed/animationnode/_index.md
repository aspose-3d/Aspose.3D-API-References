---
title: "AnimationNode"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Aspose.3Ds prend en charge la hiérarchie d'animation, chaque animation pouvant être composée de plusieurs animations et de la définition des images clés d'animation."
type: docs
weight: 15
url: /fr/java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

Aspose.3D prend en charge la hiérarchie d'animation, chaque animation pouvant être composée de plusieurs animations et de la définition des images clés d'animation. [AnimationNode](../../com.aspose.threed/animationnode) définit la transformation d'une valeur de propriété au fil du temps, par exemple, le nœud d'animation peut être utilisé pour contrôler la transformation d'un nœud ou d'autres propriétés numériques d'un objet [A3DObject](../../com.aspose.threed/a3dobject).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | Initialise une nouvelle instance de la classe [AnimationNode](../../com.aspose.threed/animationnode). |
| [AnimationNode()](#AnimationNode--) | Initialise une nouvelle instance de la classe [AnimationNode](../../com.aspose.threed/animationnode). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Crée un BindPoint basé sur le type de données de la propriété. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findBindPoint(A3DObject target, String name)](#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Trouve le point de liaison par cible et nom. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Obtient le point de liaison d'animation sur la propriété donnée. |
| [getBindPoints()](#getBindPoints--) | Obtient les points de liaison de propriété actuels |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Obtient la séquence d'images clés sur la propriété donnée. |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | Obtient la séquence d'images clés sur la propriété et le canal donnés. |
| [getName()](#getName--) | Obtient le nom. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getSubAnimations()](#getSubAnimations--) | Obtient les nœuds de sous-animation sous les animations actuelles |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


Initialise une nouvelle instance de la classe [AnimationNode](../../com.aspose.threed/animationnode).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


Initialise une nouvelle instance de la classe [AnimationNode](../../com.aspose.threed/animationnode).

### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


Crée un BindPoint basé sur le type de données de la propriété.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | Objet. |
| propName | java.lang.String | Nom de la propriété. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
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
### findBindPoint(A3DObject target, String name) {#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint findBindPoint(A3DObject target, String name)
```


Trouve le point de liaison par cible et nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Cible du point de liaison à rechercher. |
| nom | java.lang.String | Nom du point de liaison à rechercher. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
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
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


Obtient le point de liaison d'animation sur la propriété donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Sur quel objet créer le point de liaison. |
| propName | java.lang.String | Le nom de la propriété. |
| créer | boolean | Si défini sur  true  créer le point de liaison s'il n'existe pas. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


Obtient les points de liaison de propriété actuels

**Returns:**
java.util.List<com.aspose.threed.BindPoint> - les points de liaison de la propriété actuelle
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(A3DObject target, String propName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, boolean create)
```


Obtient la séquence d'images clés sur la propriété donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Sur quelle instance créer la séquence d'images clés. |
| propName | java.lang.String | Le nom de la propriété. |
| créer | boolean | Si défini sur  true , créer la séquence si elle n'existe pas. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


Obtient la séquence d'images clés sur la propriété et le canal donnés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Sur quelle instance créer la séquence d'images clés. |
| propName | java.lang.String | Le nom de la propriété. |
| channelName | java.lang.String | Le nom du canal. |
| créer | boolean | Si défini sur  true  créer la séquence d'animation si elle n'existe pas. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


Obtient les nœuds de sous-animation sous les animations actuelles

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - les nœuds de sous-animation sous les animations actuelles
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

