---
title: "MemoryFileSystem"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

Het MemoryFileSystem zal de lees-/schrijfbewerkingen naar het geheugen mappen.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| Naam | Beschrijving |
| --- | --- |
| getFileNames() | Bestandsnamen die zich in dit geheugenbestandssysteem bevinden. |

 **Result:**



---


### getFileContent{#getFileContent}

| Naam | Beschrijving |
| --- | --- |
| getFileContent(fileName) | Retourneert de ruwe inhoud van het opgegeven bestand. Gooi System.IO.FileNotFoundException als het opgegeven bestand niet bestaat. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| Naam | Beschrijving |
| --- | --- |
| readFile(fileName, options) | Maak een stream aan voor het lezen van afhankelijkheden. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileNam | String | null |
| option | IOConfig | null |

 **Result:**
Stream


---


### writeFile{#writeFile}

| Naam | Beschrijving |
| --- | --- |
| writeFile(fileName, options) | Maak een stream aan voor het schrijven van afhankelijkheden. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileNam | String | null |
| option | IOConfig | null |

 **Result:**
Stream


---



