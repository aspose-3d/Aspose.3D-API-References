---
title: "MemoryFileSystem"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

Το MemoryFileSystem θα χαρτογραφήσει τις λειτουργίες ανάγνωσης/εγγραφής στη μνήμη.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| Όνομα | Περιγραφή |
| --- | --- |
| getFileNames() | Ονόματα αρχείων που βρίσκονται σε αυτό το σύστημα αρχείων μνήμης. |

 **Result:**



---


### getFileContent{#getFileContent}

| Όνομα | Περιγραφή |
| --- | --- |
| getFileContent(fileName) | Επιστρέφει το ακατέργαστο περιεχόμενο του συγκεκριμένου αρχείου. Εναίρεται System.IO.FileNotFoundException εάν το συγκεκριμένο αρχείο δεν υπάρχει. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| Όνομα | Περιγραφή |
| --- | --- |
| readFile(fileName, options) | Δημιουργήστε μια ροή για την ανάγνωση εξαρτήσεων. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileNam | String | null |
| επιλογή | IOConfig | null |

 **Result:**
Ροή


---


### writeFile{#writeFile}

| Όνομα | Περιγραφή |
| --- | --- |
| writeFile(fileName, options) | Δημιουργήστε μια ροή για την εγγραφή εξαρτήσεων. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileNam | String | null |
| επιλογή | IOConfig | null |

 **Result:**
Ροή


---



