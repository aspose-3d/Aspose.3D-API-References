---
title: "GltfSaveOptions"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

Opciones de guardado para el formato glTF.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(contentType) | Constructor de GltfSaveOptions |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(format) | Constructor de GltfSaveOptions |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| forma | FileFormat | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| Nombre | Descripción |
| --- | --- |
| getPrettyPrint() | El contenido JSON del archivo GLTF está indentado para la lectura humana, el valor predeterminado es false |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| Nombre | Descripción |
| --- | --- |
| setPrettyPrint(value) | El contenido JSON del archivo GLTF está indentado para la lectura humana, el valor predeterminado es false |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| Nombre | Descripción |
| --- | --- |
| getFallbackNormal() | Cuando el exportador GLTF2 detecta una normal inválida, esto se usará en lugar de su valor original para eludir la validación. El valor predeterminado es (0, 1, 0) |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| Nombre | Descripción |
| --- | --- |
| getEmbedAssets() | Incrusta todos los recursos externos como base64 en un solo archivo en modo ASCII, el valor predeterminado es false. |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| Nombre | Descripción |
| --- | --- |
| setEmbedAssets(value) | Incrusta todos los recursos externos como base64 en un solo archivo en modo ASCII, el valor predeterminado es false. |

 **Result:**



---


### getImageFormat{#getImageFormat}

| Nombre | Descripción |
| --- | --- |
| getImageFormat() | El glTF estándar solo admite PNG/JPG como su formato de textura, esta opción guiará cómo Aspose.3D convierte las imágenes no estándar al formato compatible durante la exportación. El valor predeterminado es GltfEmbeddedImageFormat.PNG. El valor de la propiedad es la constante entera GltfEmbeddedImageFormat. |

 **Result:**



---


### setImageFormat{#setImageFormat}

| Nombre | Descripción |
| --- | --- |
| setImageFormat(value) | El glTF estándar solo admite PNG/JPG como su formato de textura, esta opción guiará cómo Aspose.3D convierte las imágenes no estándar al formato compatible durante la exportación. El valor predeterminado es GltfEmbeddedImageFormat.PNG. El valor de la propiedad es la constante entera GltfEmbeddedImageFormat. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Nombre | Descripción |
| --- | --- |
| getMaterialConverter() | Convertidor personalizado para convertir el material de la geometría a material PBR. Si no está asignado, el exportador glTF 2.0 convertirá automáticamente el material estándar a material PBR. El valor predeterminado es null. Esta propiedad se usa al exportar una escena a un archivo glTF 2.0. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Nombre | Descripción |
| --- | --- |
| setMaterialConverter(value) | Convertidor personalizado para convertir el material de la geometría a material PBR. Si no está asignado, el exportador glTF 2.0 convertirá automáticamente el material estándar a material PBR. El valor predeterminado es null. Esta propiedad se usa al exportar una escena a un archivo glTF 2.0. |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| Nombre | Descripción |
| --- | --- |
| getUseCommonMaterials() | Serializar materiales usando extensiones de material común KHR, el valor predeterminado es false. Establecer esto en false hará que Aspose.3D exporte un conjunto de shaders de vértice/fragmento si #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| Nombre | Descripción |
| --- | --- |
| setUseCommonMaterials(value) | Serializar materiales usando extensiones de material común KHR, el valor predeterminado es false. Establecer esto en false hará que Aspose.3D exporte un conjunto de shaders de vértice/fragmento si #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| Nombre | Descripción |
| --- | --- |
| getExternalDracoEncoder() | Utilizar un codificador draco externo para acelerar la velocidad de compresión draco. Aspose.3D creará un nuevo subproceso para codificar la malla al formato draco, úselo bajo su propio riesgo. |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| Nombre | Descripción |
| --- | --- |
| setExternalDracoEncoder(value) | Utilizar un codificador draco externo para acelerar la velocidad de compresión draco. Aspose.3D creará un nuevo subproceso para codificar la malla al formato draco, úselo bajo su propio riesgo. |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| Nombre | Descripción |
| --- | --- |
| getFlipTexCoordV() | Invertir el componente v(t) de la coordenada de textura, el valor predeterminado es true. |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| Nombre | Descripción |
| --- | --- |
| setFlipTexCoordV(value) | Invertir el componente v(t) de la coordenada de textura, el valor predeterminado es true. |

 **Result:**



---


### getBufferFile{#getBufferFile}

| Nombre | Descripción |
| --- | --- |
| getBufferFile() | El nombre de archivo del buffer externo utilizado para almacenar datos binarios. Si este archivo no se especifica, Aspose.3D generará un nombre para usted. Esto se ignora al exportar glTF en modo binario. |

 **Result:**



---


### setBufferFile{#setBufferFile}

| Nombre | Descripción |
| --- | --- |
| setBufferFile(value) | El nombre de archivo del buffer externo utilizado para almacenar datos binarios. Si este archivo no se especifica, Aspose.3D generará un nombre para usted. Esto se ignora al exportar glTF en modo binario. |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| Nombre | Descripción |
| --- | --- |
| getSaveExtras() | Guardar las propiedades dinámicas del objeto de escena en campos 'extra' en el archivo glTF generado. Esto es útil para proporcionar datos específicos de la aplicación. El valor predeterminado es false. |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| Nombre | Descripción |
| --- | --- |
| setSaveExtras(value) | Guardar las propiedades dinámicas del objeto de escena en campos 'extra' en el archivo glTF generado. Esto es útil para proporcionar datos específicos de la aplicación. El valor predeterminado es false. |

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


### getDracoCompression{#getDracoCompression}

| Nombre | Descripción |
| --- | --- |
| getDracoCompression() | Obtiene o establece si se habilita la compresión draco |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| Nombre | Descripción |
| --- | --- |
| setDracoCompression(value) | Obtiene o establece si se habilita la compresión draco |

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



