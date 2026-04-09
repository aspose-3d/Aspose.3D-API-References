---
title: Watermark
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/watermark/
---
## Watermark class

Dienstprogramm zum Codieren/Dekodieren eines Blindwasserzeichens in/aus einem Mesh.  @hideconstructor


## Methoden

### encodeWatermark{#encodeWatermark}

| Name | Beschreibung |
| --- | --- |
| encodeWatermark(input, text) | Kodieren Sie einen Text in das blinde Wasserzeichen des Meshes. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| input | Mesh | Mesh zum Kodieren eines blinden Wasserzeichens |
| Text | String | Text zum Kodieren in das Mesh |

 **Result:**
Mesh


---


### encodeWatermark{#encodeWatermark}

| Name | Beschreibung |
| --- | --- |
| encodeWatermark(input, text, password) | Kodieren Sie einen Text in das blinde Wasserzeichen des Meshes. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| input | Mesh | Mesh zum Kodieren eines blinden Wasserzeichens |
| Text | String | Text zum Kodieren in das Mesh |
| Passwort | String | Passwort zum Schutz des Wasserzeichens, optional |

 **Result:**
Mesh


---


### decodeWatermark{#decodeWatermark}

| Name | Beschreibung |
| --- | --- |
| decodeWatermark(input) | Dekodiere das Wasserzeichen aus einem Mesh |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| input | Mesh | Das Mesh zum Extrahieren des Wasserzeichens |

 **Result:**
String


---


### decodeWatermark{#decodeWatermark}

| Name | Beschreibung |
| --- | --- |
| decodeWatermark(input, password) | Dekodiere das Wasserzeichen aus einem Mesh |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| input | Mesh | Das Mesh zum Extrahieren des Wasserzeichens |
| Passwort | String | Das Passwort zum Entschlüsseln des Wasserzeichens |

 **Result:**
String


---



