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
| encodeWatermark(input, text) | Encodeer een tekst in een blinde watermerk van het mesh. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| input | Mesh | Mesh om een blinde watermerk te coderen. |
| text | String | Tekst om te coderen in het mesh |

 **Result:**
Mesh


---


### encodeWatermark{#encodeWatermark}

| Naam | Beschrijving |
| --- | --- |
| encodeWatermark(input, text, password) | Encodeer een tekst in een blinde watermerk van het mesh. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| input | Mesh | Mesh om een blinde watermerk te coderen. |
| text | String | Tekst om te coderen in het mesh |
| password | String | Wachtwoord om het watermerk te beschermen, is optioneel |

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
| input | Mesh | Het mesh om het watermerk te extraheren |

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
| input | Mesh | Het mesh om het watermerk te extraheren |
| password | String | Het wachtwoord om het watermerk te ontsleutelen |

 **Result:**
String


---



