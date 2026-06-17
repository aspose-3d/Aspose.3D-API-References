---
title: "Vattenstämpel"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/watermark/
---
## Watermark class

Verktyg för att koda/avkoda blind vattenstämpel till/från ett mesh.  @hideconstructor


## Metoder

### encodeWatermark{#encodeWatermark}

| Namn | Beskrivning |
| --- | --- |
| encodeWatermark(input, text) | Koda en text till meshens blinda vattenstämpel. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| input | Mesh | Mesh för att koda en blind vattenstämpel |
| text | Sträng | Text att koda till meshen |

 **Result:**
Mesh


---


### encodeWatermark{#encodeWatermark}

| Namn | Beskrivning |
| --- | --- |
| encodeWatermark(input, text, password) | Koda en text till meshens blinda vattenstämpel. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| input | Mesh | Mesh för att koda en blind vattenstämpel |
| text | Sträng | Text att koda till meshen |
| password | Sträng | Lösenord för att skydda vattenstämpeln, det är valfritt |

 **Result:**
Mesh


---


### decodeWatermark{#decodeWatermark}

| Namn | Beskrivning |
| --- | --- |
| decodeWatermark(input) | Dekoda vattenstämpeln från en mesh |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| input | Mesh | Meshen för att extrahera vattenstämpeln |

 **Result:**
Sträng


---


### decodeWatermark{#decodeWatermark}

| Namn | Beskrivning |
| --- | --- |
| decodeWatermark(input, password) | Dekoda vattenstämpeln från en mesh |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| input | Mesh | Meshen för att extrahera vattenstämpeln |
| password | Sträng | Lösenordet för att dekryptera vattenstämpeln |

 **Result:**
Sträng


---



