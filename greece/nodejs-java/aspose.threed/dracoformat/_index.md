---
title: "DracoFormat"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Μορφή Google Draco  @hideconstructor


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


### decode{#decode}

| Όνομα | Περιγραφή |
| --- | --- |
| decode(fileName) | Αποκωδικοποιήστε το point cloud ή το mesh από το καθορισμένο όνομα αρχείου |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Το όνομα αρχείου περιέχει το αρχείο drc |

 **Result:**
Geometry


---


### decode{#decode}

| Όνομα | Περιγραφή |
| --- | --- |
| decode(data) | Αποκωδικοποιήστε το point cloud ή το mesh από δεδομένα μνήμης |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Τα ακατέργαστα bytes του drc |

 **Result:**
Geometry


---


### encode{#encode}

| Όνομα | Περιγραφή |
| --- | --- |
| encode(entity, fileName, options) | Κωδικοποιήστε την οντότητα στο καθορισμένο αρχείο |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| οντότητα | Οντότητα | Η οντότητα που θα κωδικοποιηθεί |
| fileName | String | Το όνομα αρχείου που θα γραφτεί |
| επιλογές | DracoSaveOptions | Επιπλέον επιλογές για την κωδικοποίηση του point cloud |

 **Result:**
Geometry


---


### encode{#encode}

| Όνομα | Περιγραφή |
| --- | --- |
| encode(entity, options) | Κωδικοποιήστε την οντότητα σε ακατέργαστα δεδομένα Draco |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| οντότητα | Οντότητα | Η οντότητα που θα κωδικοποιηθεί |
| επιλογές | DracoSaveOptions | Επιπλέον επιλογές για την κωδικοποίηση του point cloud |

 **Result:**
byte[]


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



