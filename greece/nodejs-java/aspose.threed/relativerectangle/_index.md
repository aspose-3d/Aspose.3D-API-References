---
title: "RelativeRectangle"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

Σχετικό ορθογώνιο  Ο τύπος μεταξύ του σχετικού στοιχείου και της απόλυτης τιμής είναι:  Scale  (Reference Width) + offset  Επομένως, εάν θέλουμε να αντιπροσωπεύει μια απόλυτη τιμή, αφήστε όλα τα πεδία κλίμακας στο μηδέν και χρησιμοποιήστε τα πεδία offset αντί αυτού.


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
| constructor_overload(left, top, width, height) | Δημιουργεί ένα RelativeRectangle |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| αριστερά | Αριθμός | null |
| to | Αριθμός | null |
| widt | Αριθμός | null |
| heigh | Αριθμός | null |

 **Result:**



---


### getScaleX{#getScaleX}

| Όνομα | Περιγραφή |
| --- | --- |
| getScaleX() | Σχετική συντεταγμένη X |

 **Result:**



---


### setScaleX{#setScaleX}

| Όνομα | Περιγραφή |
| --- | --- |
| setScaleX(value) | Σχετική συντεταγμένη X |

 **Result:**



---


### getScaleY{#getScaleY}

| Όνομα | Περιγραφή |
| --- | --- |
| getScaleY() | Σχετική συντεταγμένη Y |

 **Result:**



---


### setScaleY{#setScaleY}

| Όνομα | Περιγραφή |
| --- | --- |
| setScaleY(value) | Σχετική συντεταγμένη Y |

 **Result:**



---


### getScaleWidth{#getScaleWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| getScaleWidth() | Σχετικό πλάτος |

 **Result:**



---


### setScaleWidth{#setScaleWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| setScaleWidth(value) | Σχετικό πλάτος |

 **Result:**



---


### getScaleHeight{#getScaleHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| getScaleHeight() | Σχετικό ύψος |

 **Result:**



---


### setScaleHeight{#setScaleHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| setScaleHeight(value) | Σχετικό ύψος |

 **Result:**



---


### getOffsetX{#getOffsetX}

| Όνομα | Περιγραφή |
| --- | --- |
| getOffsetX() | Λαμβάνει ή ορίζει την απόσταση για τη συντεταγμένη X |

 **Result:**



---


### setOffsetX{#setOffsetX}

| Όνομα | Περιγραφή |
| --- | --- |
| setOffsetX(value) | Λαμβάνει ή ορίζει την απόσταση για τη συντεταγμένη X |

 **Result:**



---


### getOffsetY{#getOffsetY}

| Όνομα | Περιγραφή |
| --- | --- |
| getOffsetY() | Λαμβάνει ή ορίζει την απόσταση για τη συντεταγμένη Y |

 **Result:**



---


### setOffsetY{#setOffsetY}

| Όνομα | Περιγραφή |
| --- | --- |
| setOffsetY(value) | Λαμβάνει ή ορίζει την απόσταση για τη συντεταγμένη Y |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| getOffsetWidth() | Λαμβάνει ή ορίζει την απόσταση για το πλάτος |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| setOffsetWidth(value) | Λαμβάνει ή ορίζει την απόσταση για το πλάτος |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| getOffsetHeight() | Λαμβάνει ή ορίζει την απόσταση για το ύψος |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| setOffsetHeight(value) | Λαμβάνει ή ορίζει την απόσταση για το ύψος |

 **Result:**



---


### toAbsolute{#toAbsolute}

| Όνομα | Περιγραφή |
| --- | --- |
| toAbsolute(left, top, width, height) | Μετατρέψτε το σχετικό ορθογώνιο σε απόλυτο ορθογώνιο |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| αριστερά | Αριθμός | Αριστερά του ορθογωνίου |
| επάνω | Αριθμός | Πάνω του ορθογωνίου |
| πλάτος | Αριθμός | Πλάτος του ορθογωνίου |
| height | Αριθμός | Ύψος του ορθογωνίου |

 **Result:**
Rect


---


### fromScale{#fromScale}

| Όνομα | Περιγραφή |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | Δημιουργήστε ένα RelativeRectangle με όλα τα πεδία μετατόπισης μηδέν και τα πεδία κλίμακας από τις δοθείσες παραμέτρους. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλίμακα | Αριθμός | null |
| κλίμακα | Αριθμός | null |
| scaleWidt | Αριθμός | null |
| scaleHeigh | Αριθμός | null |

 **Result:**
RelativeRectangle


---


### toString{#toString}

| Όνομα | Περιγραφή |
| --- | --- |
| toString() | Μετατρέπει την τιμή αυτού του αντικειμένου σε java.lang.String. |

 **Result:**
RelativeRectangle


---



