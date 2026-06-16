---
title: "Scene"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/scene/
---
## Scene class

Μια σκηνή είναι ένα αντικείμενο ανώτερου επιπέδου που περιέχει τους κόμβους, τις γεωμετρίες, τα υλικά, τις υφές, την κίνηση, τις στάσεις, τις υπο-σκηνές κ.λπ.  Η σκηνή μπορεί να έχει υπο-σκηνές, λειτουργεί ως υποστήριξη πολλαπλών εγγράφων σε αρχεία όπως collada/blender/fbx.  Η ιεραρχία κόμβων μπορεί να προσπελαστεί μέσω του RootNodeLibrary, το οποίο χρησιμοποιείται για τη διατήρηση αναφοράς σε μη συνδεδεμένα αντικείμενα κατά τη σειριοποίηση (όπως μετα-δεδομένα ή προσαρμοσμένα αντικείμενα) ώστε να μπορεί να χρησιμοποιηθεί ως βιβλιοθήκη.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor() | Αρχικοποιεί μια νέα παρουσία της κλάσης Scene. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(entity) | Αρχικοποιεί μια νέα παρουσία της κλάσης Scene με μια οντότητα συνδεδεμένη σε έναν νέο κόμβο. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| οντότητα | Οντότητα | Η αρχική οντότητα που συνδέθηκε με τη σκηνή |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload2(parentScene, name) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Scene ως υπο-σκηνή. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| parentScene | Scene | Η γονική σκηνή. |
| name | String | Το όνομα της σκηνής. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload3(fileName) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Scene και ανοίγει το αρχείο αμέσως. Αυτός είναι ένας παρωχημένος κατασκευαστής, παρακαλώ χρησιμοποιήστε #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken). |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Το όνομα του αρχείου για άνοιγμα. |

 **Result:**



---


### getSubScenes{#getSubScenes}

| Όνομα | Περιγραφή |
| --- | --- |
| getSubScenes() | Ανακτά όλες τις υπο-σκηνές |

 **Result:**



---


### getLibrary{#getLibrary}

| Όνομα | Περιγραφή |
| --- | --- |
| getLibrary() | Αντικείμενα που δεν χρησιμοποιούνται άμεσα στην ιεραρχία της σκηνής μπορούν να οριστούν στη Library. Αυτό είναι χρήσιμο όταν χρησιμοποιείτε υπο-σκηνές και τοποθετείτε επαναχρησιμοποιήσιμα στοιχεία κάτω από τις υπο-σκηνές. |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| Όνομα | Περιγραφή |
| --- | --- |
| getAnimationClips() | Ανακτά όλα τα AnimationClip που ορίζονται στη σκηνή. |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| Όνομα | Περιγραφή |
| --- | --- |
| getCurrentAnimationClip() | Ανακτά ή ορίζει το ενεργό AnimationClip |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| Όνομα | Περιγραφή |
| --- | --- |
| setCurrentAnimationClip(value) | Ανακτά ή ορίζει το ενεργό AnimationClip |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Όνομα | Περιγραφή |
| --- | --- |
| getAssetInfo() | Ανακτά ή ορίζει τις πληροφορίες του ανώτερου επιπέδου του περιουσιακού στοιχείου. Πληροφορίες εγγράφου. |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Όνομα | Περιγραφή |
| --- | --- |
| setAssetInfo(value) | Ανακτά ή ορίζει τις πληροφορίες του ανώτερου επιπέδου του περιουσιακού στοιχείου. Πληροφορίες εγγράφου. |

 **Result:**



---


### getPoses{#getPoses}

| Όνομα | Περιγραφή |
| --- | --- |
| getPoses() | Ανακτά όλες τις Pose που χρησιμοποιούνται σε αυτή τη σκηνή. Οι Pose. |

 **Result:**



---


### getRootNode{#getRootNode}

| Όνομα | Περιγραφή |
| --- | --- |
| getRootNode() | Ανακτά τον ριζικό κόμβο της σκηνής. Ο ριζικός κόμβος. |

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


### getAnimationClip{#getAnimationClip}

| Όνομα | Περιγραφή |
| --- | --- |
| getAnimationClip(name) | Ανακτά ένα ονομασμένο AnimationClip |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Το |

 **Result:**
AnimationClip


---


### clear{#clear}

