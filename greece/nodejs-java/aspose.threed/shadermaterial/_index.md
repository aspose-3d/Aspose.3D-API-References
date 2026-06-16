---
title: "ShaderMaterial"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/shadermaterial/
---
## ShaderMaterial class

Ένα υλικό shader επιτρέπει την περιγραφή του υλικού από εξωτερική μηχανή απόδοσης ή γλώσσα shader.  Το ShaderMaterial χρησιμοποιεί το ShaderTechnique για να περιγράψει τις συγκεκριμένες λεπτομέρειες απόδοσης,  και το πιο κατάλληλο θα χρησιμοποιηθεί ανάλογα με την τελική πλατφόρμα απόδοσης.  Για παράδειγμα, η παρουσία σας του ShaderMaterial μπορεί να έχει δύο τεχνικές, μία ορίζεται από HLSL και άλλη από GLSL.  Σε πλατφόρμα χωρίς παράθυρο, το GLSL πρέπει να χρησιμοποιηθεί αντί του HLSL.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor() | Αρχικοποιεί μια νέα παρουσία της κλάσης ShaderMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(name) | Αρχικοποιεί μια νέα παρουσία της κλάσης ShaderMaterial. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα |

 **Result:**



---


### getTechniques{#getTechniques}

| Όνομα | Περιγραφή |
| --- | --- |
| getTechniques() | Λαμβάνει όλες τις διαθέσιμες τεχνικές που ορίζονται σε αυτό το υλικό. |

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


### getTexture{#getTexture}

| Όνομα | Περιγραφή |
| --- | --- |
| getTexture(slotName) | Λαμβάνει την υφή από το καθορισμένο slot, μπορεί να είναι το όνομα ιδιότητας του υλικού ή το όνομα παραμέτρου του shader. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| slotName | String | Όνομα slot. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| Όνομα | Περιγραφή |
| --- | --- |
| setTexture(slotName, texture) | Ορίζει την υφή στο καθορισμένο slot |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| slotName | String | Όνομα slot. |
| texture | TextureBase | Υφή. |

 **Result:**
TextureBase


---


### toString{#toString}

| Όνομα | Περιγραφή |
| --- | --- |
| toString() | Μορφοποιεί το αντικείμενο σε συμβολοσειρά |

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


### iterator{#iterator}

| Όνομα | Περιγραφή |
| --- | --- |
| iterator() | Δεσμευμένο για εσωτερική χρήση. |

 **Result:**
Property


---



