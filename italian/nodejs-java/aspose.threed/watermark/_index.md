---
title: "Watermark"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/watermark/
---
## Watermark class

Utility per codificare/decodificare watermark cieco da/a una mesh.  @hideconstructor


## Metodi

### encodeWatermark{#encodeWatermark}

| Nome | Descrizione |
| --- | --- |
| encodeWatermark(input, text) | Codifica un testo nel watermark cieco della mesh. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| input | Mesh | Mesh per codificare un watermark cieco |
| text | Stringa | Testo da codificare nella mesh |

 **Result:**
Mesh


---


### encodeWatermark{#encodeWatermark}

| Nome | Descrizione |
| --- | --- |
| encodeWatermark(input, text, password) | Codifica un testo nel watermark cieco della mesh. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| input | Mesh | Mesh per codificare un watermark cieco |
| text | Stringa | Testo da codificare nella mesh |
| password | Stringa | Password per proteggere il watermark, è opzionale |

 **Result:**
Mesh


---


### decodeWatermark{#decodeWatermark}

| Nome | Descrizione |
| --- | --- |
| decodeWatermark(input) | Decodifica il watermark da una mesh |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| input | Mesh | La mesh da cui estrarre il watermark |

 **Result:**
Stringa


---


### decodeWatermark{#decodeWatermark}

| Nome | Descrizione |
| --- | --- |
| decodeWatermark(input, password) | Decodifica il watermark da una mesh |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| input | Mesh | La mesh da cui estrarre il watermark |
| password | Stringa | La password per decifrare il watermark |

 **Result:**
Stringa


---



