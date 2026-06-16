---
title: "GltfSaveOptions"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

Επιλογές αποθήκευσης για μορφή glTF.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor(contentType) | Κατασκευαστής του GltfSaveOptions |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(format) | Κατασκευαστής του GltfSaveOptions |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| μορφή | FileFormat | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| Όνομα | Περιγραφή |
| --- | --- |
| getPrettyPrint() | Το περιεχόμενο JSON του αρχείου GLTF είναι μορφοποιημένο με εσοχές για ανθρώπινη ανάγνωση· η προεπιλεγμένη τιμή είναι false |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| Όνομα | Περιγραφή |
| --- | --- |
| setPrettyPrint(value) | Το περιεχόμενο JSON του αρχείου GLTF είναι μορφοποιημένο με εσοχές για ανθρώπινη ανάγνωση· η προεπιλεγμένη τιμή είναι false |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| Όνομα | Περιγραφή |
| --- | --- |
| getFallbackNormal() | Όταν ο εξαγωγέας GLTF2 εντοπίσει ένα μη έγκυρο κανονικό διάνυσμα, αυτό θα χρησιμοποιηθεί αντί της αρχικής τιμής του για παράκαμψη της επικύρωσης. Η προεπιλεγμένη τιμή είναι (0, 1, 0) |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| Όνομα | Περιγραφή |
| --- | --- |
| getEmbedAssets() | Ενσωματώστε όλα τα εξωτερικά περιουσιακά στοιχεία ως base64 σε ένα ενιαίο αρχείο σε λειτουργία ASCII· η προεπιλεγμένη τιμή είναι false. |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| Όνομα | Περιγραφή |
| --- | --- |
| setEmbedAssets(value) | Ενσωματώστε όλα τα εξωτερικά περιουσιακά στοιχεία ως base64 σε ένα ενιαίο αρχείο σε λειτουργία ASCII· η προεπιλεγμένη τιμή είναι false. |

 **Result:**



---


### getImageFormat{#getImageFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getImageFormat() | Το πρότυπο glTF υποστηρίζει μόνο PNG/JPG ως μορφή υφής, αυτή η επιλογή θα καθοδηγήσει πώς το Aspose.3D μετατρέπει τις μη τυπικές εικόνες σε υποστηριζόμενη μορφή κατά την εξαγωγή. Η προεπιλεγμένη τιμή είναι GltfEmbeddedImageFormat.PNG Η τιμή της ιδιότητας είναι η ακέραια σταθερά GltfEmbeddedImageFormat. |

 **Result:**



---


### setImageFormat{#setImageFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| setImageFormat(value) | Το πρότυπο glTF υποστηρίζει μόνο PNG/JPG ως μορφή υφής, αυτή η επιλογή θα καθοδηγήσει πώς το Aspose.3D μετατρέπει τις μη τυπικές εικόνες σε υποστηριζόμενη μορφή κατά την εξαγωγή. Η προεπιλεγμένη τιμή είναι GltfEmbeddedImageFormat.PNG Η τιμή της ιδιότητας είναι η ακέραια σταθερά GltfEmbeddedImageFormat. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Όνομα | Περιγραφή |
| --- | --- |
| getMaterialConverter() | Προσαρμοσμένος μετατροπέας για τη μετατροπή του υλικού της γεωμετρίας σε υλικό PBR. Εάν αυτό δεν έχει οριστεί, ο εξαγωγέας glTF 2.0 θα μετατρέπει αυτόματα το τυπικό υλικό σε υλικό PBR. Η προεπιλεγμένη τιμή είναι null. Αυτή η ιδιότητα χρησιμοποιείται κατά την εξαγωγή μιας σκηνής σε αρχείο glTF 2.0. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Όνομα | Περιγραφή |
| --- | --- |
| setMaterialConverter(value) | Προσαρμοσμένος μετατροπέας για τη μετατροπή του υλικού της γεωμετρίας σε υλικό PBR. Εάν αυτό δεν έχει οριστεί, ο εξαγωγέας glTF 2.0 θα μετατρέπει αυτόματα το τυπικό υλικό σε υλικό PBR. Η προεπιλεγμένη τιμή είναι null. Αυτή η ιδιότητα χρησιμοποιείται κατά την εξαγωγή μιας σκηνής σε αρχείο glTF 2.0. |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| Όνομα | Περιγραφή |
| --- | --- |
| getUseCommonMaterials() | Σειριοποίηση υλικών χρησιμοποιώντας τις επεκτάσεις υλικού KHR common, η προεπιλεγμένη τιμή είναι false. Ο ορισμός αυτού σε false θα προκαλέσει το Aspose.3D να εξάγει ένα σύνολο shader κορυφής/κατακερματισμού εάν #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| Όνομα | Περιγραφή |
| --- | --- |
| setUseCommonMaterials(value) | Σειριοποίηση υλικών χρησιμοποιώντας τις επεκτάσεις υλικού KHR common, η προεπιλεγμένη τιμή είναι false. Ο ορισμός αυτού σε false θα προκαλέσει το Aspose.3D να εξάγει ένα σύνολο shader κορυφής/κατακερματισμού εάν #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| Όνομα | Περιγραφή |
| --- | --- |
| getExternalDracoEncoder() | Χρησιμοποιήστε εξωτερικό κωδικοποιητή draco για να επιταχύνετε την ταχύτητα συμπίεσης draco. Το Aspose.3D θα δημιουργήσει μια νέα υποδιαδικασία για την κωδικοποίηση του πλέγματος σε μορφή draco, χρησιμοποιήστε το με δική σας ευθύνη. |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| Όνομα | Περιγραφή |
| --- | --- |
| setExternalDracoEncoder(value) | Χρησιμοποιήστε εξωτερικό κωδικοποιητή draco για να επιταχύνετε την ταχύτητα συμπίεσης draco. Το Aspose.3D θα δημιουργήσει μια νέα υποδιαδικασία για την κωδικοποίηση του πλέγματος σε μορφή draco, χρησιμοποιήστε το με δική σας ευθύνη. |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| Όνομα | Περιγραφή |
| --- | --- |
| getFlipTexCoordV() | Αναστροφή του συντελεστή συντεταγμένης υφής v(t), η προεπιλεγμένη τιμή είναι true. |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| Όνομα | Περιγραφή |
| --- | --- |
| setFlipTexCoordV(value) | Αναστροφή του συντελεστή συντεταγμένης υφής v(t), η προεπιλεγμένη τιμή είναι true. |

 **Result:**



