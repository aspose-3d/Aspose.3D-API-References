---
title: "TransformBuilder"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

Ο TransformBuilder χρησιμοποιείται για την κατασκευή πίνακα μετασχηματισμού μέσω μιας αλυσίδας μετασχηματισμών.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor(initial, order) | Δημιουργήστε ένα TransformBuilder με αρχικό πίνακα μετασχηματισμού και καθορισμένη σειρά σύνθεσης |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| initia | Matrix4 | null |
| order | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(order) | Δημιουργήστε ένα TransformBuilder με αρχικό πίνακα μετασχηματισμού ταυτότητας και καθορισμένη σειρά σύνθεσης |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| order | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| Όνομα | Περιγραφή |
| --- | --- |
| getMatrix() | Λαμβάνει ή ορίζει την τρέχουσα τιμή του πίνακα |

 **Result:**



---


### setMatrix{#setMatrix}

| Όνομα | Περιγραφή |
| --- | --- |
| setMatrix(value) | Λαμβάνει ή ορίζει την τρέχουσα τιμή του πίνακα |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| Όνομα | Περιγραφή |
| --- | --- |
| getComposeOrder() | Λαμβάνει ή ορίζει τη σειρά σύνθεσης της αλυσίδας. Η τιμή της ιδιότητας είναι η ακέραια σταθερά ComposeOrder. |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| Όνομα | Περιγραφή |
| --- | --- |
| setComposeOrder(value) | Λαμβάνει ή ορίζει τη σειρά σύνθεσης της αλυσίδας. Η τιμή της ιδιότητας είναι η ακέραια σταθερά ComposeOrder. |

 **Result:**



---


### compose{#compose}

| Όνομα | Περιγραφή |
| --- | --- |
| compose(m) | Προσθέστε ή τοποθετήστε στην αρχή το όρισμα στον εσωτερικό πίνακα. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| Όνομα | Περιγραφή |
| --- | --- |
| append(m) | Προσθέστε τον νέο πίνακα μετασχηματισμού στην αλυσίδα μετασχηματισμού. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| Όνομα | Περιγραφή |
| --- | --- |
| prepend(m) | Προσθέστε το νέο πίνακα μετασχηματισμού στην αλυσίδα μετασχηματισμών. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| Όνομα | Περιγραφή |
| --- | --- |
| rearrange(newX, newY, newZ) | Αναδιατάξτε τη διάταξη του άξονα. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| newX | Άξονας | Άξονας |
| newY | Άξονας | Άξονας |
| newZ | Άξονας | Άξονας |

 **Result:**



---


### scale{#scale}

| Όνομα | Περιγραφή |
| --- | --- |
| scale(s) | Συνδέστε έναν πίνακα κλιμακωτικού μετασχηματισμού με ένα στοιχείο κλιμακωμένο κατά s |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | Αριθμός | null |

 **Result:**



---


### scale{#scale}

| Όνομα | Περιγραφή |
| --- | --- |
| scale(x, y, z) | Συνδέστε έναν πίνακα κλιμακωτικού μετασχηματισμού |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | Αριθμός | null |
|  | Αριθμός | null |
|  | Αριθμός | null |

 **Result:**



---


### scale{#scale}

| Όνομα | Περιγραφή |
| --- | --- |
| scale(s) | Συνδέστε έναν κλιμακωτικό μετασχηματισμό |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Όνομα | Περιγραφή |
| --- | --- |
| rotateDegree(angle, axis) | Συνδέστε έναν περιστροφικό μετασχηματισμό σε μοίρες |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | Αριθμός | Η γωνία περιστροφής σε μοίρες |
| άξονας | Vector3 | Ο άξονας περιστροφής |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Όνομα | Περιγραφή |
| --- | --- |
| rotateRadian(angle, axis) | Συνδέστε έναν περιστροφικό μετασχηματισμό σε ακτίνια |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | Αριθμός | Η γωνία περιστροφής σε ακτίνια |
| άξονας | Vector3 | Ο άξονας περιστροφής |

 **Result:**



---


### rotate{#rotate}

| Όνομα | Περιγραφή |
| --- | --- |
| rotate(q) | Συνδέστε μια περιστροφή με quaternion |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | Τεταρτοδικό | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| Όνομα | Περιγραφή |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | Συνδέστε μια περιστροφή με γωνίες Euler σε μοίρες |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| deg | Αριθμός | null |
| deg | Αριθμός | null |
| deg | Αριθμός | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Όνομα | Περιγραφή |
| --- | --- |
| rotateEulerRadian(x, y, z) | Συνδέστε μια περιστροφή με γωνίες Euler σε ακτίνια |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | Αριθμός | null |
|  | Αριθμός | null |
|  | Αριθμός | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Όνομα | Περιγραφή |
| --- | --- |
| rotateEulerRadian(r) | Συνδέστε μια περιστροφή με γωνίες Euler σε ακτίνια |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| Όνομα | Περιγραφή |
| --- | --- |
| translate(tx, ty, tz) | Συνδέστε έναν μετασχηματισμό μετάφρασης |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| t | Αριθμός | null |
| t | Αριθμός | null |
| t | Αριθμός | null |

 **Result:**



---


### translate{#translate}

| Όνομα | Περιγραφή |
| --- | --- |
| translate(v) | Συνδέστε έναν μετασχηματισμό μετάφρασης |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| Όνομα | Περιγραφή |
| --- | --- |
| reset() | Επαναφέρετε τον μετασχηματισμό στον μοναδιαίο πίνακα |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Όνομα | Περιγραφή |
| --- | --- |
| rotateDegree(rot, order) | Προσθέστε περιστροφή με καθορισμένη σειρά |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| rot | Vector3 | Περιστροφή σε μοίρες |
| order | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Όνομα | Περιγραφή |
| --- | --- |
| rotateRadian(rot, order) | Προσθέστε περιστροφή με καθορισμένη σειρά |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| rot | Vector3 | Περιστροφή σε ακτίνια |
| order | RotationOrder | RotationOrder |

 **Result:**



---



