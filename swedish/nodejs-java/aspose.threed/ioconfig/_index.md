---
title: "IOConfig"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/ioconfig/
---
## IOConfig class

IO-konfiguration för serialisering/deserialisering.  Användaren kan ange detaljerade konfigurationer som beroendeuppslagningsväg  Eller formatrelaterade konfigurationer här  @hideconstructor


## Metoder

### getFileSystemFactory{#getFileSystemFactory}

| Namn | Beskrivning |
| --- | --- |
| getFileSystemFactory() | Hämtar eller anger fabrikklassen för FileSystem. Standardfabriken skapar LocalFileSystem som inte är lämplig för servermiljö. |

 **Result:**



---


### setFileSystemFactory{#setFileSystemFactory}

| Namn | Beskrivning |
| --- | --- |
| setFileSystemFactory(value) | Hämtar eller anger fabrikklassen för FileSystem. Standardfabriken skapar LocalFileSystem som inte är lämplig för servermiljö. |

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



