---
title: "KeyframeSequence"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

Η ακολουθία των key-frames, περιγράφει τη μετασχηματισμό μιας δειγματοληπτικής τιμής με την πάροδο του χρόνου.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor(name) | Αρχικοποιεί μια νέα παρουσία της κλάσης KeyframeSequence. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload() | Αρχικοποιεί μια νέα παρουσία της κλάσης KeyframeSequence. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Όνομα | Περιγραφή |
| --- | --- |
| getBindPoint() | Αποκτά το σημείο σύνδεσης ιδιοτήτων που ανήκει σε αυτήν την καμπύλη. |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| Όνομα | Περιγραφή |
| --- | --- |
| getKeyFrames() | Αποκτά τα βασικά πλαίσια αυτής της καμπύλης. Τα κλειδιά. |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| Όνομα | Περιγραφή |
| --- | --- |
| getPostBehavior() | Αποκτά τη μεταγενέστερη συμπεριφορά που υποδεικνύει τι πρέπει να είναι η δειγματοληπτική τιμή μετά το τελευταίο πλαίσιο-κλειδί. |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| Όνομα | Περιγραφή |
| --- | --- |
| getPreBehavior() | Αποκτά την προγενέστερη συμπεριφορά που υποδεικνύει τι πρέπει να είναι η δειγματοληπτική τιμή πριν από το πρώτο κλειδί. |

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


### add{#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add(time, value) | Δημιουργήστε ένα νέο key frame με καθορισμένη τιμή |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| time | Αριθμός | Θέση χρόνου (μετράται σε δευτερόλεπτα) |
| τιμή | Αριθμός | Η τιμή σε αυτή τη θέση χρόνου |

 **Result:**



---


### add{#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add(time, value, interpolation) | Δημιουργήστε ένα νέο key frame με καθορισμένη τιμή |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| time | Αριθμός | Θέση χρόνου (μετράται σε δευτερόλεπτα) |
| τιμή | Αριθμός | Η τιμή σε αυτή τη θέση χρόνου |
| παρεμβολή | Παρεμβολή | Παρεμβολή |

 **Result:**



---


### reset{#reset}

| Όνομα | Περιγραφή |
| --- | --- |
| reset() | Αφαιρεί όλα τα key frames και επαναφέρει τις συμπεριφορές post/pre. |

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


### iterator{#iterator}

| Όνομα | Περιγραφή |
| --- | --- |
| iterator() | Δεσμευμένο για εσωτερική χρήση. |

 **Result:**
Property


---



