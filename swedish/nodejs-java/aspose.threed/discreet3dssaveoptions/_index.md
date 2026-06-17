---
title: "Discreet3dsSaveOptions"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Sparaalternativ för 3DS-fil.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Konstruktor för Discreet3dsSaveOptions |

 **Result:**



---


### getExportLight{#getExportLight}

| Namn | Beskrivning |
| --- | --- |
| getExportLight() | Hämtar eller anger om alla ljus i scenen ska exporteras. |

 **Result:**



---


### setExportLight{#setExportLight}

| Namn | Beskrivning |
| --- | --- |
| setExportLight(value) | Hämtar eller anger om alla ljus i scenen ska exporteras. |

 **Result:**



---


### getExportCamera{#getExportCamera}

| Namn | Beskrivning |
| --- | --- |
| getExportCamera() | Hämtar eller anger om alla kameror i scenen ska exporteras. |

 **Result:**



---


### setExportCamera{#setExportCamera}

| Namn | Beskrivning |
| --- | --- |
| setExportCamera(value) | Hämtar eller anger om alla kameror i scenen ska exporteras. |

 **Result:**



---


### getDuplicatedNameSeparator{#getDuplicatedNameSeparator}

| Namn | Beskrivning |
| --- | --- |
| getDuplicatedNameSeparator() | Separatorn mellan objektets namn och den duplicerade räknaren, standardvärdet är "_". När scenen innehåller objekt som använder samma namn kommer Aspose.3D 3DS-exportören att generera ett annat namn för objektet. Till exempel finns det två noder med namnet "Box", den första noden får namnet "Box" och den andra noden får ett nytt namn "Box_2" med standardkonfigurationen. |

 **Result:**



---


### setDuplicatedNameSeparator{#setDuplicatedNameSeparator}

| Namn | Beskrivning |
| --- | --- |
| setDuplicatedNameSeparator(value) | Separatorn mellan objektets namn och den duplicerade räknaren, standardvärdet är "_". När scenen innehåller objekt som använder samma namn kommer Aspose.3D 3DS-exportören att generera ett annat namn för objektet. Till exempel finns det två noder med namnet "Box", den första noden får namnet "Box" och den andra noden får ett nytt namn "Box_2" med standardkonfigurationen. |

 **Result:**



---


### getDuplicatedNameCounterBase{#getDuplicatedNameCounterBase}

| Namn | Beskrivning |
| --- | --- |
| getDuplicatedNameCounterBase() | Räknaren som används för att generera nya namn för duplicerade namn, standardvärdet är 2. |

 **Result:**



---


### setDuplicatedNameCounterBase{#setDuplicatedNameCounterBase}

| Namn | Beskrivning |
| --- | --- |
| setDuplicatedNameCounterBase(value) | Räknaren som används för att generera nya namn för duplicerade namn, standardvärdet är 2. |

 **Result:**



---


### getDuplicatedNameCounterFormat{#getDuplicatedNameCounterFormat}

| Namn | Beskrivning |
| --- | --- |
| getDuplicatedNameCounterFormat() | Formatet för den duplicerade räknaren, standardvärdet är en tom sträng. |

 **Result:**



---


### setDuplicatedNameCounterFormat{#setDuplicatedNameCounterFormat}

| Namn | Beskrivning |
| --- | --- |
| setDuplicatedNameCounterFormat(value) | Formatet för den duplicerade räknaren, standardvärdet är en tom sträng. |

 **Result:**



---


### getMasterScale{#getMasterScale}

| Namn | Beskrivning |
| --- | --- |
| getMasterScale() | Hämtar eller anger huvudskalan som används vid export. |

 **Result:**



---


### setMasterScale{#setMasterScale}

| Namn | Beskrivning |
| --- | --- |
| setMasterScale(value) | Hämtar eller anger huvudskalan som används vid export. |

 **Result:**



---


### getGammaCorrectedColor{#getGammaCorrectedColor}

| Namn | Beskrivning |
| --- | --- |
| getGammaCorrectedColor() | En 3ds-fil kan innehålla originalfärg och gamma‑korrigerad färg för samma attribut. Att sätta detta till true kommer att använda den gamma‑korrigerade färgen om möjligt, annars kommer Aspose.3D att försöka använda originalfärgen. |

 **Result:**



---


### setGammaCorrectedColor{#setGammaCorrectedColor}

| Namn | Beskrivning |
| --- | --- |
| setGammaCorrectedColor(value) | En 3ds-fil kan innehålla originalfärg och gamma‑korrigerad färg för samma attribut. Att sätta detta till true kommer att använda den gamma‑korrigerade färgen om möjligt, annars kommer Aspose.3D att försöka använda originalfärgen. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Namn | Beskrivning |
| --- | --- |
| getFlipCoordinateSystem() | Hämtar eller anger vändning av koordinatsystemet för kontrollpunkter/normaler under import/export. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Namn | Beskrivning |
| --- | --- |
| setFlipCoordinateSystem(value) | Hämtar eller anger vändning av koordinatsystemet för kontrollpunkter/normaler under import/export. |

 **Result:**



---


### getHighPreciseColor{#getHighPreciseColor}

| Namn | Beskrivning |
| --- | --- |
| getHighPreciseColor() | Om detta är true kommer den genererade 3ds-filen att använda högprecis färg, vilket betyder att varje kanal för röd/grön/blå är i 32‑bit flyttal. Annars kommer den genererade filen att använda 24‑bit färg, varje kanal använder 8‑bit byte. Standardvärdet är false, eftersom inte alla program stödjer högprecis färg. |

 **Result:**



---


### setHighPreciseColor{#setHighPreciseColor}

| Namn | Beskrivning |
| --- | --- |
| setHighPreciseColor(value) | Om detta är true kommer den genererade 3ds-filen att använda högprecis färg, vilket betyder att varje kanal för röd/grön/blå är i 32‑bit flyttal. Annars kommer den genererade filen att använda 24‑bit färg, varje kanal använder 8‑bit byte. Standardvärdet är false, eftersom inte alla program stödjer högprecis färg. |

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



