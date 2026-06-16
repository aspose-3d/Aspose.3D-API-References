---
title: "TextureData"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

Αυτή η κλάση περιέχει τα ακατέργαστα δεδομένα και τον ορισμό μορφής μιας υφής.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | Κατασκευαστής του TextureData |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| widt | Αριθμός | null |
| heigh | Αριθμός | null |
| strid | Αριθμός | null |
| bytesPerPixe | Αριθμός | null |
| pixelFormat | PixelFormat | PixelFormat |
| dat | byte[] | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | Δημιουργεί ένα νέο TextureData και κατανέμει δεδομένα εικονοστοιχείων. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| widt | Αριθμός | null |
| heigh | Αριθμός | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload2() | Κατασκευαστής του TextureData |

 **Result:**



---


### getData{#getData}

| Όνομα | Περιγραφή |
| --- | --- |
| getData() | Ακατέργαστα bytes δεδομένων εικονοστοιχείων. |

 **Result:**



---


### getWidth{#getWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| getWidth() | Αριθμός οριζόντιων εικονοστοιχείων. |

 **Result:**



---


### getHeight{#getHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| getHeight() | Αριθμός κάθετων εικονοστοιχείων. |

 **Result:**



---


### getStride{#getStride}

| Όνομα | Περιγραφή |
| --- | --- |
| getStride() | Αριθμός byte μιας γραμμής σάρωσης. |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| Όνομα | Περιγραφή |
| --- | --- |
| getBytesPerPixel() | Αριθμός byte ενός εικονοστοιχείου. |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getPixelFormat() | Η μορφή του εικονοστοιχείου. Η τιμή της ιδιότητας είναι η ακέραια σταθερά PixelFormat. |

 **Result:**



---


### fromFile{#fromFile}

| Όνομα | Περιγραφή |
| --- | --- |
| fromFile(fileName) | Φορτώνει μια υφή από αρχείο |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
TextureData


---


### save{#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save(fileName) | Αποθήκευση δεδομένων υφής σε αρχείο εικόνας |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Το όνομα αρχείου όπου θα αποθηκευτεί η εικόνα. |

 **Result:**
TextureData


---


### save{#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save(fileName, format) | Αποθήκευση δεδομένων υφής σε αρχείο εικόνας |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Το όνομα αρχείου όπου θα αποθηκευτεί η εικόνα. |
| format | String | Μορφή εικόνας του αρχείου εξόδου. |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| Όνομα | Περιγραφή |
| --- | --- |
| mapPixels(mapMode) | Αντιστοίχηση όλων των pixel για ανάγνωση/εγγραφή |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Όνομα | Περιγραφή |
| --- | --- |
| mapPixels(mapMode, format) | Αντιστοίχηση όλων των pixel για ανάγνωση/εγγραφή στη δεδομένη μορφή pixel |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Όνομα | Περιγραφή |
| --- | --- |
| mapPixels(rect, mapMode, format) | Αντιστοίχηση pixel που προσδιορίζονται από το rect για ανάγνωση/εγγραφή στη δεδομένη μορφή pixel |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | Rect | Η περιοχή των pixel που θα προσπελαστεί |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| transformPixelFormat(pixelFormat) | Μετασχηματισμός της διάταξης του pixel σε νέα μορφή pixel. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



