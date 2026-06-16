---
title: "TextureData"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

Questa classe contiene i dati grezzi e la definizione del formato di una texture.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | Costruttore di TextureData |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| widt | Numero | null |
| heigh | Numero | null |
| strid | Numero | null |
| bytesPerPixe | Numero | null |
| pixelFormat | PixelFormat | PixelFormat |
| dat | byte[] | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | Crea un nuovo TextureData e alloca i dati dei pixel. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| widt | Numero | null |
| heigh | Numero | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nome | Descrizione |
| --- | --- |
| constructor_overload2() | Costruttore di TextureData |

 **Result:**



---


### getData{#getData}

| Nome | Descrizione |
| --- | --- |
| getData() | Byte grezzi dei dati dei pixel |

 **Result:**



---


### getWidth{#getWidth}

| Nome | Descrizione |
| --- | --- |
| getWidth() | Numero di pixel orizzontali |

 **Result:**



---


### getHeight{#getHeight}

| Nome | Descrizione |
| --- | --- |
| getHeight() | Numero di pixel verticali |

 **Result:**



---


### getStride{#getStride}

| Nome | Descrizione |
| --- | --- |
| getStride() | Numero di byte di una riga di scansione. |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| Nome | Descrizione |
| --- | --- |
| getBytesPerPixel() | Numero di byte di un pixel |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| Nome | Descrizione |
| --- | --- |
| getPixelFormat() | Il formato del pixel Il valore della proprietà è la costante intera PixelFormat. |

 **Result:**



---


### fromFile{#fromFile}

| Nome | Descrizione |
| --- | --- |
| fromFile(fileName) | Carica una texture da file |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileNam | Stringa | null |

 **Result:**
TextureData


---


### save{#save}

| Nome | Descrizione |
| --- | --- |
| save(fileName) | Salva i dati della texture in un file immagine |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileName | Stringa | Il nome del file in cui l'immagine verrà salvata. |

 **Result:**
TextureData


---


### save{#save}

| Nome | Descrizione |
| --- | --- |
| save(fileName, format) | Salva i dati della texture in un file immagine |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileName | Stringa | Il nome del file in cui l'immagine verrà salvata. |
| format | Stringa | Formato immagine del file di output. |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| Nome | Descrizione |
| --- | --- |
| mapPixels(mapMode) | Mappa tutti i pixel per lettura e scrittura |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Nome | Descrizione |
| --- | --- |
| mapPixels(mapMode, format) | Mappa tutti i pixel per lettura e scrittura nel formato pixel specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Nome | Descrizione |
| --- | --- |
| mapPixels(rect, mapMode, format) | Mappa i pixel indicati da rect per lettura e scrittura nel formato pixel specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rect | L'area dei pixel da accedere |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| Nome | Descrizione |
| --- | --- |
| transformPixelFormat(pixelFormat) | Trasforma il layout del pixel al nuovo formato pixel. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



