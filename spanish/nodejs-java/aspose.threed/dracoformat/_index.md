---
title: "DracoFormat"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Formato Google Draco  @hideconstructor


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


### decode{#decode}

| Nombre | Descripción |
| --- | --- |
| decode(fileName) | Decodificar la nube de puntos o malla del nombre de archivo especificado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileName | Cadena | El nombre del archivo contiene el archivo drc |

 **Result:**
Geometría


---


### decode{#decode}

| Nombre | Descripción |
| --- | --- |
| decode(data) | Decodificar la nube de puntos o malla de los datos en memoria |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Los bytes crudos drc |

 **Result:**
Geometría


---


### encode{#encode}

| Nombre | Descripción |
| --- | --- |
| encode(entity, fileName, options) | Codificar la entidad al archivo especificado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | La entidad a codificar |
| fileName | Cadena | El nombre del archivo a escribir |
| opciones | DracoSaveOptions | Opciones extra para codificar la nube de puntos |

 **Result:**
Geometría


---


### encode{#encode}

| Nombre | Descripción |
| --- | --- |
| encode(entity, options) | Codificar la entidad a datos crudos Draco |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | La entidad a codificar |
| opciones | DracoSaveOptions | Opciones extra para codificar la nube de puntos |

 **Result:**
byte[]


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



