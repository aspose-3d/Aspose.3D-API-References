---
title: "TextureData"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

Esta clase contiene los datos sin procesar y la definición de formato de una textura.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | Constructor de TextureData |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| widt | Número | null |
| heigh | Número | null |
| strid | Número | null |
| bytesPerPixe | Número | null |
| pixelFormat | PixelFormat | PixelFormat |
| dat | byte[] | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | Construye un nuevo TextureData y asigna datos de píxeles. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| widt | Número | null |
| heigh | Número | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nombre | Descripción |
| --- | --- |
| constructor_overload2() | Constructor de TextureData |

 **Result:**



---


### getData{#getData}

| Nombre | Descripción |
| --- | --- |
| getData() | Bytes sin procesar de datos de píxeles |

 **Result:**



---


### getWidth{#getWidth}

| Nombre | Descripción |
| --- | --- |
| getWidth() | Número de píxeles horizontales |

 **Result:**



---


### getHeight{#getHeight}

| Nombre | Descripción |
| --- | --- |
| getHeight() | Número de píxeles verticales |

 **Result:**



---


### getStride{#getStride}

| Nombre | Descripción |
| --- | --- |
| getStride() | Número de bytes de una línea de escaneo. |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| Nombre | Descripción |
| --- | --- |
| getBytesPerPixel() | Número de bytes de un píxel |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| Nombre | Descripción |
| --- | --- |
| getPixelFormat() | El formato del píxel. El valor de la propiedad es la constante entera PixelFormat. |

 **Result:**



---


### fromFile{#fromFile}

| Nombre | Descripción |
| --- | --- |
| fromFile(fileName) | Cargar una textura desde un archivo |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileNam | Cadena | null |

 **Result:**
TextureData


---


### save{#save}

| Nombre | Descripción |
| --- | --- |
| save(fileName) | Guardar datos de textura en un archivo de imagen |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileName | Cadena | El nombre del archivo donde se guardará la imagen. |

 **Result:**
TextureData


---


### save{#save}

| Nombre | Descripción |
| --- | --- |
| save(fileName, format) | Guardar datos de textura en un archivo de imagen |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileName | Cadena | El nombre del archivo donde se guardará la imagen. |
| format | Cadena | Formato de imagen del archivo de salida. |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| Nombre | Descripción |
| --- | --- |
| mapPixels(mapMode) | Mapear todos los píxeles para lectura/escritura |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Nombre | Descripción |
| --- | --- |
| mapPixels(mapMode, format) | Mapear todos los píxeles para lectura/escritura en el formato de píxel dado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Nombre | Descripción |
| --- | --- |
| mapPixels(rect, mapMode, format) | Mapear los píxeles especificados por rect para lectura/escritura en el formato de píxel dado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| rect | Rect | El área de píxeles a la que se accederá |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| Nombre | Descripción |
| --- | --- |
| transformPixelFormat(pixelFormat) | Transformar la disposición del píxel al nuevo formato de píxel. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



