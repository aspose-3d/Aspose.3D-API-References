---
title: "TextureData"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

Denna klass innehåller rådata och formatdefinitionen för en textur.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | Konstruktor för TextureData |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| bredd | Nummer | null |
| höjd | Nummer | null |
| strid | Nummer | null |
| bytesPerPixe | Nummer | null |
| pixelFormat | PixelFormat | PixelFormat |
| data | byte[] | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | Skapar en ny TextureData och allokerar pixeldata. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| bredd | Nummer | null |
| höjd | Nummer | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload2() | Konstruktor för TextureData |

 **Result:**



---


### getData{#getData}

| Namn | Beskrivning |
| --- | --- |
| getData() | Rå byte för pixeldata |

 **Result:**



---


### getWidth{#getWidth}

| Namn | Beskrivning |
| --- | --- |
| getWidth() | Antal horisontella pixlar |

 **Result:**



---


### getHeight{#getHeight}

| Namn | Beskrivning |
| --- | --- |
| getHeight() | Antal vertikala pixlar |

 **Result:**



---


### getStride{#getStride}

| Namn | Beskrivning |
| --- | --- |
| getStride() | Antal byte i en rad. |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| Namn | Beskrivning |
| --- | --- |
| getBytesPerPixel() | Antal byte per pixel |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| Namn | Beskrivning |
| --- | --- |
| getPixelFormat() | Pixelens format Värdet på egenskapen är PixelFormat heltalskonstant. |

 **Result:**



---


### fromFile{#fromFile}

| Namn | Beskrivning |
| --- | --- |
| fromFile(fileName) | Ladda en textur från fil |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileNam | Sträng | null |

 **Result:**
TextureData


---


### save{#save}

| Namn | Beskrivning |
| --- | --- |
| save(fileName) | Spara texturdata i bildfil |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileName | Sträng | Filnamnet där bilden kommer att sparas. |

 **Result:**
TextureData


---


### save{#save}

| Namn | Beskrivning |
| --- | --- |
| save(fileName, format) | Spara texturdata i bildfil |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileName | Sträng | Filnamnet där bilden kommer att sparas. |
| format | Sträng | Bildformat för utdatafilen. |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| Namn | Beskrivning |
| --- | --- |
| mapPixels(mapMode) | Mappa alla pixlar för läs/skriv |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Namn | Beskrivning |
| --- | --- |
| mapPixels(mapMode, format) | Mappa alla pixlar för läs/skriv i angivet pixelformat |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Namn | Beskrivning |
| --- | --- |
| mapPixels(rect, mapMode, format) | Mappa pixlar adresserade av rect för läsning/skrivning i angivet pixelformat |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rect | Området av pixlar som ska nås |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| Namn | Beskrivning |
| --- | --- |
| transformPixelFormat(pixelFormat) | Transformera pixelns layout till ett nytt pixelformat. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



