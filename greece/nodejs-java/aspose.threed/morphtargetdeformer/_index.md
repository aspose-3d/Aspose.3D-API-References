---
title: "MorphTargetDeformer"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/morphtargetdeformer/
---
## MorphTargetDeformer class

Το MorphTargetDeformer παρέχει animation ανά κορυφή.  Το MorphTargetDeformer οργανώνει όλους τους στόχους μέσω MorphTargetChannel, κάθε κανάλι μπορεί να οργανώσει πολλαπλούς στόχους.  Μία κοινή χρήση του morph target deformer είναι η εφαρμογή εκφράσεων προσώπου σε έναν χαρακτήρα.  Περισσότερες λεπτομέρειες μπορούν να βρεθούν στο https://en.wikipedia.org/wiki/Morph_target_animation


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor(name) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MorphTargetDeformer. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MorphTargetDeformer. |

 **Result:**



---


### getChannels{#getChannels}

| Όνομα | Περιγραφή |
| --- | --- |
| getChannels() | Λαμβάνει όλα τα κανάλια που περιέχονται σε αυτόν τον παραμορφωτή |

 **Result:**



---


### getOwner{#getOwner}

| Όνομα | Περιγραφή |
| --- | --- |
| getOwner() | Λαμβάνει τη γεωμετρία που κατέχει αυτόν τον SkinDeformer. |

 **Result:**



---


### getName{#getName}

| Όνομα | Περιγραφή |
| --- | --- |
| getName() | Λαμβάνει ή ορίζει το όνομα. Το όνομα. |

 **Result:**



---


### setName{#setName}

| Όνομα | Περιγραφή |
| --- | --- |
| setName(value) | Λαμβάνει ή ορίζει το όνομα. Το όνομα. |

 **Result:**



---


### getProperties{#getProperties}

| Όνομα | Περιγραφή |
| --- | --- |
| getProperties() | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |

 **Result:**



---


### get{#get}

| Όνομα | Περιγραφή |
| --- | --- |
| get(target) |  |

 **Result:**



---


### set{#set}

| Όνομα | Περιγραφή |
| --- | --- |
| set(target, value) |  |

 **Result:**



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



