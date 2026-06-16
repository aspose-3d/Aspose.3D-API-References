---
title: "AnimationClip"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

Το κλιπ κίνησης είναι μια συλλογή κινήσεων. Η σκηνή μπορεί να έχει ένα ή περισσότερα κλιπ κίνησης.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor() | Αρχικοποιεί μια νέα παρουσία της κλάσης AnimationClip. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(name) | Αρχικοποιεί μια νέα παρουσία της κλάσης AnimationClip. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα |

 **Result:**



---


### getAnimations{#getAnimations}

| Όνομα | Περιγραφή |
| --- | --- |
| getAnimations() | Λαμβάνει τις κινήσεις που περιέχονται μέσα στο κλιπ. Τα στρώματα. |

 **Result:**



---


### getDescription{#getDescription}

| Όνομα | Περιγραφή |
| --- | --- |
| getDescription() | Λαμβάνει ή ορίζει την περιγραφή αυτού του κλιπ κίνησης |

 **Result:**



---


### setDescription{#setDescription}

| Όνομα | Περιγραφή |
| --- | --- |
| setDescription(value) | Λαμβάνει ή ορίζει την περιγραφή αυτού του κλιπ κίνησης |

 **Result:**



---


### getStart{#getStart}

| Όνομα | Περιγραφή |
| --- | --- |
| getStart() | Λαμβάνει ή ορίζει το χρόνο σε δευτερόλεπτα της αρχής του κλιπ. |

 **Result:**



---


### setStart{#setStart}

| Όνομα | Περιγραφή |
| --- | --- |
| setStart(value) | Λαμβάνει ή ορίζει το χρόνο σε δευτερόλεπτα της αρχής του κλιπ. |

 **Result:**



---


### getStop{#getStop}

| Όνομα | Περιγραφή |
| --- | --- |
| getStop() | Λαμβάνει ή ορίζει το χρόνο σε δευτερόλεπτα του τέλους του κλιπ. |

 **Result:**



---


### setStop{#setStop}

| Όνομα | Περιγραφή |
| --- | --- |
| setStop(value) | Λαμβάνει ή ορίζει το χρόνο σε δευτερόλεπτα του τέλους του κλιπ. |

 **Result:**



---


### getScene{#getScene}

| Όνομα | Περιγραφή |
| --- | --- |
| getScene() | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |

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


### createAnimationNode{#createAnimationNode}

| Όνομα | Περιγραφή |
| --- | --- |
| createAnimationNode(nodeName) | Μια συντομευμένη συνάρτηση για τη δημιουργία και καταχώριση του κόμβου κίνησης στο τρέχον κλιπ. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeName | String | Νέο όνομα κόμβου κίνησης |

 **Result:**
AnimationNode


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



