---
title: "PdfSaveOptions"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/pdfsaveoptions/
---
## PdfSaveOptions class

Las opciones de guardado al exportar PDF.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Constructor de PdfSaveOptions |

 **Result:**



---


### getRenderMode{#getRenderMode}

| Nombre | Descripción |
| --- | --- |
| getRenderMode() | El modo de renderizado especifica el estilo en el que se representa la obra 3D. El valor de la propiedad es la constante entera PdfRenderMode. |

 **Result:**



---


### setRenderMode{#setRenderMode}

| Nombre | Descripción |
| --- | --- |
| setRenderMode(value) | El modo de renderizado especifica el estilo en el que se representa la obra 3D. El valor de la propiedad es la constante entera PdfRenderMode. |

 **Result:**



---


### getLightingScheme{#getLightingScheme}

| Nombre | Descripción |
| --- | --- |
| getLightingScheme() | LightingScheme especifica la iluminación a aplicar a la obra 3D. El valor de la propiedad es la constante entera PdfLightingScheme. |

 **Result:**



---


### setLightingScheme{#setLightingScheme}

| Nombre | Descripción |
| --- | --- |
| setLightingScheme(value) | LightingScheme especifica la iluminación a aplicar a la obra 3D. El valor de la propiedad es la constante entera PdfLightingScheme. |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| Nombre | Descripción |
| --- | --- |
| getBackgroundColor() | Color de fondo de la vista 3D en el archivo PDF. |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| Nombre | Descripción |
| --- | --- |
| setBackgroundColor(value) | Color de fondo de la vista 3D en el archivo PDF. |

 **Result:**



---


### getFaceColor{#getFaceColor}

| Nombre | Descripción |
| --- | --- |
| getFaceColor() | Obtiene o establece el color de la cara que se usará al renderizar el contenido 3D. Esto solo es relevante cuando el RenderMode tiene un valor de Illustration. |

 **Result:**



---


### setFaceColor{#setFaceColor}

| Nombre | Descripción |
| --- | --- |
| setFaceColor(value) | Obtiene o establece el color de la cara que se usará al renderizar el contenido 3D. Esto solo es relevante cuando el RenderMode tiene un valor de Illustration. |

 **Result:**



---


### getAuxiliaryColor{#getAuxiliaryColor}

| Nombre | Descripción |
| --- | --- |
| getAuxiliaryColor() | Obtiene o establece el color auxiliar que se usará al renderizar el contenido 3D. La interpretación de este color depende del RenderMode. |

 **Result:**



---


### setAuxiliaryColor{#setAuxiliaryColor}

| Nombre | Descripción |
| --- | --- |
| setAuxiliaryColor(value) | Obtiene o establece el color auxiliar que se usará al renderizar el contenido 3D. La interpretación de este color depende del RenderMode. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Nombre | Descripción |
| --- | --- |
| getFlipCoordinateSystem() | Obtiene o establece si se invierte el sistema de coordenadas de la escena durante la exportación. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Nombre | Descripción |
| --- | --- |
| setFlipCoordinateSystem(value) | Obtiene o establece si se invierte el sistema de coordenadas de la escena durante la exportación. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Nombre | Descripción |
| --- | --- |
| getEmbedTextures() | Incrusta las texturas externas en el archivo PDF, el valor predeterminado es false. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Nombre | Descripción |
| --- | --- |
| setEmbedTextures(value) | Incrusta las texturas externas en el archivo PDF, el valor predeterminado es false. |

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



