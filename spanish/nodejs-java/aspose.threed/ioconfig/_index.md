---
title: "IOConfig"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/ioconfig/
---
## IOConfig class

Configuración de E/S para serialización/deserialización.  El usuario puede especificar configuraciones detalladas como la ruta de búsqueda de dependencias  o configuraciones relacionadas con el formato aquí  @hideconstructor


## Métodos

### getFileSystemFactory{#getFileSystemFactory}

| Nombre | Descripción |
| --- | --- |
| getFileSystemFactory() | Obtiene o establece la clase fábrica para FileSystem. La fábrica predeterminada creará LocalFileSystem, que no es adecuada para entornos de servidor. |

 **Result:**



---


### setFileSystemFactory{#setFileSystemFactory}

| Nombre | Descripción |
| --- | --- |
| setFileSystemFactory(value) | Obtiene o establece la clase fábrica para FileSystem. La fábrica predeterminada creará LocalFileSystem, que no es adecuada para entornos de servidor. |

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



