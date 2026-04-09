---
title: Οστό
second_title: Aspose.3D for Java API Reference
description: Ένα οστό ορίζει το υποσύνολο των σημείων ελέγχου της γεωμετρίας και καθορίζει το βάρος ανάμειξης για κάθε σημείο ελέγχου.
type: docs
weight: 20
url: /el/java/com.aspose.threed/bone/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Bone extends A3DObject
```

Ένα οστό ορίζει το υποσύνολο των σημείων ελέγχου της γεωμετρίας και καθορίζει το βάρος ανάμειξης για κάθε σημείο ελέγχου. Το αντικείμενο [Bone](../../com.aspose.threed/bone) δεν μπορεί να χρησιμοποιηθεί άμεσα, μια παρουσία [SkinDeformer](../../com.aspose.threed/skindeformer) χρησιμοποιείται για την παραμόρφωση της γεωμετρίας, και το [SkinDeformer](../../com.aspose.threed/skindeformer) περιλαμβάνει ένα σύνολο οστών, κάθε οστό συνδεδεμένο με έναν κόμβο. ΣΗΜΕΙΩΣΗ: Ένα σημείο ελέγχου μιας γεωμετρίας μπορεί να δεσμευτεί σε περισσότερα από ένα οστά.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Bone(String name)](#Bone-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Bone](../../com.aspose.threed/bone). |
| [Bone()](#Bone--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Bone](../../com.aspose.threed/bone). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [get(int index)](#get-int-) | Λαμβάνει το βάρος ανάμειξης του καθορισμένου σημείου ελέγχου |
| [getBoneTransform()](#getBoneTransform--) | Λαμβάνει τον πίνακα μετασχηματισμού του οστού. |
| [getClass()](#getClass--) |  |
| [getLinkMode()](#getLinkMode--) | Η λειτουργία σύνδεσης ενός οστού αναφέρεται στον τρόπο με τον οποίο ένα οστό συνδέεται ή συνδέεται με το γονικό του οστό μέσα σε μια ιεραρχική δομή. |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getNode()](#getNode--) | Λαμβάνει τον κόμβο. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getTransform()](#getTransform--) | Λαμβάνει τον πίνακα μετασχηματισμού του κόμβου που περιέχει το οστό. |
| [getWeight(int index)](#getWeight-int-) | Λαμβάνει το βάρος για το σημείο ελέγχου που καθορίζεται από το δείκτη |
| [getWeightCount()](#getWeightCount--) | Λαμβάνει τον αριθμό των βαρών, αυτό επεκτείνεται αυτόματα από το [setWeight](../../com.aspose.threed/bone\#setWeight) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [set(int index, double value)](#set-int-double-) | Ορίζει το βάρος ανάμειξης του καθορισμένου σημείου ελέγχου |
| [setBoneTransform(Matrix4 value)](#setBoneTransform-com.aspose.threed.Matrix4-) | Ορίζει τον πίνακα μετασχηματισμού του οστού. |
| [setLinkMode(BoneLinkMode value)](#setLinkMode-com.aspose.threed.BoneLinkMode-) | Η λειτουργία σύνδεσης ενός οστού αναφέρεται στον τρόπο με τον οποίο ένα οστό συνδέεται ή συνδέεται με το γονικό του οστό μέσα σε μια ιεραρχική δομή. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Ορίζει τον κόμβο. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setTransform(Matrix4 value)](#setTransform-com.aspose.threed.Matrix4-) | Ορίζει τον πίνακα μετασχηματισμού του κόμβου που περιέχει το οστό. |
| [setWeight(int index, double weight)](#setWeight-int-double-) | Ορίζει το βάρος για το σημείο ελέγχου που καθορίζεται από το δείκτη |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bone(String name) {#Bone-java.lang.String-}
```
public Bone(String name)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Bone](../../com.aspose.threed/bone).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα. |