---


### getBufferFile{#getBufferFile}

| Όνομα | Περιγραφή |
| --- | --- |
| getBufferFile() | Το όνομα αρχείου του εξωτερικού αρχείου buffer που χρησιμοποιείται για την αποθήκευση δυαδικών δεδομένων. Εάν αυτό το αρχείο δεν καθοριστεί, το Aspose.3D θα δημιουργήσει ένα όνομα για εσάς. Αυτό αγνοείται όταν εξάγετε glTF σε δυαδική λειτουργία. |

 **Result:**



---


### setBufferFile{#setBufferFile}

| Όνομα | Περιγραφή |
| --- | --- |
| setBufferFile(value) | Το όνομα αρχείου του εξωτερικού αρχείου buffer που χρησιμοποιείται για την αποθήκευση δυαδικών δεδομένων. Εάν αυτό το αρχείο δεν καθοριστεί, το Aspose.3D θα δημιουργήσει ένα όνομα για εσάς. Αυτό αγνοείται όταν εξάγετε glTF σε δυαδική λειτουργία. |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| Όνομα | Περιγραφή |
| --- | --- |
| getSaveExtras() | Αποθηκεύστε τις δυναμικές ιδιότητες του αντικειμένου σκηνής στα πεδία 'extra' στο παραγόμενο αρχείο glTF. Αυτό είναι χρήσιμο για την παροχή δεδομένων ειδικών για την εφαρμογή. Η προεπιλεγμένη τιμή είναι false. |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| Όνομα | Περιγραφή |
| --- | --- |
| setSaveExtras(value) | Αποθηκεύστε τις δυναμικές ιδιότητες του αντικειμένου σκηνής στα πεδία 'extra' στο παραγόμενο αρχείο glTF. Αυτό είναι χρήσιμο για την παροχή δεδομένων ειδικών για την εφαρμογή. Η προεπιλεγμένη τιμή είναι false. |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| Όνομα | Περιγραφή |
| --- | --- |
| getApplyUnitScale() | Εφαρμόστε το AssetInfo.UnitScaleFactor στο πλέγμα. Η προεπιλεγμένη τιμή είναι false. |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| Όνομα | Περιγραφή |
| --- | --- |
| setApplyUnitScale(value) | Εφαρμόστε το AssetInfo.UnitScaleFactor στο πλέγμα. Η προεπιλεγμένη τιμή είναι false. |

 **Result:**



---


### getDracoCompression{#getDracoCompression}

| Όνομα | Περιγραφή |
| --- | --- |
| getDracoCompression() | Λαμβάνει ή ορίζει εάν θα ενεργοποιηθεί η συμπίεση draco |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| Όνομα | Περιγραφή |
| --- | --- |
| setDracoCompression(value) | Λαμβάνει ή ορίζει εάν θα ενεργοποιηθεί η συμπίεση draco |

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



