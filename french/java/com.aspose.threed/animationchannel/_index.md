---
title: "AnimationChannel"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un canal associe le champ de composant d'une propriété à un ensemble de séquences d'images clés"
type: docs
weight: 13
url: /fr/java/com.aspose.threed/animationchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.KeyframeSequence](../../com.aspose.threed/keyframesequence)
```
public class AnimationChannel extends KeyframeSequence
```

Un canal associe le champ de composant d'une propriété à un ensemble de séquences d'images clés.
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(double time, float value)](#add-double-float-) | Crée une nouvelle image clé avec la valeur spécifiée |
| [add(double time, float value, Interpolation interpolation)](#add-double-float-com.aspose.threed.Interpolation-) | Crée une nouvelle image clé avec la valeur spécifiée |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getBindPoint()](#getBindPoint--) | Obtient le point de liaison de la propriété qui possède cette courbe |
| [getClass()](#getClass--) |  |
| [getComponentType()](#getComponentType--) | Obtient le type du champ de composant |
| [getDefaultValue()](#getDefaultValue--) | Obtient la valeur Default du canal. |
| [getKeyFrames()](#getKeyFrames--) | Obtient les images clés de cette courbe. |
| [getKeyframeSequence()](#getKeyframeSequence--) | Obtient la séquence d'images clés associée dans ce canal |
| [getName()](#getName--) | Obtient le nom. |
| [getPostBehavior()](#getPostBehavior--) | Obtient le comportement postérieur indiquant quelle doit être la valeur échantillonnée après la dernière image clé. |
| [getPreBehavior()](#getPreBehavior--) | Obtient le comportement antérieur indiquant quelle doit être la valeur échantillonnée avant la première image clé. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Obtient l'énumérateur pour parcourir toutes les images clés. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [reset()](#reset--) | Supprime toutes les images clés et réinitialise les comportements post/ pré. |
| [setDefaultValue(Object value)](#setDefaultValue-java.lang.Object-) | Définit la valeur Default du canal. |
| [setKeyframeSequence(KeyframeSequence value)](#setKeyframeSequence-com.aspose.threed.KeyframeSequence-) | Obtient la séquence d'images clés associée dans ce canal |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(double time, float value) {#add-double-float-}
```
public void add(double time, float value)
```


Crée une nouvelle image clé avec la valeur spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| temps | double | Position temporelle (mesurée en secondes) |
| valeur | float | La valeur à cette position temporelle |

### add(double time, float value, Interpolation interpolation) {#add-double-float-com.aspose.threed.Interpolation-}
```
public void add(double time, float value, Interpolation interpolation)
```


Crée une nouvelle image clé avec la valeur spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| temps | double | Position temporelle (mesurée en secondes) |
| valeur | float | La valeur à cette position temporelle |
| interpolation | [Interpolation](../../com.aspose.threed/interpolation) | Le type d'interpolation de cette image clé |

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
### getBindPoint() {#getBindPoint--}
```
public BindPoint getBindPoint()
```


Obtient le point de liaison de la propriété qui possède cette courbe

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - the property bind point which owns this curve
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComponentType() {#getComponentType--}
```
public Class<?> getComponentType()
```


Obtient le type du champ de composant

**Returns:**
java.lang.Class<?> - le type du champ de composant
### getDefaultValue() {#getDefaultValue--}
```
public Object getDefaultValue()
```


Obtient la valeur Default du canal. Si un canal n'a aucune séquence d'images clés connectée, la valeur Default sera utilisée lors de l'évaluation de l'animation. Un scénario réel : l'animation ne modifie que la coordonnée x d'un nœud, les y et z ne sont pas modifiés, alors la valeur Default sera utilisée lors de l'évaluation complète de la translation.

**Returns:**
java.lang.Object - la valeur Default du canal. Si un canal n'a aucune séquence d'images clés connectée, la valeur Default sera utilisée lors de l'évaluation de l'animation. Un scénario réel : l'animation ne modifie que la coordonnée x d'un nœud, les y et z ne sont pas modifiés, alors la valeur Default sera utilisée lors de l'évaluation complète de la translation.
### getKeyFrames() {#getKeyFrames--}
```
public List<KeyFrame> getKeyFrames()
```


Obtient les images clés de cette courbe.

**Returns:**
java.util.List<com.aspose.threed.KeyFrame> - les images clés de cette courbe.
### getKeyframeSequence() {#getKeyframeSequence--}
```
public KeyframeSequence getKeyframeSequence()
```


Obtient la séquence d'images clés associée dans ce canal

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - associated keyframe sequence inside this channel
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getPostBehavior() {#getPostBehavior--}
```
public Extrapolation getPostBehavior()
```


Obtient le comportement postérieur indiquant quelle doit être la valeur échantillonnée après la dernière image clé.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the post behavior indicates what the sampled value should be after the last key frame.
### getPreBehavior() {#getPreBehavior--}
```
public Extrapolation getPreBehavior()
```


Obtient le comportement antérieur indiquant quelle doit être la valeur échantillonnée avant la première image clé.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the pre behavior indicates what the sampled value should be before the first key.
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
### iterator() {#iterator--}
```
public Iterator<KeyFrame> iterator()
```


Obtient l'énumérateur pour parcourir toutes les images clés.

**Returns:**
java.util.Iterator<com.aspose.threed.KeyFrame>
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
### reset() {#reset--}
```
public void reset()
```


Supprime toutes les images clés et réinitialise les comportements post/ pré.

### setDefaultValue(Object value) {#setDefaultValue-java.lang.Object-}
```
public void setDefaultValue(Object value)
```


Définit la valeur Default du canal. Si un canal n'a aucune séquence d'images clés connectée, la valeur Default sera utilisée lors de l'évaluation de l'animation. Un scénario réel : l'animation ne modifie que la coordonnée x d'un nœud, les y et z ne sont pas modifiés, alors la valeur Default sera utilisée lors de l'évaluation complète de la translation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object | Nouvelle valeur |

### setKeyframeSequence(KeyframeSequence value) {#setKeyframeSequence-com.aspose.threed.KeyframeSequence-}
```
public void setKeyframeSequence(KeyframeSequence value)
```


Obtient la séquence d'images clés associée dans ce canal

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Nouvelle valeur |

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

