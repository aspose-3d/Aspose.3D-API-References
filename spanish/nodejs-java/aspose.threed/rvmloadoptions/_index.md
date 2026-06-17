---
title: "RvmLoadOptions"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/rvmloadoptions/
---
## RvmLoadOptions class

Opciones de carga para el archivo RVM del Sistema de Gestión de Diseño de Plantas AVEVA.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(contentType) | Construye una instancia de RvmLoadOptions |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload() | Construye una instancia de RvmLoadOptions |

 **Result:**



---


### getGenerateMaterials{#getGenerateMaterials}

| Nombre | Descripción |
| --- | --- |
| getGenerateMaterials() | Genera materiales con colores aleatorios para cada objeto en la escena si la tabla de colores no se exporta dentro del archivo RVM. El valor predeterminado es true |

 **Result:**



---


### setGenerateMaterials{#setGenerateMaterials}

| Nombre | Descripción |
| --- | --- |
| setGenerateMaterials(value) | Genera materiales con colores aleatorios para cada objeto en la escena si la tabla de colores no se exporta dentro del archivo RVM. El valor predeterminado es true |

 **Result:**



---


### getCylinderRadialSegments{#getCylinderRadialSegments}

| Nombre | Descripción |
| --- | --- |
| getCylinderRadialSegments() | Obtiene o establece el número de segmentos radiales del cilindro, el valor predeterminado es 16 |

 **Result:**



---


### setCylinderRadialSegments{#setCylinderRadialSegments}

| Nombre | Descripción |
| --- | --- |
| setCylinderRadialSegments(value) | Obtiene o establece el número de segmentos radiales del cilindro, el valor predeterminado es 16 |

 **Result:**



---


### getDishLongitudeSegments{#getDishLongitudeSegments}

| Nombre | Descripción |
| --- | --- |
| getDishLongitudeSegments() | Obtiene o establece el número de segmentos de longitud del dish, el valor predeterminado es 12 |

 **Result:**



---


### setDishLongitudeSegments{#setDishLongitudeSegments}

| Nombre | Descripción |
| --- | --- |
| setDishLongitudeSegments(value) | Obtiene o establece el número de segmentos de longitud del dish, el valor predeterminado es 12 |

 **Result:**



---


### getDishLatitudeSegments{#getDishLatitudeSegments}

| Nombre | Descripción |
| --- | --- |
| getDishLatitudeSegments() | Obtiene o establece el número de segmentos de latitud del dish, el valor predeterminado es 8 |

 **Result:**



---


### setDishLatitudeSegments{#setDishLatitudeSegments}

| Nombre | Descripción |
| --- | --- |
| setDishLatitudeSegments(value) | Obtiene o establece el número de segmentos de latitud del dish, el valor predeterminado es 8 |

 **Result:**



---


### getTorusTubularSegments{#getTorusTubularSegments}

| Nombre | Descripción |
| --- | --- |
| getTorusTubularSegments() | Obtiene o establece el número de segmentos tubulares del torus, el valor predeterminado es 20 |

 **Result:**



---


### setTorusTubularSegments{#setTorusTubularSegments}

| Nombre | Descripción |
| --- | --- |
| setTorusTubularSegments(value) | Obtiene o establece el número de segmentos tubulares del torus, el valor predeterminado es 20 |

 **Result:**



---


### getRectangularTorusSegments{#getRectangularTorusSegments}

| Nombre | Descripción |
| --- | --- |
| getRectangularTorusSegments() | Obtiene o establece el número de segmentos radiales del torus rectangular, el valor predeterminado es 20 |

 **Result:**



---


### setRectangularTorusSegments{#setRectangularTorusSegments}

| Nombre | Descripción |
| --- | --- |
| setRectangularTorusSegments(value) | Obtiene o establece el número de segmentos radiales del torus rectangular, el valor predeterminado es 20 |

 **Result:**



---


### getCenterScene{#getCenterScene}

| Nombre | Descripción |
| --- | --- |
| getCenterScene() | Centrar la escena después de que se cargue. |

 **Result:**



---


### setCenterScene{#setCenterScene}

| Nombre | Descripción |
| --- | --- |
| setCenterScene(value) | Centrar la escena después de que se cargue. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Nombre | Descripción |
| --- | --- |
| getAttributePrefix() | Obtiene o establece el prefijo de los atributos que fueron definidos en archivos de atributos externos, el prefijo se usa para evitar conflictos de nombres, el valor predeterminado es "rvm:" |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Nombre | Descripción |
| --- | --- |
| setAttributePrefix(value) | Obtiene o establece el prefijo de los atributos que fueron definidos en archivos de atributos externos, el prefijo se usa para evitar conflictos de nombres, el valor predeterminado es "rvm:" |

 **Result:**



---


### getLookupAttributes{#getLookupAttributes}

| Nombre | Descripción |
| --- | --- |
| getLookupAttributes() | Obtiene o establece si se deben cargar los atributos desde un archivo de lista de atributos externo (.att/.attrib/.txt), el valor predeterminado es true. |

 **Result:**



---


### setLookupAttributes{#setLookupAttributes}

| Nombre | Descripción |
| --- | --- |
| setLookupAttributes(value) | Obtiene o establece si se deben cargar los atributos desde un archivo de lista de atributos externo (.att/.attrib/.txt), el valor predeterminado es true. |

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



