---
title: "PdfFormat"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/pdfformat/
---
## PdfFormat class

Formato de Documento Portátil de Adobe  @hideconstructor


## Métodos

### getVersion{#getVersion}

| Nombre | Descripción |
| --- | --- |
| getVersion() | Obtiene la versión del formato de archivo |

 **Result:**



---


### getExtension{#getExtension}

| Nombre | Descripción |
| --- | --- |
| getExtension() | Obtiene el nombre de la extensión de este tipo. |

 **Result:**



---


### getExtensions{#getExtensions}

| Nombre | Descripción |
| --- | --- |
| getExtensions() | Obtiene los nombres de las extensiones de este tipo. |

 **Result:**



---


### getContentType{#getContentType}

| Nombre | Descripción |
| --- | --- |
| getContentType() | Obtiene el tipo de contenido del formato de archivo. El valor de la propiedad es la constante entera FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Nombre | Descripción |
| --- | --- |
| getFileFormatType() | Obtiene el tipo de formato de archivo |

 **Result:**



---


### extract{#extract}

| Nombre | Descripción |
| --- | --- |
| extract(fileName, password) | Extrae contenido 3D sin procesar de un archivo PDF. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileNam | Cadena | null |
| contraseña | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### extractScene{#extractScene}

| Nombre | Descripción |
| --- | --- |
| extractScene(fileName) | Extrae escenas 3D de un archivo PDF. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileNam | Cadena | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### extractScene{#extractScene}

| Nombre | Descripción |
| --- | --- |
| extractScene(fileName, password) | Extrae escenas 3D de un archivo PDF. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileNam | Cadena | null |
| contraseña | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createLoadOptions{#createLoadOptions}

| Nombre | Descripción |
| --- | --- |
| createLoadOptions() | Crea opciones de carga predeterminadas para este formato de archivo |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Nombre | Descripción |
| --- | --- |
| createSaveOptions() | Crea opciones de guardado predeterminadas para este formato de archivo |

 **Result:**
SaveOptions


---


### toString{#toString}

| Nombre | Descripción |
| --- | --- |
| toString() | Formatos a cadena |

 **Result:**
Cadena


---



