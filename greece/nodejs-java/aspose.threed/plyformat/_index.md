---
title: "PlyFormat"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

Η μορφή PLY.  @hideconstructor


## Μέθοδοι

### getVersion{#getVersion}

| Όνομα | Περιγραφή |
| --- | --- |
| getVersion() | Λαμβάνει την έκδοση μορφής αρχείου |

 **Result:**



---


### getExtension{#getExtension}

| Όνομα | Περιγραφή |
| --- | --- |
| getExtension() | Λαμβάνει το όνομα επέκτασης αυτού του τύπου. |

 **Result:**



---


### getExtensions{#getExtensions}

| Όνομα | Περιγραφή |
| --- | --- |
| getExtensions() | Λαμβάνει τα ονόματα επεκτάσεων αυτού του τύπου. |

 **Result:**



---


### getContentType{#getContentType}

| Όνομα | Περιγραφή |
| --- | --- |
| getContentType() | Λαμβάνει τον τύπο περιεχομένου μορφής αρχείου. Η τιμή της ιδιότητας είναι η ακέραια σταθερά FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Όνομα | Περιγραφή |
| --- | --- |
| getFileFormatType() | Λαμβάνει τον τύπο μορφής αρχείου |

 **Result:**



---


### encode{#encode}

| Όνομα | Περιγραφή |
| --- | --- |
| encode(entity, fileName) | Κωδικοποιήστε την οντότητα και αποθηκεύστε το αποτέλεσμα σε ένα εξωτερικό αρχείο. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| οντότητα | Οντότητα | Η οντότητα προς κωδικοποίηση |
| fileName | String | Το αρχείο στο οποίο θα γραφτεί |

 **Result:**



---


### encode{#encode}

| Όνομα | Περιγραφή |
| --- | --- |
| encode(entity, fileName, opt) | Κωδικοποιήστε την οντότητα και αποθηκεύστε το αποτέλεσμα σε ένα εξωτερικό αρχείο. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| οντότητα | Οντότητα | Η οντότητα προς κωδικοποίηση |
| fileName | String | Το αρχείο στο οποίο θα γραφτεί |
| opt | PlySaveOptions | Επιλογές αποθήκευσης |

 **Result:**



---


### decode{#decode}

| Όνομα | Περιγραφή |
| --- | --- |
| decode(fileName) | Αποκωδικοποιήστε ένα νέφος σημείων ή πλέγμα από το καθορισμένο ρεύμα. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Το ρεύμα εισόδου |

 **Result:**
Geometry


---


### decode{#decode}

| Όνομα | Περιγραφή |
| --- | --- |
| decode(fileName, opt) | Αποκωδικοποιήστε ένα νέφος σημείων ή πλέγμα από το καθορισμένο ρεύμα. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Το ρεύμα εισόδου |
| opt | PlyLoadOptions | Η επιλογή φόρτωσης της μορφής PLY |

 **Result:**
Geometry


---


### createLoadOptions{#createLoadOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| createLoadOptions() | Δημιουργεί προεπιλεγμένες επιλογές φόρτωσης για αυτή τη μορφή αρχείου |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| createSaveOptions() | Δημιουργεί προεπιλεγμένες επιλογές αποθήκευσης για αυτή τη μορφή αρχείου |

 **Result:**
SaveOptions


---


### toString{#toString}

| Όνομα | Περιγραφή |
| --- | --- |
| toString() | Μορφές σε συμβολοσειρά |

 **Result:**
String


---