### Bone() {#Bone--}
```
public Bone()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Bone](../../com.aspose.threed/bone).

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
### get(int index) {#get-int-}
```
public double get(int index)
```


Λαμβάνει το βάρος ανάμειξης του καθορισμένου σημείου ελέγχου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | Δείκτης του βάρους |

**Returns:**
double - Το βάρος
### getBoneTransform() {#getBoneTransform--}
```
public Matrix4 getBoneTransform()
```


Λαμβάνει τον πίνακα μετασχηματισμού του οστού.

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


Η λειτουργία σύνδεσης ενός οστού αναφέρεται στον τρόπο με τον οποίο ένα οστό συνδέεται ή συνδέεται με το γονικό του οστό μέσα σε μια ιεραρχική δομή.

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode) - A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure.
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getNode() {#getNode--}
```
public Node getNode()
```


Λαμβάνει τον κόμβο. Ο κόμβος οστού είναι το οστό στο οποίο προσδένεται το δέρμα, το [SkinDeformer](../../com.aspose.threed/skindeformer) θα χρησιμοποιήσει τον κόμβο οστού για να επηρεάσει τη μετατόπιση των σημείων ελέγχου. Συνήθως ο κόμβος οστού έχει ένα [Skeleton](../../com.aspose.threed/skeleton) συνδεδεμένο, αλλά δεν είναι απαραίτητο. Το συνδεδεμένο [Skeleton](../../com.aspose.threed/skeleton) χρησιμοποιείται συνήθως από λογισμικό DCC για να εμφανίσει το σκελετό στον χρήστη.

**Returns:**
[Node](../../com.aspose.threed/node) - the node. The bone node is the bone which skin attached to, the [SkinDeformer](../../com.aspose.threed/skindeformer) will use bone node to influence the displacement of the control points. Bone node usually has a [Skeleton](../../com.aspose.threed/skeleton) attached, but it's not required. Attached [Skeleton](../../com.aspose.threed/skeleton) is usually used by DCC software to show skeleton to user.
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
### getTransform() {#getTransform--}
```
public Matrix4 getTransform()
```


Λαμβάνει τον πίνακα μετασχηματισμού του κόμβου που περιέχει το οστό.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node containing the bone.
### getWeight(int index) {#getWeight-int-}
```
public double getWeight(int index)
```


Λαμβάνει το βάρος για το σημείο ελέγχου που καθορίζεται από το δείκτη

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | Δείκτης σημείου ελέγχου |

**Returns:**
double - το βάρος στον καθορισμένο δείκτη, ή 0 αν ο δείκτης είναι άκυρος
### getWeightCount() {#getWeightCount--}
```
public int getWeightCount()
```


Λαμβάνει τον αριθμό των βαρών, αυτό επεκτείνεται αυτόματα από το [setWeight](../../com.aspose.threed/bone\#setWeight)

**Returns:**
int - ο αριθμός των βαρών, αυτό επεκτείνεται αυτόματα από το [setWeight](../../com.aspose.threed/bone\#setWeight)
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
### set(int index, double value) {#set-int-double-}
```
public void set(int index, double value)
```


Ορίζει το βάρος ανάμειξης του καθορισμένου σημείου ελέγχου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | Δείκτης του βάρους |
| τιμή | double | Νέα τιμή |

### setBoneTransform(Matrix4 value) {#setBoneTransform-com.aspose.threed.Matrix4-}
```
public void setBoneTransform(Matrix4 value)
```


Ορίζει τον πίνακα μετασχηματισμού του οστού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Νέα τιμή |

### setLinkMode(BoneLinkMode value) {#setLinkMode-com.aspose.threed.BoneLinkMode-}
```
public void setLinkMode(BoneLinkMode value)
```


Η λειτουργία σύνδεσης ενός οστού αναφέρεται στον τρόπο με τον οποίο ένα οστό συνδέεται ή συνδέεται με το γονικό του οστό μέσα σε μια ιεραρχική δομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoneLinkMode](../../com.aspose.threed/bonelinkmode) | Νέα τιμή |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ορίζει το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Ορίζει τον κόμβο. Ο κόμβος οστού είναι το οστό στο οποίο προσδένεται το δέρμα, το [SkinDeformer](../../com.aspose.threed/skindeformer) θα χρησιμοποιήσει τον κόμβο οστού για να επηρεάσει τη μετατόπιση των σημείων ελέγχου. Συνήθως ο κόμβος οστού έχει ένα [Skeleton](../../com.aspose.threed/skeleton) συνδεδεμένο, αλλά δεν είναι απαραίτητο. Το συνδεδεμένο [Skeleton](../../com.aspose.threed/skeleton) χρησιμοποιείται συνήθως από λογισμικό DCC για να εμφανίσει το σκελετό στον χρήστη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Νέα τιμή |

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

### setTransform(Matrix4 value) {#setTransform-com.aspose.threed.Matrix4-}
```
public void setTransform(Matrix4 value)
```


Ορίζει τον πίνακα μετασχηματισμού του κόμβου που περιέχει το οστό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Νέα τιμή |

### setWeight(int index, double weight) {#setWeight-int-double-}
```
public void setWeight(int index, double weight)
```


Ορίζει το βάρος για το σημείο ελέγχου που καθορίζεται από το δείκτη

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | Δείκτης σημείου ελέγχου |
| βάρος | double | Νέο βάρος |

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

