---
title: "Property"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/property/
---
## Property class

Κλάση για την αποθήκευση ιδιοτήτων που ορίζονται από τον χρήστη.  @hideconstructor


## Μέθοδοι

### getValue{#getValue}

| Όνομα | Περιγραφή |
| --- | --- |
| getValue() | Λαμβάνει ή ορίζει την τιμή. Η τιμή. |

 **Result:**



---


### setValue{#setValue}

| Όνομα | Περιγραφή |
| --- | --- |
| setValue(value) | Λαμβάνει ή ορίζει την τιμή. Η τιμή. |

 **Result:**



---


### setName{#setName}

| Όνομα | Περιγραφή |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| Όνομα | Περιγραφή |
| --- | --- |
| getValueType() | Λαμβάνει τον τύπο της τιμής της ιδιότητας. Ο τύπος της τιμής. |

 **Result:**



---


### getProperties{#getProperties}

| Όνομα | Περιγραφή |
| --- | --- |
| getProperties() | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Όνομα | Περιγραφή |
| --- | --- |
| getBindPoint(anim, create) | Λαμβάνει το σημείο σύνδεσης της ιδιότητας σε καθορισμένη παρουσία animation. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| anim | AnimationNode | Σε ποια animation να δημιουργήσετε το bind point. |
| δημιουργία | boolean | Δημιουργήστε το bind point της ιδιότητας εάν δεν βρεθεί. |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Όνομα | Περιγραφή |
| --- | --- |
| getKeyframeSequence(anim, create) | Αποκτά τη σειρά keyframe σε συγκεκριμένη παρουσία animation. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| anim | AnimationNode | Σε ποια animation να δημιουργήσετε τη σειρά keyframe. |
| δημιουργία | boolean | Δημιουργήστε τη σειρά keyframe εάν δεν βρεθεί. |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| Όνομα | Περιγραφή |
| --- | --- |
| toString() | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει την τρέχουσα Property. |

 **Result:**
String


---


### removeProperty{#removeProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| removeProperty(property) | Αφαιρεί μια δυναμική ιδιότητα. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| property | Property | Ποια ιδιότητα να αφαιρεθεί |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| removeProperty(property) | Αφαιρέστε την καθορισμένη ιδιότητα που αναγνωρίζεται με όνομα |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| getProperty(property) | Αποκτήστε την τιμή της καθορισμένης ιδιότητας |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| property | String | Όνομα ιδιότητας |

 **Result:**
Αντικείμενο


---


### setProperty{#setProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| setProperty(property, value) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| property | String | Όνομα ιδιότητας |
| τιμή | Αντικείμενο | Η τιμή της ιδιότητας |

 **Result:**
Αντικείμενο


---


### findProperty{#findProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| findProperty(propertyName) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Created by CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Identified by its name) |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyName | String | Όνομα ιδιότητας. |

 **Result:**
Property


---



