---
title: "PlySaveOptions"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/plysaveoptions/
---
## PlySaveOptions class

Opciones de guardado para exportar la escena como archivo PLY.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Constructor de PlySaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(contentType) | Constructor de PlySaveOptions |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getPointCloud{#getPointCloud}

| Nombre | Descripción |
| --- | --- |
| getPointCloud() | Exporta la escena como nube de puntos, el valor predeterminado es false. |

 **Result:**



---


### setPointCloud{#setPointCloud}

| Nombre | Descripción |
| --- | --- |
| setPointCloud(value) | Exporta la escena como nube de puntos, el valor predeterminado es false. |

 **Result:**



---


### getFlipCoordinate{#getFlipCoordinate}

| Nombre | Descripción |
| --- | --- |
| getFlipCoordinate() | Invierte la coordenada al guardar la escena, el valor predeterminado es true. |

 **Result:**



---


### setFlipCoordinate{#setFlipCoordinate}

| Nombre | Descripción |
| --- | --- |
| setFlipCoordinate(value) | Invierte la coordenada al guardar la escena, el valor predeterminado es true. |

 **Result:**



---


### getVertexElement{#getVertexElement}

| Nombre | Descripción |
| --- | --- |
| getVertexElement() | El nombre del elemento para los datos de vértice, el valor predeterminado es "vertex" |

 **Result:**



---


### setVertexElement{#setVertexElement}

| Nombre | Descripción |
| --- | --- |
| setVertexElement(value) | El nombre del elemento para los datos de vértice, el valor predeterminado es "vertex" |

 **Result:**



---


### getPositionComponents{#getPositionComponents}

| Nombre | Descripción |
| --- | --- |
| getPositionComponents() | Los nombres de los componentes para los datos de posición, el valor predeterminado es ("x", "y", "z") |

 **Result:**



---


### getNormalComponents{#getNormalComponents}

| Nombre | Descripción |
| --- | --- |
| getNormalComponents() | Los nombres de los componentes para los datos normales, el valor predeterminado es ("nx", "ny", "nz") |

 **Result:**



---


### getTextureCoordinateComponents{#getTextureCoordinateComponents}

| Nombre | Descripción |
| --- | --- |
| getTextureCoordinateComponents() | Los nombres de los componentes para los datos de coordenadas de textura, el valor predeterminado es ("u", "v") |

 **Result:**



---


### getColorComponents{#getColorComponents}

| Nombre | Descripción |
| --- | --- |
| getColorComponents() | Los nombres de los componentes para el color del vértice, el valor predeterminado es ("red", "green", "blue") |

 **Result:**



---


### getFaceElement{#getFaceElement}

| Nombre | Descripción |
| --- | --- |
| getFaceElement() | El nombre del elemento para los datos de la cara, el valor predeterminado es "face" |

 **Result:**



---


### setFaceElement{#setFaceElement}

| Nombre | Descripción |
| --- | --- |
| setFaceElement(value) | El nombre del elemento para los datos de la cara, el valor predeterminado es "face" |

 **Result:**



---


### getFaceProperty{#getFaceProperty}

| Nombre | Descripción |
| --- | --- |
| getFaceProperty() | El nombre de la propiedad para los datos de la cara, el valor predeterminado es "vertex_index" |

 **Result:**



---


### setFaceProperty{#setFaceProperty}

| Nombre | Descripción |
| --- | --- |
| setFaceProperty(value) | El nombre de la propiedad para los datos de la cara, el valor predeterminado es "vertex_index" |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Nombre | Descripción |
| --- | --- |
| getExportTextures() | Intenta copiar las texturas usadas en la escena al directorio de salida. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Nombre | Descripción |
| --- | --- |
| setExportTextures(value) | Intenta copiar las texturas usadas en la escena al directorio de salida. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Nombre | Descripción |
| --- | --- |
| getFileFormat() | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |

 **Result:**



---


### getEncoding{#getEncoding}

| Nombre | Descripción |
| --- | --- |
| getEncoding() | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Nombre | Descripción |
| --- | --- |
| getFileSystem() | Permite al usuario manejar cómo gestionar las dependencias externas durante la carga/guardado. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Nombre | Descripción |
| --- | --- |
| setFileSystem(value) | Permite al usuario manejar cómo gestionar las dependencias externas durante la carga/guardado. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Nombre | Descripción |
| --- | --- |
| getLookupPaths() | Algunos archivos como OBJ dependen de archivos externos; las rutas de búsqueda permiten que Aspose.3D busque el archivo externo para cargarlo. |

 **Result:**



---


### getFileName{#getFileName}

| Nombre | Descripción |
| --- | --- |
| getFileName() | El nombre de archivo de la escena de exportación/importación. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Nombre | Descripción |
| --- | --- |
| setFileName(value) | El nombre de archivo de la escena de exportación/importación. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |

 **Result:**



---



