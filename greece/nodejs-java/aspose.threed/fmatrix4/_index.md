---
title: "FMatrix4"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

Μήτρα 4x4 με όλα τα στοιχεία τύπου float


## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| m00 | Το m00. |
| m01 | Το m01. |
| m02 | Το m02. |
| m03 | Το m03. |
| m10 | Το m10. |
| m11 | Το m11. |
| m12 | Το m12. |
| m13 | Το m13. |
| m20 | Το m20. |
| m21 | Το m21. |
| m22 | Το m22. |
| m23 | Το m23. |
| m30 | Το m30. |
| m31 | Το m31. |
| m32 | Το m32. |
| m33 | Το m33. |
| IDENTITY | Ο πίνακας ταυτότητας |

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
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Αρχικοποιήστε την παρουσία του FMatrix4 |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| m0 | Αριθμός | null |
| m0 | Αριθμός | null |
| m0 | Αριθμός | null |
| m0 | Αριθμός | null |
| m1 | Αριθμός | null |
| m1 | Αριθμός | null |
| m1 | Αριθμός | null |
| m1 | Αριθμός | null |
| m2 | Αριθμός | null |
| m2 | Αριθμός | null |
| m2 | Αριθμός | null |
| m2 | Αριθμός | null |
| m3 | Αριθμός | null |
| m3 | Αριθμός | null |
| m3 | Αριθμός | null |
| m3 | Αριθμός | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload2(mat) | Αρχικοποιήστε το αντικείμενο FMatrix4 από ένα αντικείμενο Matrix4. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | Δημιουργεί πίνακα από 4 σειρές. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| Όνομα | Περιγραφή |
| --- | --- |
| concatenate(m2) | Συνενώνει τους δύο πίνακες |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


---


### concatenate{#concatenate}

| Όνομα | Περιγραφή |
| --- | --- |
| concatenate(m2) | Συνενώνει τους δύο πίνακες |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
FMatrix4


---


### transpose{#transpose}

| Όνομα | Περιγραφή |
| --- | --- |
| transpose() | Μετατρέπει αυτήν την παρουσία. |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| Όνομα | Περιγραφή |
| --- | --- |
| inverse() | Υπολογίστε τον αντίστροφο πίνακα του τρέχοντος αντικειμένου. |

 **Result:**
FMatrix4


---



