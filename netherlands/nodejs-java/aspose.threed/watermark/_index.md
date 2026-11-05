---
title: "Watermark"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/watermark/
---
## Watermark class

Hulpmiddel om een blinde watermerk te coderen/decoderen naar/van een mesh.  @hideconstructor


## Methoden

### encodeWatermark{#encodeWatermark}

| Naam | Beschrijving |
| --- | --- |
| encodeWatermark(input, text) | Codeer een tekst in een blinde watermerk van het mesh. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| input | Mesh | Mesh om een blinde watermerk te coderen |
| text | String | Tekst om te coderen naar het mesh |

 **Result:**
Mesh


---


### encodeWatermark{#encodeWatermark}

| Naam | Beschrijving |
| --- | --- |
| encodeWatermark(input, text, password) | Codeer een tekst in een blinde watermerk van het mesh. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| input | Mesh | Mesh om een blinde watermerk te coderen |
| text | String | Tekst om te coderen naar het mesh |
| password | String | Wachtwoord om het watermerk te beschermen, optioneel |

 **Result:**
Mesh


---


### decodeWatermark{#decodeWatermark}

| Naam | Beschrijving |
| --- | --- |
| decodeWatermark(input) | Decodeer het watermerk van een mesh |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| input | Mesh | De mesh om het watermerk te extraheren |

 **Result:**
String


---


### decodeWatermark{#decodeWatermark}

| Naam | Beschrijving |
| --- | --- |
| decodeWatermark(input, password) | Decodeer het watermerk van een mesh |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| input | Mesh | De mesh om het watermerk te extraheren |
| password | String | Het wachtwoord om het watermerk te ontcijferen |

 **Result:**
String


---



