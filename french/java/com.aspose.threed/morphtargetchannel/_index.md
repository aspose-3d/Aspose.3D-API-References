---
title: "MorphTargetChannel"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un MorphTargetChannel est utilisé par  pour organiser les géométries cibles."
type: docs
weight: 107
url: /fr/java/com.aspose.threed/morphtargetchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class MorphTargetChannel extends A3DObject
```

Un MorphTargetChannel est utilisé par [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) pour organiser les géométries cibles. Certains formats de fichier comme FBX prennent en charge plusieurs canaux en parallèle. **Remarques :** Le poids est compris entre 0 et 1,0, et le poids par défaut pour la cible est 0,0 ;
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MorphTargetChannel(String name)](#MorphTargetChannel-java.lang.String-) | Initialise une nouvelle instance de la classe [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel). |
| [MorphTargetChannel()](#MorphTargetChannel--) | Initialise une nouvelle instance de la classe [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel). |
## Champs

| Champ | Description |
| --- | --- |
| [DEFAULT_WEIGHT](#DEFAULT-WEIGHT) | Poids par défaut pour la cible de morph. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | Obtient le poids pour la géométrie spécifiée |
| [getChannelWeight()](#getChannelWeight--) | Obtient le poids du déformeur de ce canal. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Obtient le nom. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getTargets()](#getTargets--) | Obtient toutes les cibles associées au canal. |
| [getWeight(Shape target)](#getWeight-com.aspose.threed.Shape-) | Obtient le poids pour la cible spécifiée, si la cible n'appartient pas à ce canal, la valeur par défaut 0 est renvoyée. |
| [getWeights()](#getWeights--) | Obtient les valeurs complètes de poids des géométries cibles. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | Définit le poids pour la géométrie spécifiée |
| [setChannelWeight(double value)](#setChannelWeight-double-) | Définit le poids du déformeur de ce canal. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setWeight(Shape target)](#setWeight-com.aspose.threed.Shape-) | Définit le poids pour la cible spécifiée, la valeur par défaut est 1, la plage doit être entre 0~1 |
| [setWeight(Shape target, double weight)](#setWeight-com.aspose.threed.Shape-double-) | Définit le poids pour la cible spécifiée, la valeur par défaut est 1, la plage doit être entre 0~1 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetChannel(String name) {#MorphTargetChannel-java.lang.String-}
```
public MorphTargetChannel(String name)
```


Initialise une nouvelle instance de la classe [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom. |

### MorphTargetChannel() {#MorphTargetChannel--}
```
public MorphTargetChannel()
```


Initialise une nouvelle instance de la classe [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel).

### DEFAULT_WEIGHT {#DEFAULT-WEIGHT}
```
public static final double DEFAULT_WEIGHT
```


Poids par défaut pour la cible de morph.

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


Obtient le poids pour la géométrie spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Géométrie cible. |

**Returns:**
double - Poids
### getChannelWeight() {#getChannelWeight--}
```
public double getChannelWeight()
```


Obtient le poids du déformeur de ce canal. Le poids est compris entre 0,0 et 1,0

**Returns:**
double - le poids du déformeur de ce canal. Le poids est compris entre 0,0 et 1,0
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
### getTargets() {#getTargets--}
```
public List<Shape> getTargets()
```


Obtient toutes les cibles associées au canal.

**Returns:**
java.util.List<com.aspose.threed.Shape> - toutes les cibles associées au canal.
### getWeight(Shape target) {#getWeight-com.aspose.threed.Shape-}
```
public double getWeight(Shape target)
```


Obtient le poids pour la cible spécifiée, si la cible n'appartient pas à ce canal, la valeur par défaut 0 est renvoyée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

**Returns:**
double
### getWeights() {#getWeights--}
```
public List<Double> getWeights()
```


Obtient les valeurs complètes de poids des géométries cibles.

**Returns:**
java.util.List<java.lang.Double> - les valeurs complètes de poids des géométries cibles.
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


Définit le poids pour la géométrie spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Géométrie cible. |
| valeur | double | Nouvelle valeur |

### setChannelWeight(double value) {#setChannelWeight-double-}
```
public void setChannelWeight(double value)
```


Définit le poids du déformeur de ce canal. Le poids est compris entre 0,0 et 1,0

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

### setWeight(Shape target) {#setWeight-com.aspose.threed.Shape-}
```
public void setWeight(Shape target)
```


Définit le poids pour la cible spécifiée, la valeur par défaut est 1, la plage doit être entre 0~1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

### setWeight(Shape target, double weight) {#setWeight-com.aspose.threed.Shape-double-}
```
public void setWeight(Shape target, double weight)
```


Définit le poids pour la cible spécifiée, la valeur par défaut est 1, la plage doit être entre 0~1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |
| poids | double |  |

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

