---
title: "Pose"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/pose/
---
## Pose class

Η pose χρησιμοποιείται για την αποθήκευση του πίνακα μετασχηματισμού όταν η γεωμετρία είναι ενσωματωμένη. Η pose είναι ένα σύνολο από BonePose, κάθε BonePose αποθηκεύει τις συγκεκριμένες πληροφορίες μετασχηματισμού του κόμβου οστέου.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor(name) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Pose. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Pose. |

 **Result:**



---


### getPoseType{#getPoseType}

| Όνομα | Περιγραφή |
| --- | --- |
| getPoseType() | Λαμβάνει ή ορίζει τον τύπο της στάσης. Η τιμή της ιδιότητας είναι η ακέραια σταθερά PoseType. Ο τύπος της στάσης. |

 **Result:**



---


### setPoseType{#setPoseType}

| Όνομα | Περιγραφή |
| --- | --- |
| setPoseType(value) | Λαμβάνει ή ορίζει τον τύπο της στάσης. Η τιμή της ιδιότητας είναι η ακέραια σταθερά PoseType. Ο τύπος της στάσης. |

 **Result:**



---


### getBonePoses{#getBonePoses}

| Όνομα | Περιγραφή |
| --- | --- |
| getBonePoses() | Λαμβάνει όλα τα BonePose. Οι κόμβοι. |

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


### addBonePose{#addBonePose}

| Όνομα | Περιγραφή |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | Αποθηκεύει τον πίνακα μετασχηματισμού στάσης για τον δοσμένο κόμβο οστέου. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| κόμβος | Κόμβος | Κόμβος οστέου. |
| matrix | Matrix4 | Πίνακας μετασχηματισμού. |
| localMatrix | boolean | Αν οριστεί σε |

 **Result:**



---


### addBonePose{#addBonePose}

| Όνομα | Περιγραφή |
| --- | --- |
| addBonePose(node, matrix) | Αποθηκεύει τον πίνακα μετασχηματισμού θέσης για τον δεδομένο κόμβο οστέου. Ο γενικός πίνακας μετασχηματισμού υπονοείται. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| κόμβος | Κόμβος | Κόμβος οστέου. |
| matrix | Matrix4 | Πίνακας μετασχηματισμού. |

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



