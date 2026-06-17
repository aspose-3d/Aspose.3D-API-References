---
title: "StlLoadOptions"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/stlloadoptions/
---
## StlLoadOptions class

Opciones de carga para STL


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva instancia de StlLoadOptions. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(contentType) | Inicializa una nueva instancia de StlLoadOptions. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Nombre | Descripción |
| --- | --- |
| getFlipCoordinateSystem() | Obtiene o establece si se invierte el sistema de coordenadas de los puntos de control/normal durante la importación. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Nombre | Descripción |
| --- | --- |
| setFlipCoordinateSystem(value) | Obtiene o establece si se invierte el sistema de coordenadas de los puntos de control/normal durante la importación. |

 **Result:**



---


### getRecalculateNormal{#getRecalculateNormal}

| Nombre | Descripción |
| --- | --- |
| getRecalculateNormal() | Ignorar los datos de normal almacenados en el archivo STL y recalcular los datos de normal basándose en la posición de los vértices. El valor predeterminado es false. |

 **Result:**



---


### setRecalculateNormal{#setRecalculateNormal}

| Nombre | Descripción |
| --- | --- |
| setRecalculateNormal(value) | Ignorar los datos de normal almacenados en el archivo STL y recalcular los datos de normal basándose en la posición de los vértices. El valor predeterminado es false. |

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



