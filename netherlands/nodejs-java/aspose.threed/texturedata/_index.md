---
title: "TextureData"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

Deze klasse bevat de ruwe gegevens en de formaatdefinitie van een textuur.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | Constructor van TextureData |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| breedte | Nummer | null |
| hoogte | Nummer | null |
| strid | Nummer | null |
| bytesPerPixe | Nummer | null |
| pixelFormat | PixelFormat | PixelFormat |
| dat | byte[] | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | Construeert een nieuwe TextureData en reserveert pixelgegevens. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| breedte | Nummer | null |
| hoogte | Nummer | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload2() | Constructor van TextureData |

 **Result:**



---


### getData{#getData}

| Naam | Beschrijving |
| --- | --- |
| getData() | Ruwe bytes van pixelgegevens |

 **Result:**



---


### getWidth{#getWidth}

| Naam | Beschrijving |
| --- | --- |
| getWidth() | Aantal horizontale pixels |

 **Result:**



---


### getHeight{#getHeight}

| Naam | Beschrijving |
| --- | --- |
| getHeight() | Aantal verticale pixels |

 **Result:**



---


### getStride{#getStride}

| Naam | Beschrijving |
| --- | --- |
| getStride() | Aantal bytes van een scanlijn. |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| Naam | Beschrijving |
| --- | --- |
| getBytesPerPixel() | Aantal bytes van een pixel |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| Naam | Beschrijving |
| --- | --- |
| getPixelFormat() | Het pixelformaat De waarde van de eigenschap is een PixelFormat integer-constante. |

 **Result:**



---


### fromFile{#fromFile}

| Naam | Beschrijving |
| --- | --- |
| fromFile(fileName) | Laad een textuur vanuit bestand |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
TextureData


---


### save{#save}

| Naam | Beschrijving |
| --- | --- |
| save(fileName) | Sla textuurgegevens op in een afbeeldingsbestand |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | De bestandsnaam waar de afbeelding wordt opgeslagen. |

 **Result:**
TextureData


---


### save{#save}

| Naam | Beschrijving |
| --- | --- |
| save(fileName, format) | Sla textuurgegevens op in een afbeeldingsbestand |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | De bestandsnaam waar de afbeelding wordt opgeslagen. |
| format | String | Afbeeldingsformaat van het uitvoerbestand. |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| Naam | Beschrijving |
| --- | --- |
| mapPixels(mapMode) | Map alle pixels voor lezen/schrijven |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Naam | Beschrijving |
| --- | --- |
| mapPixels(mapMode, format) | Map alle pixels voor lezen/schrijven in het opgegeven pixelformaat |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Naam | Beschrijving |
| --- | --- |
| mapPixels(rect, mapMode, format) | Map pixels aangeduid door rect voor lezen/schrijven in het opgegeven pixelformaat |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| rect | Rect | Het gebied van pixels dat benaderd moet worden |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| Naam | Beschrijving |
| --- | --- |
| transformPixelFormat(pixelFormat) | Transformeer de lay-out van de pixel naar een nieuw pixelformaat. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



