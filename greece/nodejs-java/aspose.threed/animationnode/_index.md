---
title: "AnimationNode"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Το Aspose.3D υποστηρίζει ιεραρχία κίνησης, κάθε κίνηση μπορεί να αποτελείται από πολλές κινήσεις και τον ορισμό των key-frame της κίνησης. Το AnimationNode ορίζει τη μετασχηματισμό μιας τιμής ιδιότητας με την πάροδο του χρόνου, για παράδειγμα, ένας κόμβος κίνησης μπορεί να χρησιμοποιηθεί για να ελέγξει τον μετασχηματισμό ενός κόμβου ή άλλες αριθμητικές ιδιότητες του αντικειμένου A3DObject.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor(name) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης AnimationNode. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης AnimationNode. |

 **Result:**



---


### getBindPoints{#getBindPoints}

| Όνομα | Περιγραφή |
| --- | --- |
| getBindPoints() | Λαμβάνει τα τρέχοντα σημεία σύνδεσης ιδιοτήτων |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| Όνομα | Περιγραφή |
| --- | --- |
| getSubAnimations() | Λαμβάνει τους κόμβους υπο-ανιμασιών κάτω από τις τρέχουσες ανιμασίες |

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


### findBindPoint{#findBindPoint}

| Όνομα | Περιγραφή |
| --- | --- |
| findBindPoint(name) | Βρίσκει το σημείο σύνδεσης με βάση το όνομα. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα σημείου σύνδεσης για εύρεση. |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| Όνομα | Περιγραφή |
| --- | --- |
| getBindPoint(target, propName, create) | Λαμβάνει το σημείο σύνδεσης της κίνησης στην καθορισμένη ιδιότητα. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| target | A3DObject | Σε ποιο αντικείμενο θα δημιουργηθεί το σημείο σύνδεσης. |
| propName | String | Το όνομα της ιδιότητας. |
| δημιουργία | boolean | Αν οριστεί σε |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Όνομα | Περιγραφή |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | Λαμβάνει την ακολουθία καρέ-κλειδιού στην καθορισμένη ιδιότητα και στο κανάλι. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| target | A3DObject | Σε ποιο αντικείμενο θα δημιουργηθεί η ακολουθία καρέ-κλειδιού. |
| propName | String | Το όνομα της ιδιότητας. |
| channelName | String | Το όνομα του καναλιού. |
| δημιουργία | boolean | Αν οριστεί σε |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| Όνομα | Περιγραφή |
| --- | --- |
| getKeyframeSequence(target, propName, create) | Λαμβάνει την ακολουθία καρέ-κλειδιού στην καθορισμένη ιδιότητα. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| target | A3DObject | Σε ποιο αντικείμενο θα δημιουργηθεί η ακολουθία καρέ-κλειδιού. |
| propName | String | Το όνομα της ιδιότητας. |
| δημιουργία | boolean | Αν οριστεί σε |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| Όνομα | Περιγραφή |
| --- | --- |
| createBindPoint(obj, propName) | Δημιουργεί ένα BindPoint βάσει του τύπου δεδομένων της ιδιότητας. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | A3DObject | Αντικείμενο. |
| propName | String | Όνομα ιδιότητας. |

 **Result:**
BindPoint


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



