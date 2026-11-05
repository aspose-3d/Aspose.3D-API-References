---
title: "MemoryFileSystem"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

Das MemoryFileSystem mappt die Lese-/Schreibvorgänge in den Speicher.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| Name | Beschreibung |
| --- | --- |
| getFileNames() | Dateinamen, die in diesem MemoryFileSystem vorhanden sind. |

 **Result:**



---


### getFileContent{#getFileContent}

| Name | Beschreibung |
| --- | --- |
| getFileContent(fileName) | Gibt den Rohinhalt der angegebenen Datei zurück. Wirft System.IO.FileNotFoundException, wenn die angegebene Datei nicht existiert. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| Name | Beschreibung |
| --- | --- |
| readFile(fileName, options) | Erstellt einen Stream zum Lesen von Abhängigkeiten. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileNam | String | null |
| option | IOConfig | null |

 **Result:**
Stream


---


### writeFile{#writeFile}

| Name | Beschreibung |
| --- | --- |
| writeFile(fileName, options) | Erstellt einen Stream zum Schreiben von Abhängigkeiten. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileNam | String | null |
| option | IOConfig | null |

 **Result:**
Stream


---



