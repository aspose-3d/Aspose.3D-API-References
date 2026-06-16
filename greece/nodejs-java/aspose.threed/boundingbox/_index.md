---
title: "BoundingBox"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

Το πλαίσιο περιβάλλοντος ευθυγραμμισμένο με τους άξονες


## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| NULL | Το μηδενικό πλαίσιο οριοθέτησης |
| INFINITE | Το άπειρο πλαίσιο οριοθέτησης |

## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(minimum, maximum) | Αρχικοποιεί ένα πεπερασμένο πλαίσιο οριοθέτησης με δεδομένες γωνίες ελάχιστο και μέγιστο |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| ελάχιστο | Vector3 | Η ελάχιστη γωνία |
| μέγιστο | Vector3 | Η μέγιστη γωνία |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | Αρχικοποιεί ένα πεπερασμένο πλαίσιο οριοθέτησης με δεδομένες γωνίες ελάχιστο και μέγιστο |

 **Result:**



---


### getExtent{#getExtent}

| Όνομα | Περιγραφή |
| --- | --- |
| getExtent() | Λαμβάνει την έκταση του πλαισίου οριοθέτησης. Η τιμή της ιδιότητας είναι η ακέραια σταθερά BoundingBoxExtent. |

 **Result:**



---


### getMinimum{#getMinimum}

| Όνομα | Περιγραφή |
| --- | --- |
| getMinimum() | Η ελάχιστη γωνία του πλαισίου οριοθέτησης |

 **Result:**



---


### getMaximum{#getMaximum}

| Όνομα | Περιγραφή |
| --- | --- |
| getMaximum() | Η μέγιστη γωνία του πλαισίου οριοθέτησης |

 **Result:**



---


### getSize{#getSize}

| Όνομα | Περιγραφή |
| --- | --- |
| getSize() | Το μέγεθος του περιοριστικού πλαισίου |

 **Result:**



---


### getCenter{#getCenter}

| Όνομα | Περιγραφή |
| --- | --- |
| getCenter() | Το κέντρο του περιοριστικού πλαισίου. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Όνομα | Περιγραφή |
| --- | --- |
| fromGeometry(geometry) | Δημιουργήστε ένα περιοριστικό πλαίσιο από τη δοσμένη γεωμετρία |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| geometr | Geometry | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| Όνομα | Περιγραφή |
| --- | --- |
| toString() | Λαμβάνει την αναπαράσταση συμβολοσειράς του πλαισίου οριοθέτησης. |

 **Result:**
String


---


### hashCode{#hashCode}

| Όνομα | Περιγραφή |
| --- | --- |
| hashCode() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |

 **Result:**
Αριθμός


---


### equals{#equals}

| Όνομα | Περιγραφή |
| --- | --- |
| equals(obj) | Καθορίζει αν δύο αντικείμενα είναι ίσα |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| ob | Αντικείμενο | null |

 **Result:**
boolean


---



