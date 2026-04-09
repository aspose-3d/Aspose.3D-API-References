---
title: AnimationNode
second_title: Aspose.3D for Java API Reference
description: Aspose.3Ds supports animation hierarchy each animation can be composed by several animations and animations key-frame definition.
type: docs
weight: 15
url: /el/java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

Aspose.3D's supports animation hierarchy, each animation can be composed by several animations and animation's key-frame definition. [AnimationNode](../../com.aspose.threed/animationnode) defines the transformation of a property value over time, for example, animation node can be used to control a node's transformation or other [A3DObject](../../com.aspose.threed/a3dobject) object's numerical properties.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | Initializes a new instance of the [AnimationNode](../../com.aspose.threed/animationnode) class. |
| [AnimationNode()](#AnimationNode--) | Initializes a new instance of the [AnimationNode](../../com.aspose.threed/animationnode) class. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Δημιουργεί ένα BindPoint βάσει του τύπου δεδομένων της ιδιότητας. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findBindPoint(A3DObject target, String name)](#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Finds the bind point by target and name. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Λαμβάνει το σημείο σύνδεσης της κίνησης στην καθορισμένη ιδιότητα. |
| [getBindPoints()](#getBindPoints--) | Λαμβάνει τα τρέχοντα σημεία σύνδεσης ιδιοτήτων |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Λαμβάνει τη σειρά των καρέ-κλειδιών στην καθορισμένη ιδιότητα. |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | Λαμβάνει τη σειρά keyframe στην δεδομένη ιδιότητα και κανάλι. |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getSubAnimations()](#getSubAnimations--) | Λαμβάνει τους υπο-ανιμασιον κόμβους κάτω από τις τρέχουσες αναπαραστάσεις |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


Initializes a new instance of the [AnimationNode](../../com.aspose.threed/animationnode) class.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


Initializes a new instance of the [AnimationNode](../../com.aspose.threed/animationnode) class.

### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


Δημιουργεί ένα BindPoint βάσει του τύπου δεδομένων της ιδιότητας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | Αντικείμενο. |
| propName | java.lang.String | Όνομα ιδιότητας. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
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
### findBindPoint(A3DObject target, String name) {#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint findBindPoint(A3DObject target, String name)
```


Finds the bind point by target and name.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Στόχος του σημείου σύνδεσης για εύρεση. |
| name | java.lang.String | Όνομα του σημείου σύνδεσης για εύρεση. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
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
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


Λαμβάνει το σημείο σύνδεσης της κίνησης στην καθορισμένη ιδιότητα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Σε ποιο αντικείμενο θα δημιουργηθεί το σημείο σύνδεσης. |
| propName | java.lang.String | Το όνομα της ιδιότητας. |
| Δημιουργία | boolean | Εάν οριστεί σε  true  δημιουργήστε το σημείο σύνδεσης εάν δεν υπάρχει. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


Λαμβάνει τα τρέχοντα σημεία σύνδεσης ιδιοτήτων

**Returns:**
java.util.List<com.aspose.threed.BindPoint> - τα τρέχοντα σημεία σύνδεσης ιδιοτήτων
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


Λαμβάνει τη σειρά των καρέ-κλειδιών στην καθορισμένη ιδιότητα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Σε ποια παρουσία θα δημιουργηθεί η σειρά keyframe. |
| propName | java.lang.String | Το όνομα της ιδιότητας. |
| Δημιουργία | boolean | Εάν οριστεί σε  true , δημιουργήστε τη σειρά εάν δεν υπάρχει. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


Λαμβάνει τη σειρά keyframe στην δεδομένη ιδιότητα και κανάλι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Σε ποια παρουσία θα δημιουργηθεί η σειρά keyframe. |
| propName | java.lang.String | Το όνομα της ιδιότητας. |
| channelName | java.lang.String | Το όνομα του καναλιού. |
| Δημιουργία | boolean | Εάν οριστεί σε  true  δημιουργήστε τη σειρά αναπαράστασης εάν δεν υπάρχει. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


Λαμβάνει τους υπο-ανιμασιον κόμβους κάτω από τις τρέχουσες αναπαραστάσεις

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - οι υπο-ανιμασιον κόμβοι κάτω από τις τρέχουσες αναπαραστάσεις
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

