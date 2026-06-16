---
title: "AnimationClip"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le clip d'animation est une collection d'animations."
type: docs
weight: 14
url: /fr/java/com.aspose.threed/animationclip/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class AnimationClip extends SceneObject
```

Le clip d'animation est une collection d'animations. La scène peut contenir un ou plusieurs clips d'animation.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AnimationClip()](#AnimationClip--) | Initialise une nouvelle instance de la classe [AnimationClip](../../com.aspose.threed/animationclip). |
| [AnimationClip(String name)](#AnimationClip-java.lang.String-) | Initialise une nouvelle instance de la classe [AnimationClip](../../com.aspose.threed/animationclip). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createAnimationNode(String nodeName)](#createAnimationNode-java.lang.String-) | Une fonction raccourcie pour créer et enregistrer le nœud d'animation sur le clip actuel. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getAnimations()](#getAnimations--) | Obtient les animations contenues dans le clip. |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Obtient la description de ce clip d'animation |
| [getName()](#getName--) | Obtient le nom. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [getStart()](#getStart--) | Obtient le temps en secondes du début du clip. |
| [getStop()](#getStop--) | Obtient le temps en secondes de la fin du clip. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setDescription(String value)](#setDescription-java.lang.String-) | Définit la description de ce clip d'animation |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setStart(double value)](#setStart-double-) | Définit le temps en secondes du début du clip. |
| [setStop(double value)](#setStop-double-) | Définit le temps en secondes de la fin du clip. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationClip() {#AnimationClip--}
```
public AnimationClip()
```


Initialise une nouvelle instance de la classe [AnimationClip](../../com.aspose.threed/animationclip).

### AnimationClip(String name) {#AnimationClip-java.lang.String-}
```
public AnimationClip(String name)
```


Initialise une nouvelle instance de la classe [AnimationClip](../../com.aspose.threed/animationclip).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom |

### createAnimationNode(String nodeName) {#createAnimationNode-java.lang.String-}
```
public AnimationNode createAnimationNode(String nodeName)
```


Une fonction raccourcie pour créer et enregistrer le nœud d'animation sur le clip actuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nodeName | java.lang.String | Nom du nouveau nœud d'animation |

**Returns:**
[AnimationNode](../../com.aspose.threed/animationnode) - A new instance of [AnimationNode](../../com.aspose.threed/animationnode) with given name.
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
### getAnimations() {#getAnimations--}
```
public List<AnimationNode> getAnimations()
```


Obtient les animations contenues dans le clip.

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - les animations contenues dans le clip.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public String getDescription()
```


Obtient la description de ce clip d'animation

**Returns:**
java.lang.String - la description de ce clip d'animation
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtient la scène à laquelle cet objet appartient

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getStart() {#getStart--}
```
public double getStart()
```


Obtient le temps en secondes du début du clip.

**Returns:**
double - le temps en secondes du début du clip.
### getStop() {#getStop--}
```
public double getStop()
```


Obtient le temps en secondes de la fin du clip.

**Returns:**
double - le temps en secondes de la fin du clip.
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
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Définit la description de ce clip d'animation

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

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

### setStart(double value) {#setStart-double-}
```
public void setStart(double value)
```


Définit le temps en secondes du début du clip.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setStop(double value) {#setStop-double-}
```
public void setStop(double value)
```


Définit le temps en secondes de la fin du clip.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

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

