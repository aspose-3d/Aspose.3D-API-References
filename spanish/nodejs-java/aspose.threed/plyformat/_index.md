---
title: "PlyFormat"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

El formato PLY.  @hideconstructor


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


### encode{#encode}

| Nombre | Descripción |
| --- | --- |
| encode(entity, fileName) | Codifique la entidad y guarde el resultado en un archivo externo. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | La entidad a codificar |
| fileName | Cadena | El archivo al que escribir |

 **Result:**



---


### encode{#encode}

| Nombre | Descripción |
| --- | --- |
| encode(entity, fileName, opt) | Codifique la entidad y guarde el resultado en un archivo externo. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | La entidad a codificar |
| fileName | Cadena | El archivo al que escribir |
| opt | PlySaveOptions | Opciones de guardado |

 **Result:**



---


### decode{#decode}

| Nombre | Descripción |
| --- | --- |
| decode(fileName) | Decodifique una nube de puntos o malla del flujo especificado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileName | Cadena | El flujo de entrada |

 **Result:**
Geometría


---


### decode{#decode}

| Nombre | Descripción |
| --- | --- |
| decode(fileName, opt) | Decodifique una nube de puntos o malla del flujo especificado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileName | Cadena | El flujo de entrada |
| opt | PlyLoadOptions | La opción de carga del formato PLY |

 **Result:**
Geometría


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



