---
title: "Watermark"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/watermark/
---
## Watermark class

Utility per codificare/decodificare un watermark cieco da/a una mesh.  @hideconstructor


## Metodi

### encodeWatermark{#encodeWatermark}

| Nome | Descrizione |
| --- | --- |
| encodeWatermark(input, text) | Codifica un testo in un watermark cieco della mesh. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| input | Mesh | Mesh per codificare un watermark cieco |
| text | String | Testo da codificare nella mesh |

 **Result:**
Mesh


---


### encodeWatermark{#encodeWatermark}

| Nome | Descrizione |
| --- | --- |
| encodeWatermark(input, text, password) | Codifica un testo in un watermark cieco della mesh. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| input | Mesh | Mesh per codificare un watermark cieco |
| text | String | Testo da codificare nella mesh |
| password | String | Password per proteggere il watermark, è opzionale |

 **Result:**
Mesh


---


### decodeWatermark{#decodeWatermark}

| Nome | Descrizione |
| --- | --- |
| decodeWatermark(input) | Decodifica la filigrana da una mesh |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| input | Mesh | La mesh per estrarre la filigrana |

 **Result:**
String


---


### decodeWatermark{#decodeWatermark}

| Nome | Descrizione |
| --- | --- |
| decodeWatermark(input, password) | Decodifica la filigrana da una mesh |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| input | Mesh | La mesh per estrarre la filigrana |
| password | String | La password per decifrare la filigrana |

 **Result:**
String


---



