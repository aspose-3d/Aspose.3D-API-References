---
title: "DracoSaveOptions"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/dracosaveoptions/
---
## DracoSaveOptions class

Opciones de guardado para archivos Google draco


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Construir una configuración predeterminada para guardar archivos draco. |

 **Result:**



---


### getPositionBits{#getPositionBits}

| Nombre | Descripción |
| --- | --- |
| getPositionBits() | Bits de cuantización para la posición, el valor predeterminado es 14. |

 **Result:**



---


### setPositionBits{#setPositionBits}

| Nombre | Descripción |
| --- | --- |
| setPositionBits(value) | Bits de cuantización para la posición, el valor predeterminado es 14. |

 **Result:**



---


### getTextureCoordinateBits{#getTextureCoordinateBits}

| Nombre | Descripción |
| --- | --- |
| getTextureCoordinateBits() | Bits de cuantización para la coordenada de textura, el valor predeterminado es 12. |

 **Result:**



---


### setTextureCoordinateBits{#setTextureCoordinateBits}

| Nombre | Descripción |
| --- | --- |
| setTextureCoordinateBits(value) | Bits de cuantización para la coordenada de textura, el valor predeterminado es 12. |

 **Result:**



---


### getColorBits{#getColorBits}

| Nombre | Descripción |
| --- | --- |
| getColorBits() | Bits de cuantización para el color del vértice, el valor predeterminado es 10. |

 **Result:**



---


### setColorBits{#setColorBits}

| Nombre | Descripción |
| --- | --- |
| setColorBits(value) | Bits de cuantización para el color del vértice, el valor predeterminado es 10. |

 **Result:**



---


### getNormalBits{#getNormalBits}

| Nombre | Descripción |
| --- | --- |
| getNormalBits() | Bits de cuantización para vectores normales, el valor predeterminado es 10. |

 **Result:**



---


### setNormalBits{#setNormalBits}

| Nombre | Descripción |
| --- | --- |
| setNormalBits(value) | Bits de cuantización para vectores normales, el valor predeterminado es 10. |

 **Result:**



---


### getCompressionLevel{#getCompressionLevel}

| Nombre | Descripción |
| --- | --- |
| getCompressionLevel() | Nivel de compresión, el valor predeterminado es DracoCompressionLevel.STANDARD. El valor de la propiedad es una constante entera DracoCompressionLevel. |

 **Result:**



---


### setCompressionLevel{#setCompressionLevel}

| Nombre | Descripción |
| --- | --- |
| setCompressionLevel(value) | Nivel de compresión, el valor predeterminado es DracoCompressionLevel.STANDARD. El valor de la propiedad es una constante entera DracoCompressionLevel. |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| Nombre | Descripción |
| --- | --- |
| getApplyUnitScale() | Aplicar AssetInfo.UnitScaleFactor a la malla. El valor predeterminado es false. |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| Nombre | Descripción |
| --- | --- |
| setApplyUnitScale(value) | Aplicar AssetInfo.UnitScaleFactor a la malla. El valor predeterminado es false. |

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



