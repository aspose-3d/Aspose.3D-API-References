---
title: "VertexDeclaration"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/vertexdeclaration/
---
## VertexDeclaration class

Η δήλωση της δομής μιας προσαρμοσμένης κορυφής


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getSealed{#getSealed}

| Όνομα | Περιγραφή |
| --- | --- |
| getSealed() | Ένα VertexDeclaration θα σφραγιστεί όταν έχει χρησιμοποιηθεί από com.aspose.threed.TriMesh`1 ή TriMesh, δεν επιτρέπονται περαιτέρω τροποποιήσεις. |

 **Result:**



---


### getCount{#getCount}

| Όνομα | Περιγραφή |
| --- | --- |
| getCount() | Λαμβάνει τον αριθμό όλων των πεδίων που ορίζονται σε αυτό το VertexDeclaration |

 **Result:**



---


### getSize{#getSize}

| Όνομα | Περιγραφή |
| --- | --- |
| getSize() | Το μέγεθος σε byte της δομής κορυφής. |

 **Result:**



---


### get{#get}

| Όνομα | Περιγραφή |
| --- | --- |
| get(index) |  |

 **Result:**



---


### clear{#clear}

| Όνομα | Περιγραφή |
| --- | --- |
| clear() | Καθαρίστε όλα τα πεδία. |

 **Result:**



---


### addField{#addField}

| Όνομα | Περιγραφή |
| --- | --- |
| addField(dataType, semantic, index, alias) | Προσθέστε ένα νέο πεδίο κορυφής |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataType | Αριθμός | VertexFieldDataType |
| semantic | VertexFieldSemantic | VertexFieldSemantic |
| index | Αριθμός | Ο δείκτης για το ίδιο semantic πεδίου, -1 για αυτόματη δημιουργία |
| alias | String | Το όνομα alias του πεδίου |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Όνομα | Περιγραφή |
| --- | --- |
| fromGeometry(geometry, useFloat) | Δημιουργήστε ένα VertexDeclaration βασισμένο στη διάταξη ενός Geometry. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| geometr | Geometry | null |
| useFloat | boolean | Χρησιμοποιήστε float αντί για τύπο double |

 **Result:**
VertexDeclaration


---


### compareTo{#compareTo}

| Όνομα | Περιγραφή |
| --- | --- |
| compareTo(other) | Συγκρίνει αυτή την παρουσία με ένα καθορισμένο αντικείμενο και επιστρέφει ένδειξη των σχετικών τιμών τους. |

 **Result:**
VertexDeclaration


---


### toString{#toString}

| Όνομα | Περιγραφή |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### hashCode{#hashCode}

| Όνομα | Περιγραφή |
| --- | --- |
| hashCode() |  |

 **Result:**
Αριθμός


---


### equals{#equals}

| Όνομα | Περιγραφή |
| --- | --- |
| equals(obj) | Καθορίζει εάν αυτή η παρουσία και ένα καθορισμένο αντικείμενο, το οποίο πρέπει επίσης να είναι αντικείμενο VertexDeclaration, έχουν την ίδια τιμή. |

 **Result:**
Αριθμός


---


### iterator{#iterator}

| Όνομα | Περιγραφή |
| --- | --- |
| iterator() | Δεσμευμένο για εσωτερική χρήση. |

 **Result:**
Αριθμός


---



