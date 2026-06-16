---
title: "UsdSaveOptions"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

Αποθήκευση επιλογών για μορφές USD/USDZ.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor() | Αρχικοποιήστε ένα νέο UsdSaveOptions με μορφή FileFormat.USD |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(fileFormat) | Αρχικοποιήστε ένα νέο UsdSaveOptions με την καθορισμένη μορφή USD/USDZ. |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| Όνομα | Περιγραφή |
| --- | --- |
| getPrimitiveToMesh() | Μετατρέπει τις πρωτόγονες οντότητες σε πλέγμα κατά την εξαγωγή. Ή κωδικοποιεί άμεσα τις πρωτόγονες στο αρχείο εξόδου (θα χρησιμοποιήσει τον ορισμό επέκτασης της Aspose για ανεπίσημες πρωτόγονες όπως Dish, Torus). Η προεπιλεγμένη τιμή είναι true. |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| Όνομα | Περιγραφή |
| --- | --- |
| setPrimitiveToMesh(value) | Μετατρέπει τις πρωτόγονες οντότητες σε πλέγμα κατά την εξαγωγή. Ή κωδικοποιεί άμεσα τις πρωτόγονες στο αρχείο εξόδου (θα χρησιμοποιήσει τον ορισμό επέκτασης της Aspose για ανεπίσημες πρωτόγονες όπως Dish, Torus). Η προεπιλεγμένη τιμή είναι true. |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| Όνομα | Περιγραφή |
| --- | --- |
| getExportMetaData() | Εξάγει τις ιδιότητες του κόμβου μέσω του πεδίου customData του USD. |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| Όνομα | Περιγραφή |
| --- | --- |
| setExportMetaData(value) | Εξάγει τις ιδιότητες του κόμβου μέσω του πεδίου customData του USD. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Όνομα | Περιγραφή |
| --- | --- |
| getMaterialConverter() | Προσαρμοσμένος μετατροπέας για τη μετατροπή του υλικού της γεωμετρίας σε υλικό PBR. Εάν δεν έχει οριστεί, ο εξαγωγέας USD θα μετατρέψει αυτόματα το τυπικό υλικό σε υλικό PBR. Η προεπιλεγμένη τιμή είναι null |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Όνομα | Περιγραφή |
| --- | --- |
| setMaterialConverter(value) | Προσαρμοσμένος μετατροπέας για τη μετατροπή του υλικού της γεωμετρίας σε υλικό PBR. Εάν δεν έχει οριστεί, ο εξαγωγέας USD θα μετατρέψει αυτόματα το τυπικό υλικό σε υλικό PBR. Η προεπιλεγμένη τιμή είναι null |

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



