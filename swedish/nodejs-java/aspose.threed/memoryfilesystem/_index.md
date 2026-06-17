---
title: "MemoryFileSystem"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

MemoryFileSystem mappar läs-/skrivoperationer till minnet.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| Namn | Beskrivning |
| --- | --- |
| getFileNames() | Filnamn som finns i detta minnesfilssystem. |

 **Result:**



---


### getFileContent{#getFileContent}

| Namn | Beskrivning |
| --- | --- |
| getFileContent(fileName) | Returnerar det råa innehållet i den angivna filen. Kastar System.IO.FileNotFoundException om den angivna filen inte finns. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileNam | Sträng | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| Namn | Beskrivning |
| --- | --- |
| readFile(fileName, options) | Skapa en ström för att läsa beroenden. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileNam | Sträng | null |
| alternativ | IOConfig | null |

 **Result:**
Stream


---


### writeFile{#writeFile}

| Namn | Beskrivning |
| --- | --- |
| writeFile(fileName, options) | Skapa en ström för att skriva beroenden. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileNam | Sträng | null |
| alternativ | IOConfig | null |

 **Result:**
Stream


---



