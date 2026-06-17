---
title: "Watermark"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/watermark/
---
## Watermark class

Utilidad para codificar/decodificar marca de agua ciega a/de una malla.  @hideconstructor


## Métodos

### encodeWatermark{#encodeWatermark}

| Nombre | Descripción |
| --- | --- |
| encodeWatermark(input, text) | Codifica un texto en la marca de agua ciega de la malla. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| input | Malla | Malla para codificar una marca de agua ciega |
| text | Cadena | Texto para codificar en la malla |

 **Result:**
Malla


---


### encodeWatermark{#encodeWatermark}

| Nombre | Descripción |
| --- | --- |
| encodeWatermark(input, text, password) | Codifica un texto en la marca de agua ciega de la malla. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| input | Malla | Malla para codificar una marca de agua ciega |
| text | Cadena | Texto para codificar en la malla |
| password | Cadena | Contraseña para proteger la marca de agua, es opcional |

 **Result:**
Malla


---


### decodeWatermark{#decodeWatermark}

| Nombre | Descripción |
| --- | --- |
| decodeWatermark(input) | Decodifica la marca de agua de una malla |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| input | Malla | La malla para extraer la marca de agua |

 **Result:**
Cadena


---


### decodeWatermark{#decodeWatermark}

| Nombre | Descripción |
| --- | --- |
| decodeWatermark(input, password) | Decodifica la marca de agua de una malla |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| input | Malla | La malla para extraer la marca de agua |
| password | Cadena | La contraseña para descifrar la marca de agua |

 **Result:**
Cadena


---



