---
title: "FbxSaveOptions"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/fbxsaveoptions/
---
## FbxSaveOptions class

Opciones de guardado para archivo Fbx.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(format) | Inicializa un FbxSaveOptions |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| forma | FileFormat | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(contentType) | Inicializa un FbxSaveOptions usando la última versión compatible. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getReusePrimitiveMesh{#getReusePrimitiveMesh}

| Nombre | Descripción |
| --- | --- |
| getReusePrimitiveMesh() | Reutiliza la malla para los primitivas con los mismos parámetros, lo que reducirá significativamente el tamaño del archivo FBX cuando la escena se haya construido con un gran conjunto de formas primitivas (como importadas de archivos CAD). El valor predeterminado es false. |

 **Result:**



---


### setReusePrimitiveMesh{#setReusePrimitiveMesh}

| Nombre | Descripción |
| --- | --- |
| setReusePrimitiveMesh(value) | Reutiliza la malla para los primitivas con los mismos parámetros, lo que reducirá significativamente el tamaño del archivo FBX cuando la escena se haya construido con un gran conjunto de formas primitivas (como importadas de archivos CAD). El valor predeterminado es false. |

 **Result:**



---


### getEnableCompression{#getEnableCompression}

| Nombre | Descripción |
| --- | --- |
| getEnableCompression() | Compresión de datos binarios grandes en el archivo FBX (p. ej., datos de animación, puntos de control, datos de elementos de vértice, índices), el valor predeterminado es true. |

 **Result:**



---


### setEnableCompression{#setEnableCompression}

| Nombre | Descripción |
| --- | --- |
| setEnableCompression(value) | Compresión de datos binarios grandes en el archivo FBX (p. ej., datos de animación, puntos de control, datos de elementos de vértice, índices), el valor predeterminado es true. |

 **Result:**



---


### getFoldRepeatedCurveData{#getFoldRepeatedCurveData}

| Nombre | Descripción |
| --- | --- |
| getFoldRepeatedCurveData() | Obtiene o establece si reutiliza datos de curvas repetidas incrementando el recuento de referencias del último dato; true si se pliegan los datos de curvas repetidas; de lo contrario, false. |

 **Result:**



---


### getExportLegacyMaterialProperties{#getExportLegacyMaterialProperties}

| Nombre | Descripción |
| --- | --- |
| getExportLegacyMaterialProperties() | Obtiene o establece si exporta propiedades de material heredadas, usadas para compatibilidad retroactiva. Esta opción está activada por defecto. |

 **Result:**



---


### setExportLegacyMaterialProperties{#setExportLegacyMaterialProperties}

| Nombre | Descripción |
| --- | --- |
| setExportLegacyMaterialProperties(value) | Obtiene o establece si exporta propiedades de material heredadas, usadas para compatibilidad retroactiva. Esta opción está activada por defecto. |

 **Result:**



---


### getVideoForTexture{#getVideoForTexture}

| Nombre | Descripción |
| --- | --- |
| getVideoForTexture() | Obtiene o establece si genera una instancia de Video para la Textura al exportar como FBX. |

 **Result:**



---


### setVideoForTexture{#setVideoForTexture}

| Nombre | Descripción |
| --- | --- |
| setVideoForTexture(value) | Obtiene o establece si genera una instancia de Video para la Textura al exportar como FBX. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Nombre | Descripción |
| --- | --- |
| getEmbedTextures() | Obtiene o establece si incrusta la textura en el archivo de salida final. El exportador FBX intentará encontrar los datos sin procesar de la textura en el sistema de archivos y incrustará el archivo en el FBX final. El valor predeterminado es false. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Nombre | Descripción |
| --- | --- |
| setEmbedTextures(value) | Obtiene o establece si incrusta la textura en el archivo de salida final. El exportador FBX intentará encontrar los datos sin procesar de la textura en el sistema de archivos y incrustará el archivo en el FBX final. El valor predeterminado es false. |

 **Result:**



---


### getGenerateVertexElementMaterial{#getGenerateVertexElementMaterial}

| Nombre | Descripción |
| --- | --- |
| getGenerateVertexElementMaterial() | Obtiene o establece si siempre genera un VertexElementMaterial para geometrías cuando el nodo adjunto contiene materiales. Esta opción está desactivada por defecto. |

 **Result:**



---


### setGenerateVertexElementMaterial{#setGenerateVertexElementMaterial}

| Nombre | Descripción |
| --- | --- |
| setGenerateVertexElementMaterial(value) | Obtiene o establece si siempre genera un VertexElementMaterial para geometrías cuando el nodo adjunto contiene materiales. Esta opción está desactivada por defecto. |

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



