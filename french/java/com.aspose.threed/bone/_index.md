---
title: "Os"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un os définit le sous-ensemble des points de contrôle de la géométrie et le poids de mélange défini pour chaque point de contrôle."
type: docs
weight: 20
url: /fr/java/com.aspose.threed/bone/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Bone extends A3DObject
```

Un os définit le sous-ensemble des points de contrôle de la géométrie et le poids de mélange défini pour chaque point de contrôle. L'objet [Bone](../../com.aspose.threed/bone) ne peut pas être utilisé directement, une instance de [SkinDeformer](../../com.aspose.threed/skindeformer) est utilisée pour déformer la géométrie, et [SkinDeformer](../../com.aspose.threed/skindeformer) est fourni avec un ensemble d'os, chaque os étant lié à un nœud. NOTE : Un point de contrôle d'une géométrie peut être lié à plusieurs os.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Bone(String name)](#Bone-java.lang.String-) | Initialise une nouvelle instance de la classe [Bone](../../com.aspose.threed/bone). |
| [Bone()](#Bone--) | Initialise une nouvelle instance de la classe [Bone](../../com.aspose.threed/bone). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [get(int index)](#get-int-) | Obtient le poids de mélange du point de contrôle spécifié |
| [getBoneTransform()](#getBoneTransform--) | Obtient la matrice de transformation de l'os. |
| [getClass()](#getClass--) |  |
| [getLinkMode()](#getLinkMode--) | Le mode de liaison d'un os fait référence à la manière dont un os est connecté ou lié à son os parent au sein d'une structure hiérarchique. |
| [getName()](#getName--) | Obtient le nom. |
| [getNode()](#getNode--) | Obtient le nœud. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getTransform()](#getTransform--) | Obtient la matrice de transformation du nœud contenant l'os. |
| [getWeight(int index)](#getWeight-int-) | Obtient le poids du point de contrôle spécifié par l'index |
| [getWeightCount()](#getWeightCount--) | Obtient le nombre de poids, celui-ci est automatiquement étendu par [setWeight](../../com.aspose.threed/bone\#setWeight) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [set(int index, double value)](#set-int-double-) | Définit le poids de mélange du point de contrôle spécifié |
| [setBoneTransform(Matrix4 value)](#setBoneTransform-com.aspose.threed.Matrix4-) | Définit la matrice de transformation de l'os. |
| [setLinkMode(BoneLinkMode value)](#setLinkMode-com.aspose.threed.BoneLinkMode-) | Le mode de liaison d'un os fait référence à la manière dont un os est connecté ou lié à son os parent au sein d'une structure hiérarchique. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Définit le nœud. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setTransform(Matrix4 value)](#setTransform-com.aspose.threed.Matrix4-) | Définit la matrice de transformation du nœud contenant l'os. |
| [setWeight(int index, double weight)](#setWeight-int-double-) | Définit le poids du point de contrôle spécifié par l'index |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bone(String name) {#Bone-java.lang.String-}
```
public Bone(String name)
```


Initialise une nouvelle instance de la classe [Bone](../../com.aspose.threed/bone).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom. |

### Bone() {#Bone--}
```
public Bone()
```


Initialise une nouvelle instance de la classe [Bone](../../com.aspose.threed/bone).

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
### get(int index) {#get-int-}
```
public double get(int index)
```


Obtient le poids de mélange du point de contrôle spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int | Index du poids |

**Returns:**
double - Le poids
### getBoneTransform() {#getBoneTransform--}
```
public Matrix4 getBoneTransform()
```


Obtient la matrice de transformation de l'os.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the bone.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLinkMode() {#getLinkMode--}
```
public BoneLinkMode getLinkMode()
```


Le mode de liaison d'un os fait référence à la manière dont un os est connecté ou lié à son os parent au sein d'une structure hiérarchique.

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode) - A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure.
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getNode() {#getNode--}
```
public Node getNode()
```


Obtient le nœud. Le nœud osseux est l'os auquel la peau est attachée, le [SkinDeformer](../../com.aspose.threed/skindeformer) utilisera le nœud osseux pour influencer le déplacement des points de contrôle. Le nœud osseux possède généralement un [Skeleton](../../com.aspose.threed/skeleton) attaché, mais ce n'est pas obligatoire. Le [Skeleton](../../com.aspose.threed/skeleton) attaché est généralement utilisé par les logiciels DCC pour afficher le squelette à l'utilisateur.

**Returns:**
[Node](../../com.aspose.threed/node) - the node. The bone node is the bone which skin attached to, the [SkinDeformer](../../com.aspose.threed/skindeformer) will use bone node to influence the displacement of the control points. Bone node usually has a [Skeleton](../../com.aspose.threed/skeleton) attached, but it's not required. Attached [Skeleton](../../com.aspose.threed/skeleton) is usually used by DCC software to show skeleton to user.
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
### getTransform() {#getTransform--}
```
public Matrix4 getTransform()
```


Obtient la matrice de transformation du nœud contenant l'os.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node containing the bone.
### getWeight(int index) {#getWeight-int-}
```
public double getWeight(int index)
```


Obtient le poids du point de contrôle spécifié par l'index

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int | Index du point de contrôle |

**Returns:**
double - le poids à l'index spécifié, ou 0 si l'index est invalide
### getWeightCount() {#getWeightCount--}
```
public int getWeightCount()
```


Obtient le nombre de poids, celui-ci est automatiquement étendu par [setWeight](../../com.aspose.threed/bone\#setWeight)

**Returns:**
int - le nombre de poids, celui-ci est automatiquement étendu par [setWeight](../../com.aspose.threed/bone\#setWeight)
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
### set(int index, double value) {#set-int-double-}
```
public void set(int index, double value)
```


Définit le poids de mélange du point de contrôle spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int | Index du poids |
| valeur | double | Nouvelle valeur |

### setBoneTransform(Matrix4 value) {#setBoneTransform-com.aspose.threed.Matrix4-}
```
public void setBoneTransform(Matrix4 value)
```


Définit la matrice de transformation de l'os.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nouvelle valeur |

### setLinkMode(BoneLinkMode value) {#setLinkMode-com.aspose.threed.BoneLinkMode-}
```
public void setLinkMode(BoneLinkMode value)
```


Le mode de liaison d'un os fait référence à la manière dont un os est connecté ou lié à son os parent au sein d'une structure hiérarchique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BoneLinkMode](../../com.aspose.threed/bonelinkmode) | Nouvelle valeur |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Définit le nœud. Le nœud osseux est l'os auquel la peau est attachée, le [SkinDeformer](../../com.aspose.threed/skindeformer) utilisera le nœud osseux pour influencer le déplacement des points de contrôle. Le nœud osseux possède généralement un [Skeleton](../../com.aspose.threed/skeleton) attaché, mais ce n'est pas obligatoire. Le [Skeleton](../../com.aspose.threed/skeleton) attaché est généralement utilisé par les logiciels DCC pour afficher le squelette à l'utilisateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nouvelle valeur |

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

### setTransform(Matrix4 value) {#setTransform-com.aspose.threed.Matrix4-}
```
public void setTransform(Matrix4 value)
```


Définit la matrice de transformation du nœud contenant l'os.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nouvelle valeur |

### setWeight(int index, double weight) {#setWeight-int-double-}
```
public void setWeight(int index, double weight)
```


Définit le poids du point de contrôle spécifié par l'index

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int | Index du point de contrôle |
| poids | double | Nouveau poids |

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

