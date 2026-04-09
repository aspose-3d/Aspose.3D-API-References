---
title: BindPoint
second_title: Aspose.3D for Java API Reference
description: Ένα  δημιουργείται συνήθως σε μια ιδιότητα αντικειμένου· ορισμένοι τύποι ιδιοτήτων περιέχουν πολλαπλά πεδία συστατικών (όπως ένα πεδίο Vector3)· θα δημιουργήσει κανάλι για κάθε πεδίο συστατικού και συνδέει το πεδίο με μία ή περισσότερες εμφανίσεις ακολουθίας κλειδιών μέσω των καναλιών.
type: docs
weight: 19
url: /el/java/com.aspose.threed/bindpoint/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class BindPoint extends A3DObject
```

Ένα [BindPoint](../../com.aspose.threed/bindpoint) δημιουργείται συνήθως σε μια ιδιότητα αντικειμένου· ορισμένοι τύποι ιδιοτήτων περιέχουν πολλαπλά πεδία συστατικών (όπως ένα πεδίο Vector3), το [BindPoint](../../com.aspose.threed/bindpoint) θα δημιουργήσει κανάλι για κάθε πεδίο συστατικού και θα συνδέσει το πεδίο με μία ή περισσότερες εμφανίσεις ακολουθίας κλειδιών μέσω των καναλιών.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [BindPoint(Scene scene, Property prop)](#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [BindPoint](../../com.aspose.threed/bindpoint). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addChannel(String name, Class<?> type, Object value)](#addChannel-java.lang.String-java.lang.Class----java.lang.Object-) | Προσθέτει την καθορισμένη ιδιότητα καναλιού. |
| [addChannel(String name, Object value)](#addChannel-java.lang.String-java.lang.Object-) | Προσθέτει την καθορισμένη ιδιότητα καναλιού. |
| [bindKeyframeSequence(String channelName, KeyframeSequence sequence)](#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-) | Συνδέστε την ακολουθία κλειδιών στο καθορισμένο κανάλι |
| [createKeyframeSequence(String name)](#createKeyframeSequence-java.lang.String-) | Δημιουργεί μια νέα καμπύλη και τη συνδέει με το πρώτο κανάλι της αντιστοίχισης καμπύλης |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [get(String channelName)](#get-java.lang.String-) | Λαμβάνει το κανάλι με το δεδομένο όνομα |
| [getChannel(String channelName)](#getChannel-java.lang.String-) | Λαμβάνει το κανάλι με το δεδομένο όνομα |
| [getChannelsCount()](#getChannelsCount--) | Λαμβάνει τον συνολικό αριθμό των καναλιών ιδιοτήτων που ορίζονται σε αυτήν την αντιστοίχηση καμπύλης κίνησης. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(String channelName)](#getKeyframeSequence-java.lang.String-) | Λαμβάνει την πρώτη ακολουθία κλειδιών στο καθορισμένο κανάλι |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty()](#getProperty--) | Λαμβάνει την ιδιότητα που σχετίζεται με το CurveMapping |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [resetChannels()](#resetChannels--) | Αδειάζει τα κανάλια ιδιοτήτων αυτής της αντιστοίχισης καμπύλης κίνησης. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setProperty(Property value)](#setProperty-com.aspose.threed.Property-) | Λαμβάνει την ιδιότητα που σχετίζεται με το CurveMapping |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [toString()](#toString--) | Μετατρέπει το αντικείμενο σε συμβολοσειρά |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BindPoint(Scene scene, Property prop) {#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-}
```
public BindPoint(Scene scene, Property prop)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [BindPoint](../../com.aspose.threed/bindpoint).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Η σκηνή που περιέχει την κίνηση. |
| prop | [Property](../../com.aspose.threed/property) | Ιδιότητα. |

### addChannel(String name, Class<?> type, Object value) {#addChannel-java.lang.String-java.lang.Class----java.lang.Object-}
```
public boolean addChannel(String name, Class<?> type, Object value)
```


Προσθέτει την καθορισμένη ιδιότητα καναλιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα. |
| type | java.lang.Class<?> | Τύπος. |
| τιμή | java.lang.Object | Τιμή. |

**Returns:**
boolean - true, εάν το κανάλι προστέθηκε, false διαφορετικά.
### addChannel(String name, Object value) {#addChannel-java.lang.String-java.lang.Object-}
```
public boolean addChannel(String name, Object value)
```


Προσθέτει την καθορισμένη ιδιότητα καναλιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα. |
| τιμή | java.lang.Object | Τιμή. |

**Returns:**
boolean - true, εάν το κανάλι προστέθηκε, false διαφορετικά.
### bindKeyframeSequence(String channelName, KeyframeSequence sequence) {#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-}
```
public void bindKeyframeSequence(String channelName, KeyframeSequence sequence)
```


Συνδέστε την ακολουθία κλειδιών στο καθορισμένο κανάλι

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelName | java.lang.String | Σε ποιο κανάλι θα συνδεθεί η ακολουθία κλειδιών |
| sequence | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Η ακολουθία κλειδιών προς σύνδεση |

### createKeyframeSequence(String name) {#createKeyframeSequence-java.lang.String-}
```
public KeyframeSequence createKeyframeSequence(String name)
```


Δημιουργεί μια νέα καμπύλη και τη συνδέει με το πρώτο κανάλι της αντιστοίχισης καμπύλης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της νέας ακολουθίας. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### get(String channelName) {#get-java.lang.String-}
```
public AnimationChannel get(String channelName)
```


Λαμβάνει το κανάλι με το δεδομένο όνομα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelName | java.lang.String | Όνομα καναλιού |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Animation channel
### getChannel(String channelName) {#getChannel-java.lang.String-}
```
public AnimationChannel getChannel(String channelName)
```


Λαμβάνει το κανάλι με το δεδομένο όνομα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelName | java.lang.String | Το όνομα καναλιού για εύρεση |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Channel with the name
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Λαμβάνει τον συνολικό αριθμό των καναλιών ιδιοτήτων που ορίζονται σε αυτήν την αντιστοίχηση καμπύλης κίνησης.

**Returns:**
int - Ο αριθμός των καναλιών.
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


Λαμβάνει την πρώτη ακολουθία κλειδιών στο καθορισμένο κανάλι

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelName | java.lang.String | Το όνομα καναλιού για εύρεση |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - First keyframe sequence with the channel name
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
### getProperty() {#getProperty--}
```
public Property getProperty()
```


Λαμβάνει την ιδιότητα που σχετίζεται με το CurveMapping

**Returns:**
[Property](../../com.aspose.threed/property) - the property associated with the CurveMapping
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
### resetChannels() {#resetChannels--}
```
public void resetChannels()
```


Αδειάζει τα κανάλια ιδιοτήτων αυτής της αντιστοίχισης καμπύλης κίνησης.

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ορίζει το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setProperty(Property value) {#setProperty-com.aspose.threed.Property-}
```
public void setProperty(Property value)
```


Λαμβάνει την ιδιότητα που σχετίζεται με το CurveMapping

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Property](../../com.aspose.threed/property) | Νέα τιμή |

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


Μετατρέπει το αντικείμενο σε συμβολοσειρά

**Returns:**
java.lang.String - Συμβολοσειρά αντικειμένου
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

