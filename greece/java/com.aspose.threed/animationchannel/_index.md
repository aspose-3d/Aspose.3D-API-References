---
title: AnimationChannel
second_title: Aspose.3D for Java API Reference
description: Ένα κανάλι αντιστοιχίζει το πεδίο συνιστώσας της ιδιότητας σε ένα σύνολο ακολουθιών κλειδιών καρέ
type: docs
weight: 13
url: /el/java/com.aspose.threed/animationchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.KeyframeSequence](../../com.aspose.threed/keyframesequence)
```
public class AnimationChannel extends KeyframeSequence
```

Ένα κανάλι αντιστοιχίζει το πεδίο συνιστώσας της ιδιότητας σε ένα σύνολο ακολουθιών κλειδιών-πλαισίων
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(double time, float value)](#add-double-float-) | Δημιουργήστε ένα νέο key frame με την καθορισμένη τιμή |
| [add(double time, float value, Interpolation interpolation)](#add-double-float-com.aspose.threed.Interpolation-) | Δημιουργήστε ένα νέο key frame με την καθορισμένη τιμή |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getBindPoint()](#getBindPoint--) | Αποκτά το σημείο σύνδεσης ιδιότητας που ανήκει σε αυτή την καμπύλη |
| [getClass()](#getClass--) |  |
| [getComponentType()](#getComponentType--) | Λαμβάνει τον τύπο του πεδίου συνιστώσας |
| [getDefaultValue()](#getDefaultValue--) | Λαμβάνει την προεπιλεγμένη τιμή του καναλιού. |
| [getKeyFrames()](#getKeyFrames--) | Αποκτά τα key frames αυτής της καμπύλης. |
| [getKeyframeSequence()](#getKeyframeSequence--) | Λαμβάνει τη συσχετισμένη ακολουθία κλειδιού καρέ μέσα σε αυτό το κανάλι |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getPostBehavior()](#getPostBehavior--) | Αποκτά τη μεταγενέστερη συμπεριφορά που υποδεικνύει τι πρέπει να είναι η δειγματοληπτική τιμή μετά το τελευταίο key frame. |
| [getPreBehavior()](#getPreBehavior--) | Αποκτά τη προγενέστερη συμπεριφορά που υποδεικνύει τι πρέπει να είναι η δειγματοληπτική τιμή πριν από το πρώτο key. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Αποκτά τον enumerator για τη διαπέραση όλων των key frames. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [reset()](#reset--) | Αφαιρεί όλα τα key frames και επαναφέρει τις μεταγενέστερες/προγενέστερες συμπεριφορές. |
| [setDefaultValue(Object value)](#setDefaultValue-java.lang.Object-) | Ορίζει την προεπιλεγμένη τιμή του καναλιού. |
| [setKeyframeSequence(KeyframeSequence value)](#setKeyframeSequence-com.aspose.threed.KeyframeSequence-) | Λαμβάνει τη συσχετισμένη ακολουθία κλειδιού καρέ μέσα σε αυτό το κανάλι |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(double time, float value) {#add-double-float-}
```
public void add(double time, float value)
```


Δημιουργήστε ένα νέο key frame με την καθορισμένη τιμή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| χρόνος | double | Θέση χρόνου (μετράται σε δευτερόλεπτα) |
| τιμή | float | Η τιμή σε αυτή τη θέση χρόνου |

### add(double time, float value, Interpolation interpolation) {#add-double-float-com.aspose.threed.Interpolation-}
```
public void add(double time, float value, Interpolation interpolation)
```


Δημιουργήστε ένα νέο key frame με την καθορισμένη τιμή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| χρόνος | double | Θέση χρόνου (μετράται σε δευτερόλεπτα) |
| τιμή | float | Η τιμή σε αυτή τη θέση χρόνου |
| interpolation | [Interpolation](../../com.aspose.threed/interpolation) | Ο τύπος παρεμβολής αυτού του key frame |

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
### getBindPoint() {#getBindPoint--}
```
public BindPoint getBindPoint()
```


Αποκτά το σημείο σύνδεσης ιδιότητας που ανήκει σε αυτή την καμπύλη

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


Λαμβάνει τον τύπο του πεδίου συνιστώσας

**Returns:**
java.lang.Class<?> - ο τύπος του πεδίου συνιστώσας
### getDefaultValue() {#getDefaultValue--}
```
public Object getDefaultValue()
```


Λαμβάνει την προεπιλεγμένη τιμή του καναλιού. Εάν ένα κανάλι δεν έχει συνδεδεμένες ακολουθίες κλειδιών καρέ, η προεπιλεγμένη τιμή θα χρησιμοποιηθεί κατά την αξιολόγηση της κίνησης. Ένα πραγματικό σενάριο: Η κίνηση (Animation) αναπαριστά μόνο την x‑συντεταγμένη ενός κόμβου, οι y και z δεν αλλάζουν, οπότε η προεπιλεγμένη τιμή θα χρησιμοποιηθεί κατά την πλήρη αξιολόγηση της μετάφρασης.

**Returns:**
java.lang.Object - η προεπιλεγμένη τιμή του καναλιού. Εάν ένα κανάλι δεν έχει συνδεδεμένες ακολουθίες κλειδιών καρέ, η προεπιλεγμένη τιμή θα χρησιμοποιηθεί κατά την αξιολόγηση της κίνησης. Ένα πραγματικό σενάριο: Η κίνηση (Animation) αναπαριστά μόνο την x‑συντεταγμένη ενός κόμβου, οι y και z δεν αλλάζουν, οπότε η προεπιλεγμένη τιμή θα χρησιμοποιηθεί κατά την πλήρη αξιολόγηση της μετάφρασης.
### getKeyFrames() {#getKeyFrames--}
```
public List<KeyFrame> getKeyFrames()
```


Αποκτά τα key frames αυτής της καμπύλης.

**Returns:**
java.util.List<com.aspose.threed.KeyFrame> - τα key frames αυτής της καμπύλης.
### getKeyframeSequence() {#getKeyframeSequence--}
```
public KeyframeSequence getKeyframeSequence()
```


Λαμβάνει τη συσχετισμένη ακολουθία κλειδιού καρέ μέσα σε αυτό το κανάλι

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - associated keyframe sequence inside this channel
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getPostBehavior() {#getPostBehavior--}
```
public Extrapolation getPostBehavior()
```


Αποκτά τη μεταγενέστερη συμπεριφορά που υποδεικνύει τι πρέπει να είναι η δειγματοληπτική τιμή μετά το τελευταίο key frame.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the post behavior indicates what the sampled value should be after the last key frame.
### getPreBehavior() {#getPreBehavior--}
```
public Extrapolation getPreBehavior()
```


Αποκτά τη προγενέστερη συμπεριφορά που υποδεικνύει τι πρέπει να είναι η δειγματοληπτική τιμή πριν από το πρώτο key.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the pre behavior indicates what the sampled value should be before the first key.
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


Αποκτά τον enumerator για τη διαπέραση όλων των key frames.

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
### reset() {#reset--}
```
public void reset()
```


Αφαιρεί όλα τα key frames και επαναφέρει τις μεταγενέστερες/προγενέστερες συμπεριφορές.

### setDefaultValue(Object value) {#setDefaultValue-java.lang.Object-}
```
public void setDefaultValue(Object value)
```


Ορίζει την προεπιλεγμένη τιμή του καναλιού. Εάν ένα κανάλι δεν έχει συνδεδεμένες ακολουθίες κλειδιών καρέ, η προεπιλεγμένη τιμή θα χρησιμοποιηθεί κατά την αξιολόγηση της κίνησης. Ένα πραγματικό σενάριο: Η κίνηση (Animation) αναπαριστά μόνο την x‑συντεταγμένη ενός κόμβου, οι y και z δεν αλλάζουν, οπότε η προεπιλεγμένη τιμή θα χρησιμοποιηθεί κατά την πλήρη αξιολόγηση της μετάφρασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object | Νέα τιμή |

### setKeyframeSequence(KeyframeSequence value) {#setKeyframeSequence-com.aspose.threed.KeyframeSequence-}
```
public void setKeyframeSequence(KeyframeSequence value)
```


Λαμβάνει τη συσχετισμένη ακολουθία κλειδιού καρέ μέσα σε αυτό το κανάλι

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Νέα τιμή |

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

