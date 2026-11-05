---
title: "TextureData"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

Diese Klasse enthält die Rohdaten und die Formatdefinition einer Textur.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | Konstruktor von TextureData |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Breite | Zahl | null |
| Höhe | Zahl | null |
| strid | Zahl | null |
| bytesPerPixe | Zahl | null |
| pixelFormat | PixelFormat | PixelFormat |
| dat | byte[] | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | Konstruiert ein neues TextureData und allokiert Pixeldaten. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Breite | Zahl | null |
| Höhe | Zahl | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Name | Beschreibung |
| --- | --- |
| constructor_overload2() | Konstruktor von TextureData |

 **Result:**



---


### getData{#getData}

| Name | Beschreibung |
| --- | --- |
| getData() | Rohbytes der Pixeldaten |

 **Result:**



---


### getWidth{#getWidth}

| Name | Beschreibung |
| --- | --- |
| getWidth() | Anzahl der horizontalen Pixel |

 **Result:**



---


### getHeight{#getHeight}

| Name | Beschreibung |
| --- | --- |
| getHeight() | Anzahl der vertikalen Pixel |

 **Result:**



---


### getStride{#getStride}

| Name | Beschreibung |
| --- | --- |
| getStride() | Anzahl der Bytes einer Scanzeile. |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| Name | Beschreibung |
| --- | --- |
| getBytesPerPixel() | Anzahl der Bytes eines Pixels |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| Name | Beschreibung |
| --- | --- |
| getPixelFormat() | Das Format des Pixels Der Wert der Eigenschaft ist die PixelFormat-Ganzzahlkonstante. |

 **Result:**



---


### fromFile{#fromFile}

| Name | Beschreibung |
| --- | --- |
| fromFile(fileName) | Lädt eine Textur aus einer Datei |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
TextureData


---


### save{#save}

| Name | Beschreibung |
| --- | --- |
| save(fileName) | Speichert Texturdaten in eine Bilddatei |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Der Dateiname, unter dem das Bild gespeichert wird. |

 **Result:**
TextureData


---


### save{#save}

| Name | Beschreibung |
| --- | --- |
| save(fileName, format) | Speichert Texturdaten in eine Bilddatei |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Der Dateiname, unter dem das Bild gespeichert wird. |
| Format | String | Bildformat der Ausgabedatei. |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| Name | Beschreibung |
| --- | --- |
| mapPixels(mapMode) | Alle Pixel zum Lesen/Schreiben abbilden |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Name | Beschreibung |
| --- | --- |
| mapPixels(mapMode, format) | Alle Pixel zum Lesen/Schreiben im angegebenen Pixelformat abbilden |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| Format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Name | Beschreibung |
| --- | --- |
| mapPixels(rect, mapMode, format) | Pixel, die durch rect adressiert werden, zum Lesen/Schreiben im angegebenen Pixelformat abbilden |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rect | Der Bereich der zuzugreifenden Pixel |
| mapMode | PixelMapMode | PixelMapMode |
| Format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| Name | Beschreibung |
| --- | --- |
| transformPixelFormat(pixelFormat) | Transformiere das Layout des Pixels in ein neues Pixelformat. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



