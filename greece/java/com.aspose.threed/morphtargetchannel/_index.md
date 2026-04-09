---
title: MorphTargetChannel
second_title: Aspose.3D for Java API Reference
description: Ένα MorphTargetChannel χρησιμοποιείται από  για να οργανώσει τις γεωμετρίες-στόχο.
type: docs
weight: 107
url: /el/java/com.aspose.threed/morphtargetchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class MorphTargetChannel extends A3DObject
```

Ένα MorphTargetChannel χρησιμοποιείται από [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) για να οργανώσει τις γεωμετρίες-στόχο. Ορισμένες μορφές αρχείων όπως το FBX υποστηρίζουν πολλαπλά κανάλια παράλληλα. **Remarks:** Το βάρος είναι μεταξύ 0 και 1.0, και το προεπιλεγμένο βάρος για τον στόχο είναι 0.0.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [MorphTargetChannel(String name)](#MorphTargetChannel-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel). |
| [MorphTargetChannel()](#MorphTargetChannel--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [DEFAULT_WEIGHT](#DEFAULT-WEIGHT) | Προεπιλεγμένο βάρος για το μορφολογικό στόχο. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | Λαμβάνει το βάρος για την καθορισμένη γεωμετρία |
| [getChannelWeight()](#getChannelWeight--) | Λαμβάνει το βάρος του παραμορφωτή αυτού του καναλιού. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getTargets()](#getTargets--) | Λαμβάνει όλους τους στόχους που σχετίζονται με το κανάλι. |
| [getWeight(Shape target)](#getWeight-com.aspose.threed.Shape-) | Λαμβάνει το βάρος για τον καθορισμένο στόχο, εάν ο στόχος δεν ανήκει σε αυτό το κανάλι, επιστρέφεται η προεπιλεγμένη τιμή 0. |
| [getWeights()](#getWeights--) | Λαμβάνει τις πλήρεις τιμές βάρους των γεωμετριών στόχου. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | Ορίζει το βάρος για την καθορισμένη γεωμετρία |
| [setChannelWeight(double value)](#setChannelWeight-double-) | Ορίζει το βάρος του παραμορφωτή αυτού του καναλιού. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setWeight(Shape target)](#setWeight-com.aspose.threed.Shape-) | Ορίζει το βάρος για τον καθορισμένο στόχο, η προεπιλεγμένη τιμή είναι 1, το εύρος πρέπει να είναι μεταξύ 0~1 |
| [setWeight(Shape target, double weight)](#setWeight-com.aspose.threed.Shape-double-) | Ορίζει το βάρος για τον καθορισμένο στόχο, η προεπιλεγμένη τιμή είναι 1, το εύρος πρέπει να είναι μεταξύ 0~1 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetChannel(String name) {#MorphTargetChannel-java.lang.String-}
```
public MorphTargetChannel(String name)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα. |

### MorphTargetChannel() {#MorphTargetChannel--}
```
public MorphTargetChannel()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel).

### DEFAULT_WEIGHT {#DEFAULT-WEIGHT}
```
public static final double DEFAULT_WEIGHT
```


Προεπιλεγμένο βάρος για το μορφολογικό στόχο.

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


Λαμβάνει το βάρος για την καθορισμένη γεωμετρία

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Γεωμετρία στόχου. |

**Returns:**
double - Βάρος
### getChannelWeight() {#getChannelWeight--}
```
public double getChannelWeight()
```


Λαμβάνει το βάρος του παραμορφωτή αυτού του καναλιού. Το βάρος είναι μεταξύ 0.0 και 1.0

**Returns:**
double - το βάρος του παραμορφωτή αυτού του καναλιού. Το βάρος είναι μεταξύ 0.0 και 1.0
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
### getTargets() {#getTargets--}
```
public List<Shape> getTargets()
```


Λαμβάνει όλους τους στόχους που σχετίζονται με το κανάλι.

**Returns:**
java.util.List<com.aspose.threed.Shape> - όλοι οι στόχοι που σχετίζονται με το κανάλι.
### getWeight(Shape target) {#getWeight-com.aspose.threed.Shape-}
```
public double getWeight(Shape target)
```


Λαμβάνει το βάρος για τον καθορισμένο στόχο, εάν ο στόχος δεν ανήκει σε αυτό το κανάλι, επιστρέφεται η προεπιλεγμένη τιμή 0.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

**Returns:**
double
### getWeights() {#getWeights--}
```
public List<Double> getWeights()
```


Λαμβάνει τις πλήρεις τιμές βάρους των γεωμετριών στόχου.

**Returns:**
java.util.List<java.lang.Double> - οι πλήρεις τιμές βάρους των γεωμετριών στόχου.
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


Ορίζει το βάρος για την καθορισμένη γεωμετρία

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Γεωμετρία στόχου. |
| τιμή | double | Νέα τιμή |

### setChannelWeight(double value) {#setChannelWeight-double-}
```
public void setChannelWeight(double value)
```


Ορίζει το βάρος του παραμορφωτή αυτού του καναλιού. Το βάρος είναι μεταξύ 0.0 και 1.0

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

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

### setWeight(Shape target) {#setWeight-com.aspose.threed.Shape-}
```
public void setWeight(Shape target)
```


Ορίζει το βάρος για τον καθορισμένο στόχο, η προεπιλεγμένη τιμή είναι 1, το εύρος πρέπει να είναι μεταξύ 0~1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

### setWeight(Shape target, double weight) {#setWeight-com.aspose.threed.Shape-double-}
```
public void setWeight(Shape target, double weight)
```


Ορίζει το βάρος για τον καθορισμένο στόχο, η προεπιλεγμένη τιμή είναι 1, το εύρος πρέπει να είναι μεταξύ 0~1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |
| βάρος | double |  |

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

