---
title: "FileFormat"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

Definición del formato de archivo  @hideconstructor


## Propiedades

| Nombre | Descripción |
| --- | --- |
| MAYA_BINARY | Autodesk Maya en formato binario |
| STL_BINARY | Formato de archivo STL binario |
| STLASCII | Formato de archivo STL ASCII |
| COLLADA | Formato de archivo Collada |
| GLTF | glTF de Khronos Group |
| GLTF_BINARY | glTF de Khronos Group en formato binario |
| PDF | Formato de Documento Portátil de Adobe |
| DXF | AutoCAD DXF |
| PLY | Formato de Archivo de Polígonos o Formato de Triángulo de Stanford |
| X_BINARY | Archivo X de DirectX en formato binario |
| X_TEXT | Archivo X de DirectX en formato binario |
| DRACO | Malla Draco de Google |
| RVM_TEXT | Modelo del Sistema de Gestión de Diseño de Planta AVEVA en formato de texto |
| RVM_BINARY | Modelo del Sistema de Gestión de Diseño de Planta AVEVA en formato binario |
| ASE | Formato del exportador de escena ASCII de 3D Studio Max. |
| IFC | Modelo de datos de Industry Foundation Classes ISO 16739-1. |
| AMF | Formato de archivo de fabricación aditiva |
| VRML | El Lenguaje de Modelado de Realidad Virtual |
| ZIP | Archivo Zip que contiene otros formatos de archivo 3d. |
| USD | Descripción de escena universal |
| USDZ | Descripción de escena universal comprimida |
| XYZ | Archivo de nube de puntos Xyz |
| PCD | Archivo de datos de nube de puntos PCL en modo ASCII |
| PCD_BINARY | Archivo de datos de nube de puntos PCL en modo binario |

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


### getFormatByExtension{#getFormatByExtension}

| Nombre | Descripción |
| --- | --- |
| getFormatByExtension(extensionName) | Obtiene el formato de archivo preferido a partir del nombre de la extensión del archivo. El nombre de la extensión debe comenzar con un punto ('.'). |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| extensionNam | Cadena | null |

 **Result:**
FileFormat


---


### detect{#detect}

| Nombre | Descripción |
| --- | --- |
| detect(fileName) | Detecta el formato de archivo a partir del nombre del archivo; el archivo debe ser legible para que Aspose.3D pueda detectar el formato de archivo mediante el encabezado del archivo. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileNam | Cadena | null |

 **Result:**
FileFormat


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



