---
title: "UsdSaveOptions"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

Opciones de guardado para formatos USD/USDZ.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva UsdSaveOptions con el formato FileFormat.USD. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(fileFormat) | Inicializa una nueva UsdSaveOptions con el formato USD/USDZ especificado. |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| Nombre | Descripción |
| --- | --- |
| getPrimitiveToMesh() | Convierte las entidades primitivas a malla durante la exportación. O codifica directamente las primitivas al archivo de salida (se usará la definición de extensión de Aspose para primitivas no oficiales como Dish, Torus). El valor predeterminado es true. |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| Nombre | Descripción |
| --- | --- |
| setPrimitiveToMesh(value) | Convierte las entidades primitivas a malla durante la exportación. O codifica directamente las primitivas al archivo de salida (se usará la definición de extensión de Aspose para primitivas no oficiales como Dish, Torus). El valor predeterminado es true. |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| Nombre | Descripción |
| --- | --- |
| getExportMetaData() | Exporta las propiedades del nodo a través del campo customData de USD. |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| Nombre | Descripción |
| --- | --- |
| setExportMetaData(value) | Exporta las propiedades del nodo a través del campo customData de USD. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Nombre | Descripción |
| --- | --- |
| getMaterialConverter() | Convertidor personalizado para convertir el material de la geometría a material PBR. Si no está asignado, el exportador USD convertirá automáticamente el material estándar a material PBR. El valor predeterminado es null |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Nombre | Descripción |
| --- | --- |
| setMaterialConverter(value) | Convertidor personalizado para convertir el material de la geometría a material PBR. Si no está asignado, el exportador USD convertirá automáticamente el material estándar a material PBR. El valor predeterminado es null |

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



