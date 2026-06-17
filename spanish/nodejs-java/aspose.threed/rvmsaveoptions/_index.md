---
title: "RvmSaveOptions"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/rvmsaveoptions/
---
## RvmSaveOptions class

Opciones de guardado para el archivo RVM de Aveva PDMS.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Constructor de RvmSaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(contentType) | Constructor de RvmSaveOptions |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFileNote{#getFileNote}

| Nombre | Descripción |
| --- | --- |
| getFileNote() | Nota del archivo en el encabezado del archivo. |

 **Result:**



---


### setFileNote{#setFileNote}

| Nombre | Descripción |
| --- | --- |
| setFileNote(value) | Nota del archivo en el encabezado del archivo. |

 **Result:**



---


### getAuthor{#getAuthor}

| Nombre | Descripción |
| --- | --- |
| getAuthor() |  |

 **Result:**



---


### setAuthor{#setAuthor}

| Nombre | Descripción |
| --- | --- |
| setAuthor(value) |  |

 **Result:**



---


### getCreationTime{#getCreationTime}

| Nombre | Descripción |
| --- | --- |
| getCreationTime() | La marca de tiempo que exportó este archivo, el valor predeterminado es la hora actual. |

 **Result:**



---


### setCreationTime{#setCreationTime}

| Nombre | Descripción |
| --- | --- |
| setCreationTime(value) | La marca de tiempo que exportó este archivo, el valor predeterminado es la hora actual. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Nombre | Descripción |
| --- | --- |
| getAttributePrefix() | Obtiene o establece el prefijo de los atributos que se exportarán, la propiedad exportada no contendrá prefijo, las propiedades personalizadas con un prefijo diferente no se exportarán, el valor predeterminado es 'rvm:'. Por ejemplo, si una propiedad es rvm:Refno=345, el atributo exportado será Refno = 345, el prefijo se elimina. |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Nombre | Descripción |
| --- | --- |
| setAttributePrefix(value) | Obtiene o establece el prefijo de los atributos que se exportarán, la propiedad exportada no contendrá prefijo, las propiedades personalizadas con un prefijo diferente no se exportarán, el valor predeterminado es 'rvm:'. Por ejemplo, si una propiedad es rvm:Refno=345, el atributo exportado será Refno = 345, el prefijo se elimina. |

 **Result:**



---


### getAttributeListFile{#getAttributeListFile}

| Nombre | Descripción |
| --- | --- |
| getAttributeListFile() | Obtiene o establece el nombre de archivo de la lista de atributos, el exportador generará un nombre basado en el nombre del archivo .rvm cuando esta propiedad no esté definida, el valor predeterminado es null. |

 **Result:**



---


### setAttributeListFile{#setAttributeListFile}

| Nombre | Descripción |
| --- | --- |
| setAttributeListFile(value) | Obtiene o establece el nombre de archivo de la lista de atributos, el exportador generará un nombre basado en el nombre del archivo .rvm cuando esta propiedad no esté definida, el valor predeterminado es null. |

 **Result:**



---


### getExportAttributes{#getExportAttributes}

| Nombre | Descripción |
| --- | --- |
| getExportAttributes() | Obtiene o establece si se debe exportar la lista de atributos a un archivo .att externo, el valor predeterminado es false. |

 **Result:**



---


### setExportAttributes{#setExportAttributes}

| Nombre | Descripción |
| --- | --- |
| setExportAttributes(value) | Obtiene o establece si se debe exportar la lista de atributos a un archivo .att externo, el valor predeterminado es false. |

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



