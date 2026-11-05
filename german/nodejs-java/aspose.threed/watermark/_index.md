---
title: "Wasserzeichen"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/watermark/
---
## Watermark class

Dienstprogramm zum Kodieren/Dekodieren eines blinden Wasserzeichens in/einem Mesh.  @hideconstructor


## Methoden

### encodeWatermark{#encodeWatermark}

| Name | Beschreibung |
| --- | --- |
| encodeWatermark(input, text) | Kodiert einen Text in ein blindes Wasserzeichen des Meshes. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| input | Mesh | Mesh zum Kodieren eines blinden Wasserzeichens |
| Text | String | Text, der in das Mesh kodiert werden soll |

 **Result:**
Mesh


---


### encodeWatermark{#encodeWatermark}

| Name | Beschreibung |
| --- | --- |
| encodeWatermark(input, text, password) | Kodiert einen Text in ein blindes Wasserzeichen des Meshes. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| input | Mesh | Mesh zum Kodieren eines blinden Wasserzeichens |
| Text | String | Text, der in das Mesh kodiert werden soll |
| password | String | Passwort zum Schutz des Wasserzeichens, optional |

 **Result:**
Mesh


---


### decodeWatermark{#decodeWatermark}

| Name | Beschreibung |
| --- | --- |
| decodeWatermark(input) | Dekodiert das Wasserzeichen aus einem Mesh |

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
| decodeWatermark(input, password) | Dekodiert das Wasserzeichen aus einem Mesh |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| input | Mesh | Das Mesh zum Extrahieren des Wasserzeichens |
| password | String | Das Passwort zum Entschlüsseln des Wasserzeichens |

 **Result:**
String


---



