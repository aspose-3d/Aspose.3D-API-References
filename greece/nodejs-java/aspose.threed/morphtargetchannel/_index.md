---
title: "MorphTargetChannel"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

Ένα MorphTargetChannel χρησιμοποιείται από το MorphTargetDeformer για την οργάνωση των γεωμετριών-στόχων.  Μερικές μορφές αρχείων όπως το FBX υποστηρίζουν πολλαπλά κανάλια παράλληλα.  Το βάρος είναι μεταξύ 0 και 1.0, και το προεπιλεγμένο βάρος για τον στόχο είναι 0.0;


## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| DEFAULT_WEIGHT | Προεπιλεγμένο βάρος για το morph target. |

## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor(name) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MorphTargetChannel. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MorphTargetChannel. |

 **Result:**



---


### getWeights{#getWeights}

| Όνομα | Περιγραφή |
| --- | --- |
| getWeights() | Λαμβάνει τις πλήρεις τιμές βάρους των γεωμετριών-στόχου. Τα πλήρη βάρη. |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| Όνομα | Περιγραφή |
| --- | --- |
| getChannelWeight() | Λαμβάνει ή ορίζει το βάρος του παραμορφωτή αυτού του καναλιού. Το βάρος είναι μεταξύ 0.0 και 1.0 |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| Όνομα | Περιγραφή |
| --- | --- |
| setChannelWeight(value) | Λαμβάνει ή ορίζει το βάρος του παραμορφωτή αυτού του καναλιού. Το βάρος είναι μεταξύ 0.0 και 1.0 |

 **Result:**



---


### getTargets{#getTargets}

| Όνομα | Περιγραφή |
| --- | --- |
| getTargets() | Λαμβάνει όλους τους στόχους που σχετίζονται με το κανάλι. |

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


### getWeight{#getWeight}

| Όνομα | Περιγραφή |
| --- | --- |
| getWeight(target) | Λαμβάνει το βάρος για τον καθορισμένο στόχο, εάν ο στόχος δεν ανήκει σε αυτό το κανάλι, επιστρέφεται η προεπιλεγμένη τιμή 0. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| targe | Σχήμα | null |

 **Result:**
Αριθμός


---


### setWeight{#setWeight}

| Όνομα | Περιγραφή |
| --- | --- |
| setWeight(target, weight) | Ορίζει το βάρος για τον καθορισμένο στόχο, η προεπιλεγμένη τιμή είναι 1, το εύρος πρέπει να είναι μεταξύ 0~1. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| targe | Σχήμα | null |
| ζυγίζει | Αριθμός | null |

 **Result:**
Αριθμός


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



