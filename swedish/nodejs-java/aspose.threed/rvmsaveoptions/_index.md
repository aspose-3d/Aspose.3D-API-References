---
title: "RvmSaveOptions"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/rvmsaveoptions/
---
## RvmSaveOptions class

Sparaalternativ för Aveva PDMS RVM-fil.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Konstruktor för RvmSaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(contentType) | Konstruktor för RvmSaveOptions |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFileNote{#getFileNote}

| Namn | Beskrivning |
| --- | --- |
| getFileNote() | Filanteckning i filhuvudet. |

 **Result:**



---


### setFileNote{#setFileNote}

| Namn | Beskrivning |
| --- | --- |
| setFileNote(value) | Filanteckning i filhuvudet. |

 **Result:**



---


### getAuthor{#getAuthor}

| Namn | Beskrivning |
| --- | --- |
| getAuthor() |  |

 **Result:**



---


### setAuthor{#setAuthor}

| Namn | Beskrivning |
| --- | --- |
| setAuthor(value) |  |

 **Result:**



---


### getCreationTime{#getCreationTime}

| Namn | Beskrivning |
| --- | --- |
| getCreationTime() | Tidsstämpeln som exporterade den här filen, standardvärdet är aktuell tid. |

 **Result:**



---


### setCreationTime{#setCreationTime}

| Namn | Beskrivning |
| --- | --- |
| setCreationTime(value) | Tidsstämpeln som exporterade den här filen, standardvärdet är aktuell tid. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Namn | Beskrivning |
| --- | --- |
| getAttributePrefix() | Hämtar eller anger prefixet för vilka attribut som ska exporteras, den exporterade egenskapen kommer inte att innehålla något prefix, anpassade egenskaper med annat prefix exporteras inte, standardvärdet är 'rvm:'. Till exempel om en egenskap är rvm:Refno=345, kommer det exporterade attributet att vara Refno = 345, prefixet tas bort. |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Namn | Beskrivning |
| --- | --- |
| setAttributePrefix(value) | Hämtar eller anger prefixet för vilka attribut som ska exporteras, den exporterade egenskapen kommer inte att innehålla något prefix, anpassade egenskaper med annat prefix exporteras inte, standardvärdet är 'rvm:'. Till exempel om en egenskap är rvm:Refno=345, kommer det exporterade attributet att vara Refno = 345, prefixet tas bort. |

 **Result:**



---


### getAttributeListFile{#getAttributeListFile}

| Namn | Beskrivning |
| --- | --- |
| getAttributeListFile() | Hämtar eller anger filnamnet för attributlistfilen, exportören kommer att generera ett namn baserat på .rvm-filnamnet när denna egenskap är odefinierad, standardvärdet är null. |

 **Result:**



---


### setAttributeListFile{#setAttributeListFile}

| Namn | Beskrivning |
| --- | --- |
| setAttributeListFile(value) | Hämtar eller anger filnamnet för attributlistfilen, exportören kommer att generera ett namn baserat på .rvm-filnamnet när denna egenskap är odefinierad, standardvärdet är null. |

 **Result:**



---


### getExportAttributes{#getExportAttributes}

| Namn | Beskrivning |
| --- | --- |
| getExportAttributes() | Hämtar eller anger huruvida attributlistan ska exporteras till en extern .att-fil, standardvärdet är false. |

 **Result:**



---


### setExportAttributes{#setExportAttributes}

| Namn | Beskrivning |
| --- | --- |
| setExportAttributes(value) | Hämtar eller anger huruvida attributlistan ska exporteras till en extern .att-fil, standardvärdet är false. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Namn | Beskrivning |
| --- | --- |
| getExportTextures() | Försök att kopiera texturer som används i scenen till utdatamappen. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Namn | Beskrivning |
| --- | --- |
| setExportTextures(value) | Försök att kopiera texturer som används i scenen till utdatamappen. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Namn | Beskrivning |
| --- | --- |
| getFileFormat() | Hämtar filformatet som anges i aktuellt Spara/Ladda-alternativ. |

 **Result:**



---


### getEncoding{#getEncoding}

| Namn | Beskrivning |
| --- | --- |
| getEncoding() | Hämtar eller anger standardkodning för textbaserade filer. Standardvärdet är null, vilket betyder att importören/exportören bestämmer vilken kodning som ska användas. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Namn | Beskrivning |
| --- | --- |
| getFileSystem() | Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Namn | Beskrivning |
| --- | --- |
| setFileSystem(value) | Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Namn | Beskrivning |
| --- | --- |
| getLookupPaths() | Vissa filer, som OBJ, är beroende av externa filer; sökvägarna gör det möjligt för Aspose.3D att leta efter externa filer att ladda. |

 **Result:**



---


### getFileName{#getFileName}

| Namn | Beskrivning |
| --- | --- |
| getFileName() | Filnamnet för den exporterade/importerade scenen. Detta är valfritt, men användbart när externa resurser som OBJ:s material serialiseras. |

 **Result:**



---


### setFileName{#setFileName}

| Namn | Beskrivning |
| --- | --- |
| setFileName(value) | Filnamnet för den exporterade/importerade scenen. Detta är valfritt, men användbart när externa resurser som OBJ:s material serialiseras. |

 **Result:**



---



