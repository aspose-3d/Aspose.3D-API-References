---
title: "PushConstant"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/pushconstant/
---
## PushConstant class

Μία βοηθητική λειτουργία για την παροχή δεδομένων στον shader μέσω push constant.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor() | Κατασκευαστής του PushConstant |

 **Result:**



---


### write{#write}

| Όνομα | Περιγραφή |
| --- | --- |
| write(mat) | Γράψτε τη μήτρα στην σταθερά |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| mat | FMatrix4 | Η μήτρα προς εγγραφή |

 **Result:**



---


### write{#write}

| Όνομα | Περιγραφή |
| --- | --- |
| write(n) | Γράψτε μια τιμή int στην σταθερά |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | Αριθμός | null |

 **Result:**



---


### write{#write}

| Όνομα | Περιγραφή |
| --- | --- |
| write(f) | Γράψτε μια τιμή float στην σταθερά |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | Αριθμός | null |

 **Result:**



---


### write{#write}

| Όνομα | Περιγραφή |
| --- | --- |
| write(vec) | Γράψτε ένα διάνυσμα 4-συνιστωσών στην σταθερά |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| ve | FVector4 | null |

 **Result:**



---


### write{#write}

| Όνομα | Περιγραφή |
| --- | --- |
| write(vec) | Γράψτε ένα διάνυσμα 3-συνιστωσών στην σταθερά |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| ve | FVector3 | null |

 **Result:**



---


### write{#write}

| Όνομα | Περιγραφή |
| --- | --- |
| write(x, y, z, w) | Γράψτε ένα διάνυσμα 4-συνιστωσών στην σταθερά |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | Αριθμός | null |
|  | Αριθμός | null |
|  | Αριθμός | null |
|  | Αριθμός | null |

 **Result:**



---


### commit{#commit}

| Όνομα | Περιγραφή |
| --- | --- |
| commit(stage, commandList) | Καταχωρήστε τα προετοιμασμένα δεδομένα στην pipeline γραφικών. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stage | Αριθμός | ShaderStage |
| commandLis | ICommandList | null |

 **Result:**



---



