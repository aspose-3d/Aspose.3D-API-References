---
title: "FbxSaveOptions"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/fbxsaveoptions/
---
## FbxSaveOptions class

Επιλογές αποθήκευσης για αρχείο Fbx.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor(format) | Αρχικοποιεί ένα FbxSaveOptions |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| μορφή | FileFormat | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(contentType) | Αρχικοποιήστε ένα FbxSaveOptions χρησιμοποιώντας την πιο πρόσφατη υποστηριζόμενη έκδοση. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getReusePrimitiveMesh{#getReusePrimitiveMesh}

| Όνομα | Περιγραφή |
| --- | --- |
| getReusePrimitiveMesh() | Επαναχρησιμοποιήστε το πλέγμα για τα πρωτότυπα με τις ίδιες παραμέτρους, αυτό θα μειώσει σημαντικά το μέγεθος του εξόδου FBX όταν η σκηνή κατασκευάστηκε από μεγάλο σύνολο πρωτότυπων σχημάτων (όπως εισαγόμενα από αρχεία CAD). Η προεπιλεγμένη τιμή είναι ψευδής |

 **Result:**



---


### setReusePrimitiveMesh{#setReusePrimitiveMesh}

| Όνομα | Περιγραφή |
| --- | --- |
| setReusePrimitiveMesh(value) | Επαναχρησιμοποιήστε το πλέγμα για τα πρωτότυπα με τις ίδιες παραμέτρους, αυτό θα μειώσει σημαντικά το μέγεθος του εξόδου FBX όταν η σκηνή κατασκευάστηκε από μεγάλο σύνολο πρωτότυπων σχημάτων (όπως εισαγόμενα από αρχεία CAD). Η προεπιλεγμένη τιμή είναι ψευδής |

 **Result:**



---


### getEnableCompression{#getEnableCompression}

| Όνομα | Περιγραφή |
| --- | --- |
| getEnableCompression() | Συμπίεση μεγάλων δυαδικών δεδομένων στο αρχείο FBX (π.χ. δεδομένα κίνησης, σημεία ελέγχου, δεδομένα στοιχείων κορυφών, δείκτες), η προεπιλεγμένη τιμή είναι αληθής. |

 **Result:**



---


### setEnableCompression{#setEnableCompression}

| Όνομα | Περιγραφή |
| --- | --- |
| setEnableCompression(value) | Συμπίεση μεγάλων δυαδικών δεδομένων στο αρχείο FBX (π.χ. δεδομένα κίνησης, σημεία ελέγχου, δεδομένα στοιχείων κορυφών, δείκτες), η προεπιλεγμένη τιμή είναι αληθής. |

 **Result:**



---


### getFoldRepeatedCurveData{#getFoldRepeatedCurveData}

| Όνομα | Περιγραφή |
| --- | --- |
| getFoldRepeatedCurveData() | Λαμβάνει ή ορίζει εάν θα επαναχρησιμοποιηθεί επαναλαμβανόμενο δεδομένο καμπύλης αυξάνοντας τον μετρητή αναφορών του τελευταίου δεδομένου· αληθής εάν θα διπλώσει τα επαναλαμβανόμενα δεδομένα καμπύλης· διαφορετικά, ψευδής. |

 **Result:**



---


### getExportLegacyMaterialProperties{#getExportLegacyMaterialProperties}

| Όνομα | Περιγραφή |
| --- | --- |
| getExportLegacyMaterialProperties() | Λαμβάνει ή ορίζει εάν θα εξαχθούν κληρονομημένες ιδιότητες υλικού, που χρησιμοποιούνται για συμβατότητα με παλαιότερες εκδόσεις. Αυτή η επιλογή είναι ενεργοποιημένη από προεπιλογή. |

 **Result:**



---


### setExportLegacyMaterialProperties{#setExportLegacyMaterialProperties}

| Όνομα | Περιγραφή |
| --- | --- |
| setExportLegacyMaterialProperties(value) | Λαμβάνει ή ορίζει εάν θα εξαχθούν κληρονομημένες ιδιότητες υλικού, που χρησιμοποιούνται για συμβατότητα με παλαιότερες εκδόσεις. Αυτή η επιλογή είναι ενεργοποιημένη από προεπιλογή. |

 **Result:**



---


### getVideoForTexture{#getVideoForTexture}

| Όνομα | Περιγραφή |
| --- | --- |
| getVideoForTexture() | Λαμβάνει ή ορίζει εάν θα δημιουργηθεί ένα αντικείμενο Video για την Υφή κατά την εξαγωγή ως FBX. |

 **Result:**



---


### setVideoForTexture{#setVideoForTexture}

| Όνομα | Περιγραφή |
| --- | --- |
| setVideoForTexture(value) | Λαμβάνει ή ορίζει εάν θα δημιουργηθεί ένα αντικείμενο Video για την Υφή κατά την εξαγωγή ως FBX. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Όνομα | Περιγραφή |
| --- | --- |
| getEmbedTextures() | Λαμβάνει ή ορίζει εάν θα ενσωματωθεί η υφή στο τελικό αρχείο εξόδου. Ο FBX Exporter θα προσπαθήσει να βρει τα ακατέργαστα δεδομένα της υφής από το FileSystem και να ενσωματώσει το αρχείο στο τελικό αρχείο FBX. Η προεπιλεγμένη τιμή είναι ψευδής. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Όνομα | Περιγραφή |
| --- | --- |
| setEmbedTextures(value) | Λαμβάνει ή ορίζει εάν θα ενσωματωθεί η υφή στο τελικό αρχείο εξόδου. Ο FBX Exporter θα προσπαθήσει να βρει τα ακατέργαστα δεδομένα της υφής από το FileSystem και να ενσωματώσει το αρχείο στο τελικό αρχείο FBX. Η προεπιλεγμένη τιμή είναι ψευδής. |

 **Result:**



---


### getGenerateVertexElementMaterial{#getGenerateVertexElementMaterial}

| Όνομα | Περιγραφή |
| --- | --- |
| getGenerateVertexElementMaterial() | Λαμβάνει ή ορίζει εάν θα δημιουργείται πάντα ένα VertexElementMaterial για γεωμετρίες εάν ο συνημμένος κόμβος περιέχει υλικά. Αυτό είναι απενεργοποιημένο από προεπιλογή. |

 **Result:**



---


### setGenerateVertexElementMaterial{#setGenerateVertexElementMaterial}

| Όνομα | Περιγραφή |
| --- | --- |
| setGenerateVertexElementMaterial(value) | Λαμβάνει ή ορίζει εάν θα δημιουργείται πάντα ένα VertexElementMaterial για γεωμετρίες εάν ο συνημμένος κόμβος περιέχει υλικά. Αυτό είναι απενεργοποιημένο από προεπιλογή. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Όνομα | Περιγραφή |
| --- | --- |
| getExportTextures() | Προσπαθήστε να αντιγράψετε τις υφές που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Όνομα | Περιγραφή |
| --- | --- |
| setExportTextures(value) | Προσπαθήστε να αντιγράψετε τις υφές που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getFileFormat() | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |

 **Result:**



---


### getEncoding{#getEncoding}

| Όνομα | Περιγραφή |
| --- | --- |
| getEncoding() | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Όνομα | Περιγραφή |
| --- | --- |
| getFileSystem() | Επιτρέπει στον χρήστη να διαχειριστεί πώς θα διαχειριστεί τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Όνομα | Περιγραφή |
| --- | --- |
| setFileSystem(value) | Επιτρέπει στον χρήστη να διαχειριστεί πώς θα διαχειριστεί τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Όνομα | Περιγραφή |
| --- | --- |
| getLookupPaths() | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο· οι διαδρομές αναζήτησης επιτρέπουν στο Aspose.3D να εντοπίζει το εξωτερικό αρχείο για φόρτωση. |

 **Result:**



---


### getFileName{#getFileName}

| Όνομα | Περιγραφή |
| --- | --- |
| getFileName() | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν σειριοποιούνται εξωτερικά περιουσιακά στοιχεία όπως το υλικό του OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Όνομα | Περιγραφή |
| --- | --- |
| setFileName(value) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν σειριοποιούνται εξωτερικά περιουσιακά στοιχεία όπως το υλικό του OBJ. |

 **Result:**



---



