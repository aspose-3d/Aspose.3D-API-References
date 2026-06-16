---
title: "FileFormat"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

Ορισμός μορφής αρχείου  @hideconstructor


## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| MAYA_BINARY | Autodesk Maya σε δυαδική μορφή |
| STL_BINARY | Δυαδική μορφή αρχείου STL |
| STLASCII | Μορφή αρχείου ASCII STL |
| COLLADA | Μορφή αρχείου Collada |
| GLTF | Το glTF της Khronos Group |
| GLTF_BINARY | Το glTF της Khronos Group σε δυαδική μορφή |
| PDF | Το Portable Document Format της Adobe |
| DXF | AutoCAD DXF |
| PLY | Μορφή αρχείου Polygon ή Stanford Triangle Format |
| X_BINARY | Αρχείο DirectX X σε δυαδική μορφή |
| X_TEXT | Αρχείο DirectX X σε δυαδική μορφή |
| DRACO | Google Draco Mesh |
| RVM_TEXT | Μοντέλο του Συστήματος Διαχείρισης Σχεδίασης Εγκαταστάσεων AVEVA σε μορφή κειμένου |
| RVM_BINARY | Μοντέλο του Συστήματος Διαχείρισης Σχεδίασης Εγκαταστάσεων AVEVA σε δυαδική μορφή |
| ASE | Μορφή ASCII εξαγωγέα σκηνής του 3D Studio Max. |
| IFC | Μοντέλο δεδομένων Industry Foundation Classes (ISO 16739-1). |
| AMF | Μορφή αρχείου προσθετικής κατασκευής |
| VRML | Η Virtual Reality Modeling Language |
| ZIP | Αρχείο Zip που περιέχει άλλες μορφές αρχείων 3d. |
| USD | Καθολική Περιγραφή Σκηνής |
| USDZ | Συμπιεσμένη Καθολική Περιγραφή Σκηνής |
| XYZ | Αρχείο νέφους σημείων Xyz |
| PCD | Αρχείο δεδομένων νέφους σημείων PCL σε λειτουργία ASCII |
| PCD_BINARY | Αρχείο δεδομένων νέφους σημείων PCL σε δυαδική λειτουργία |

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


### getFormatByExtension{#getFormatByExtension}

| Όνομα | Περιγραφή |
| --- | --- |
| getFormatByExtension(extensionName) | Λαμβάνει την προτιμώμενη μορφή αρχείου από το όνομα επέκτασης του αρχείου. Το όνομα επέκτασης πρέπει να αρχίζει με τελεία ('.'). |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| extensionNam | String | null |

 **Result:**
FileFormat


---


### detect{#detect}

| Όνομα | Περιγραφή |
| --- | --- |
| detect(fileName) | Ανιχνεύει τη μορφή αρχείου από το όνομα αρχείου, το αρχείο πρέπει να είναι αναγνώσιμο ώστε το Aspose.3D να μπορεί να ανιχνεύσει τη μορφή αρχείου μέσω της κεφαλίδας του αρχείου. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
FileFormat


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



