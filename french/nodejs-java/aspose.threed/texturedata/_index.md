---
title: TextureData
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

Cette classe contient les données brutes et la définition du format d’une texture.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | Constructeur de TextureData |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| widt | Number | null |
| heigh | Number | null |
| strid | Number | null |
| bytesPerPixe | Number | null |
| pixelFormat | PixelFormat | PixelFormat |
| dat | byte[] | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | Construit un nouveau TextureData et alloue les données de pixel. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| widt | Number | null |
| heigh | Number | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nom | Description |
| --- | --- |
| constructor_overload2() | Constructeur de TextureData |

 **Result:**



---


### getData{#getData}

| Nom | Description |
| --- | --- |
| getData() | Octets bruts des données de pixel |

 **Result:**



---


### getWidth{#getWidth}

| Nom | Description |
| --- | --- |
| getWidth() | Nombre de pixels horizontaux |

 **Result:**



---


### getHeight{#getHeight}

| Nom | Description |
| --- | --- |
| getHeight() | Nombre de pixels verticaux |

 **Result:**



---


### getStride{#getStride}

| Nom | Description |
| --- | --- |
| getStride() | Nombre d'octets d'une ligne de balayage. |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| Nom | Description |
| --- | --- |
| getBytesPerPixel() | Nombre d'octets d'un pixel |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| Nom | Description |
| --- | --- |
| getPixelFormat() | Le format du pixel La valeur de la propriété est la constante entière PixelFormat. |

 **Result:**



---


### fromFile{#fromFile}

| Nom | Description |
| --- | --- |
| fromFile(fileName) | Charger une texture depuis un fichier |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
TextureData


---


### save{#save}

| Nom | Description |
| --- | --- |
| save(fileName) | Enregistrer les données de texture dans un fichier image |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileName | String | Le nom de fichier où l'image sera enregistrée. |

 **Result:**
TextureData


---


### save{#save}

| Nom | Description |
| --- | --- |
| save(fileName, format) | Enregistrer les données de texture dans un fichier image |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileName | String | Le nom de fichier où l'image sera enregistrée. |
| format | String | Format d'image du fichier de sortie. |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| Nom | Description |
| --- | --- |
| mapPixels(mapMode) | Mapper tous les pixels en lecture/écriture |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Nom | Description |
| --- | --- |
| mapPixels(mapMode, format) | Mapper tous les pixels en lecture/écriture dans le format de pixel donné |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Nom | Description |
| --- | --- |
| mapPixels(rect, mapMode, format) | Mapper les pixels adressés par le rectangle pour la lecture/écriture dans le format de pixel donné |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| rect | Rect | La zone de pixels à accéder |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| Nom | Description |
| --- | --- |
| transformPixelFormat(pixelFormat) | Transformer la disposition du pixel vers un nouveau format de pixel. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



