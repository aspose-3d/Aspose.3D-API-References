---
title: "BoundingBox2D"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

Το πλαίσιο περιβάλλοντος ευθυγραμμισμένο με άξονες για Vector2


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
| ελάχιστο | Vector2 | Η ελάχιστη γωνία |
| μέγιστο | Vector2 | Η μέγιστη γωνία |

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


### merge{#merge}

| Όνομα | Περιγραφή |
| --- | --- |
| merge(pt) | Συγχωνεύει το νέο πλαίσιο στο τρέχον πλαίσιο οριοθέτησης. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| Όνομα | Περιγραφή |
| --- | --- |
| merge(bb) | Συγχωνεύει το νέο πλαίσιο στο τρέχον πλαίσιο οριοθέτησης. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| Όνομα | Περιγραφή |
| --- | --- |
| toString() | Λαμβάνει την αναπαράσταση συμβολοσειράς του πλαισίου οριοθέτησης. |

 **Result:**
String


---



