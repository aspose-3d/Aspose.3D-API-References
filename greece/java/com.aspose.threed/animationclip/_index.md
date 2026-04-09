---
title: AnimationClip
second_title: Aspose.3D for Java API Reference
description: Το κλιπ Animation είναι μια συλλογή από κινήσεις.
type: docs
weight: 14
url: /el/java/com.aspose.threed/animationclip/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class AnimationClip extends SceneObject
```

Το Animation clip είναι μια συλλογή από animation. Η σκηνή μπορεί να έχει ένα ή περισσότερα animation clips.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [AnimationClip()](#AnimationClip--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [AnimationClip](../../com.aspose.threed/animationclip). |
| [AnimationClip(String name)](#AnimationClip-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [AnimationClip](../../com.aspose.threed/animationclip). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createAnimationNode(String nodeName)](#createAnimationNode-java.lang.String-) | Μια συντομευμένη συνάρτηση για τη δημιουργία και καταχώριση του κόμβου animation στο τρέχον clip. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getAnimations()](#getAnimations--) | Αποκτά τα animations που περιέχονται μέσα στο clip. |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Αποκτά την περιγραφή αυτού του animation clip |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getScene()](#getScene--) | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [getStart()](#getStart--) | Αποκτά το χρόνο σε δευτερόλεπτα της έναρξης του clip. |
| [getStop()](#getStop--) | Αποκτά το χρόνο σε δευτερόλεπτα του τέλους του clip. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setDescription(String value)](#setDescription-java.lang.String-) | Ορίζει την περιγραφή αυτού του animation clip |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setStart(double value)](#setStart-double-) | Ορίζει το χρόνο σε δευτερόλεπτα της αρχής του κλιπ. |
| [setStop(double value)](#setStop-double-) | Ορίζει το χρόνο σε δευτερόλεπτα του τέλους του κλιπ. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationClip() {#AnimationClip--}
```
public AnimationClip()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [AnimationClip](../../com.aspose.threed/animationclip).

### AnimationClip(String name) {#AnimationClip-java.lang.String-}
```
public AnimationClip(String name)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [AnimationClip](../../com.aspose.threed/animationclip).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα |

### createAnimationNode(String nodeName) {#createAnimationNode-java.lang.String-}
```
public AnimationNode createAnimationNode(String nodeName)
```


Μια συντομευμένη συνάρτηση για τη δημιουργία και καταχώριση του κόμβου animation στο τρέχον clip.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeName | java.lang.String | Όνομα νέου κόμβου κίνησης |

**Returns:**
[AnimationNode](../../com.aspose.threed/animationnode) - A new instance of [AnimationNode](../../com.aspose.threed/animationnode) with given name.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Βρίσκει την ιδιότητα. Μπορεί να είναι μια δυναμική ιδιότητα (Δημιουργήθηκε με CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Προσδιορίζεται με το όνομά της)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyName | java.lang.String | Όνομα ιδιότητας. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAnimations() {#getAnimations--}
```
public List<AnimationNode> getAnimations()
```


Αποκτά τα animations που περιέχονται μέσα στο clip.

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - οι κινήσεις που περιέχονται μέσα στο κλιπ.
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


Αποκτά την περιγραφή αυτού του animation clip

**Returns:**
java.lang.String - η περιγραφή αυτού του κλιπ κίνησης
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Λαμβάνει τη συλλογή όλων των ιδιοτήτων.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Λάβετε την τιμή της συγκεκριμένης ιδιότητας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Όνομα ιδιότητας |

**Returns:**
java.lang.Object - Η τιμή της ευρεθείσας ιδιότητας
### getScene() {#getScene--}
```
public Scene getScene()
```


Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getStart() {#getStart--}
```
public double getStart()
```


Αποκτά το χρόνο σε δευτερόλεπτα της έναρξης του clip.

**Returns:**
double - ο χρόνος σε δευτερόλεπτα της αρχής του κλιπ.
### getStop() {#getStop--}
```
public double getStop()
```


Αποκτά το χρόνο σε δευτερόλεπτα του τέλους του clip.

**Returns:**
double - ο χρόνος σε δευτερόλεπτα του τέλους του κλιπ.
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


Αφαιρεί μια δυναμική ιδιότητα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Ποια ιδιότητα να αφαιρεθεί |

**Returns:**
boolean - true εάν η ιδιότητα αφαιρεθεί επιτυχώς
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Ποια ιδιότητα να αφαιρεθεί |

**Returns:**
boolean - true εάν η ιδιότητα αφαιρεθεί επιτυχώς
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Ορίζει την περιγραφή αυτού του animation clip

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ορίζει το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Ορίζει την τιμή της συγκεκριμένης ιδιότητας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Όνομα ιδιότητας |
| τιμή | java.lang.Object | Η τιμή της ιδιότητας |

### setStart(double value) {#setStart-double-}
```
public void setStart(double value)
```


Ορίζει το χρόνο σε δευτερόλεπτα της αρχής του κλιπ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setStop(double value) {#setStop-double-}
```
public void setStop(double value)
```


Ορίζει το χρόνο σε δευτερόλεπτα του τέλους του κλιπ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

