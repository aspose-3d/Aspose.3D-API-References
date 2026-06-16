---
title: "Watermark"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/watermark/
---
## Watermark class

Εργαλείο για κωδικοποίηση/αποκωδικοποίηση τυφλού υδατογραφήματος σε/από ένα πλέγμα.  @hideconstructor


## Μέθοδοι

### encodeWatermark{#encodeWatermark}

| Όνομα | Περιγραφή |
| --- | --- |
| encodeWatermark(input, text) | Κωδικοποιήστε ένα κείμενο σε τυφλό υδατογράφημα πλέγματος. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | Πλέγμα | Πλέγμα για κωδικοποίηση τυφλού υδατογραφήματος |
| text | String | Κείμενο για κωδικοποίηση στο πλέγμα |

 **Result:**
Πλέγμα


---


### encodeWatermark{#encodeWatermark}

| Όνομα | Περιγραφή |
| --- | --- |
| encodeWatermark(input, text, password) | Κωδικοποιήστε ένα κείμενο σε τυφλό υδατογράφημα πλέγματος. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | Πλέγμα | Πλέγμα για κωδικοποίηση τυφλού υδατογραφήματος |
| text | String | Κείμενο για κωδικοποίηση στο πλέγμα |
| password | String | Κωδικός πρόσβασης για προστασία του υδατογραφήματος, είναι προαιρετικός |

 **Result:**
Πλέγμα


---


### decodeWatermark{#decodeWatermark}

| Όνομα | Περιγραφή |
| --- | --- |
| decodeWatermark(input) | Αποκωδικοποίηση του υδατογραφήματος από ένα πλέγμα |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | Πλέγμα | Το πλέγμα για εξαγωγή του υδατογραφήματος |

 **Result:**
String


---


### decodeWatermark{#decodeWatermark}

| Όνομα | Περιγραφή |
| --- | --- |
| decodeWatermark(input, password) | Αποκωδικοποίηση του υδατογραφήματος από ένα πλέγμα |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | Πλέγμα | Το πλέγμα για εξαγωγή του υδατογραφήματος |
| password | String | Ο κωδικός πρόσβασης για αποκρυπτογράφηση του υδατογραφήματος |

 **Result:**
String


---



