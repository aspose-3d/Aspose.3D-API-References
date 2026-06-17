---
title: "MemoryFileSystem"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

El MemoryFileSystem asignará las operaciones de lectura/escritura a la memoria.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| Nombre | Descripción |
| --- | --- |
| getFileNames() | Nombres de archivo que se encuentran en este sistema de archivos en memoria. |

 **Result:**



---


### getFileContent{#getFileContent}

| Nombre | Descripción |
| --- | --- |
| getFileContent(fileName) | Devuelve el contenido bruto del archivo especificado. Lanza System.IO.FileNotFoundException si el archivo especificado no existe. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileNam | Cadena | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| Nombre | Descripción |
| --- | --- |
| readFile(fileName, options) | Crea un flujo para leer dependencias. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileNam | Cadena | null |
| opción | IOConfig | null |

 **Result:**
Stream


---


### writeFile{#writeFile}

| Nombre | Descripción |
| --- | --- |
| writeFile(fileName, options) | Crea un flujo para escribir dependencias. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileNam | Cadena | null |
| opción | IOConfig | null |

 **Result:**
Stream


---