| Όνομα | Περιγραφή |
| --- | --- |
| clear() | Καθαρίζει το περιεχόμενο της σκηνής και επαναφέρει τις προεπιλεγμένες ρυθμίσεις. |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| Όνομα | Περιγραφή |
| --- | --- |
| createAnimationClip(name) | Μια συντομευμένη λειτουργία για τη δημιουργία και καταχώρηση του AnimationClip. Το πρώτο AnimationClip θα εκχωρηθεί στο CurrentAnimationClip. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα του animation clip |

 **Result:**
AnimationClip


---


### open{#open}

| Όνομα | Περιγραφή |
| --- | --- |
| open(fileName, options) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |
| επιλογές | LoadOptions | Πιο λεπτομερής διαμόρφωση για το άνοιγμα της ροής. |

 **Result:**
AnimationClip


---


### open{#open}

| Όνομα | Περιγραφή |
| --- | --- |
| open(fileName) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| Όνομα | Περιγραφή |
| --- | --- |
| fromFile(fileName) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |

 **Result:**
AnimationClip


---


### save{#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save(fileName) | Αποθηκεύει τη σκηνή στο καθορισμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |

 **Result:**
AnimationClip


---


### save{#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save(fileName, format) | Αποθηκεύει τη σκηνή στο καθορισμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |
| format | FileFormat | Μορφότυπο. |

 **Result:**
AnimationClip


---


### save{#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save(fileName, options) | Αποθηκεύει τη σκηνή στο καθορισμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |
| επιλογές | SaveOptions | Πιο λεπτομερής διαμόρφωση για την αποθήκευση της ροής. |

 **Result:**
AnimationClip


---


### render{#render}

| Όνομα | Περιγραφή |
| --- | --- |
| render(camera, fileName) | Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας. Το προεπιλεγμένο μέγεθος εξόδου είναι 1024x768 και η μορφή εξόδου είναι png. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| κάμερα | Κάμερα | Από ποια προοπτική κάμερας να αποδοθεί η σκηνή |
| fileName | String | Το όνομα αρχείου του αρχείου εξόδου |

 **Result:**
AnimationClip


---


### render{#render}

| Όνομα | Περιγραφή |
| --- | --- |
| render(camera, fileName, size, format) | Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| κάμερα | Κάμερα | Από ποια προοπτική κάμερας να αποδοθεί η σκηνή |
| fileName | String | Το όνομα αρχείου του αρχείου εξόδου |
| μέγεθος | Vector2 | Το μέγεθος της τελικής αποδομένης εικόνας |
| format | String | Η μορφή εικόνας του αρχείου εξόδου |

 **Result:**
AnimationClip


---


### render{#render}

| Όνομα | Περιγραφή |
| --- | --- |
| render(camera, fileName, size, format, options) | Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| κάμερα | Κάμερα | Από ποια προοπτική κάμερας να αποδοθεί η σκηνή |
| fileName | String | Το όνομα αρχείου του αρχείου εξόδου |
| μέγεθος | Vector2 | Το μέγεθος της τελικής αποδομένης εικόνας |
| format | String | Η μορφή εικόνας του αρχείου εξόδου |
| επιλογές | ImageRenderOptions | Η επιλογή για προσαρμογή ορισμένων εσωτερικών ρυθμίσεων. |

 **Result:**
AnimationClip


---


### render{#render}

| Όνομα | Περιγραφή |
| --- | --- |
| render(camera, bitmap) | Απόδοση της σκηνής σε bitmap από την προοπτική της δοσμένης κάμερας. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| κάμερα | Κάμερα | Από ποια προοπτική κάμερας να αποδοθεί η σκηνή |
| bitmap | TextureData | Στόχος του αποδιδόμενου αποτελέσματος |

 **Result:**
AnimationClip


---


### render{#render}

| Όνομα | Περιγραφή |
| --- | --- |
| render(camera, bitmap, options) | Απόδοση της σκηνής σε bitmap από την προοπτική της δοσμένης κάμερας. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| κάμερα | Κάμερα | Από ποια προοπτική κάμερας να αποδοθεί η σκηνή |
| bitmap | TextureData | Στόχος του αποδιδόμενου αποτελέσματος |
| επιλογές | ImageRenderOptions | Η επιλογή για προσαρμογή ορισμένων εσωτερικών ρυθμίσεων. |

 **Result:**
AnimationClip


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



