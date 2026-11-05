---
title: "Discreet3dsSaveOptions"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Opslaanopties voor 3DS-bestand.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Constructor van Discreet3dsSaveOptions. |

 **Result:**



---


### getExportLight{#getExportLight}

| Naam | Beschrijving |
| --- | --- |
| getExportLight() | Geeft of stelt in of alle lichten in de scène geëxporteerd moeten worden. |

 **Result:**



---


### setExportLight{#setExportLight}

| Naam | Beschrijving |
| --- | --- |
| setExportLight(value) | Geeft of stelt in of alle lichten in de scène geëxporteerd moeten worden. |

 **Result:**



---


### getExportCamera{#getExportCamera}

| Naam | Beschrijving |
| --- | --- |
| getExportCamera() | Geeft of stelt in of alle camera's in de scène geëxporteerd moeten worden. |

 **Result:**



---


### setExportCamera{#setExportCamera}

| Naam | Beschrijving |
| --- | --- |
| setExportCamera(value) | Geeft of stelt in of alle camera's in de scène geëxporteerd moeten worden. |

 **Result:**



---


### getDuplicatedNameSeparator{#getDuplicatedNameSeparator}

| Naam | Beschrijving |
| --- | --- |
| getDuplicatedNameSeparator() | De scheidingsteken tussen de naam van een object en de gedupliceerde teller, standaardwaarde is "_". Wanneer de scène objecten bevat die dezelfde naam gebruiken, zal de Aspose.3D 3DS-exporteur een andere naam voor het object genereren. Bijvoorbeeld er zijn twee knooppunten met de naam "Box", het eerste knooppunt krijgt de naam "Box", en het tweede knooppunt krijgt een nieuwe naam "Box_2" met de standaardconfiguratie. |

 **Result:**



---


### setDuplicatedNameSeparator{#setDuplicatedNameSeparator}

| Naam | Beschrijving |
| --- | --- |
| setDuplicatedNameSeparator(value) | De scheidingsteken tussen de naam van een object en de gedupliceerde teller, standaardwaarde is "_". Wanneer de scène objecten bevat die dezelfde naam gebruiken, zal de Aspose.3D 3DS-exporteur een andere naam voor het object genereren. Bijvoorbeeld er zijn twee knooppunten met de naam "Box", het eerste knooppunt krijgt de naam "Box", en het tweede knooppunt krijgt een nieuwe naam "Box_2" met de standaardconfiguratie. |

 **Result:**



---


### getDuplicatedNameCounterBase{#getDuplicatedNameCounterBase}

| Naam | Beschrijving |
| --- | --- |
| getDuplicatedNameCounterBase() | De teller die wordt gebruikt bij het genereren van een nieuwe naam voor gedupliceerde namen, standaardwaarde is 2. |

 **Result:**



---


### setDuplicatedNameCounterBase{#setDuplicatedNameCounterBase}

| Naam | Beschrijving |
| --- | --- |
| setDuplicatedNameCounterBase(value) | De teller die wordt gebruikt bij het genereren van een nieuwe naam voor gedupliceerde namen, standaardwaarde is 2. |

 **Result:**



---


### getDuplicatedNameCounterFormat{#getDuplicatedNameCounterFormat}

| Naam | Beschrijving |
| --- | --- |
| getDuplicatedNameCounterFormat() | Het formaat van de gedupliceerde teller, standaardwaarde is een lege string. |

 **Result:**



---


### setDuplicatedNameCounterFormat{#setDuplicatedNameCounterFormat}

| Naam | Beschrijving |
| --- | --- |
| setDuplicatedNameCounterFormat(value) | Het formaat van de gedupliceerde teller, standaardwaarde is een lege string. |

 **Result:**



---


### getMasterScale{#getMasterScale}

| Naam | Beschrijving |
| --- | --- |
| getMasterScale() | Haalt op of stelt de master‑schaal in die wordt gebruikt bij het exporteren. |

 **Result:**



---


### setMasterScale{#setMasterScale}

| Naam | Beschrijving |
| --- | --- |
| setMasterScale(value) | Haalt op of stelt de master‑schaal in die wordt gebruikt bij het exporteren. |

 **Result:**



---


### getGammaCorrectedColor{#getGammaCorrectedColor}

| Naam | Beschrijving |
| --- | --- |
| getGammaCorrectedColor() | Een 3ds‑bestand kan originele kleur en gamma‑gecorrigeerde kleur voor hetzelfde attribuut bevatten. Als u dit instelt op true, wordt de gamma‑gecorrigeerde kleur gebruikt indien mogelijk; anders zal Aspose.3D proberen de originele kleur te gebruiken. |

 **Result:**



---


### setGammaCorrectedColor{#setGammaCorrectedColor}

| Naam | Beschrijving |
| --- | --- |
| setGammaCorrectedColor(value) | Een 3ds‑bestand kan originele kleur en gamma‑gecorrigeerde kleur voor hetzelfde attribuut bevatten. Als u dit instelt op true, wordt de gamma‑gecorrigeerde kleur gebruikt indien mogelijk; anders zal Aspose.3D proberen de originele kleur te gebruiken. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Naam | Beschrijving |
| --- | --- |
| getFlipCoordinateSystem() | Haalt op of stelt het omkeren van het coördinatensysteem van controlepunten/normaal in tijdens importeren/exporteren. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Naam | Beschrijving |
| --- | --- |
| setFlipCoordinateSystem(value) | Haalt op of stelt het omkeren van het coördinatensysteem van controlepunten/normaal in tijdens importeren/exporteren. |

 **Result:**



---


### getHighPreciseColor{#getHighPreciseColor}

| Naam | Beschrijving |
| --- | --- |
| getHighPreciseColor() | Als dit true is, zal het gegenereerde 3ds‑bestand een hoge‑precisie kleur gebruiken, wat betekent dat elk kanaal van rood/groen/blauw een 32‑bit float is. Anders zal het gegenereerde bestand een 24‑bit kleur gebruiken, waarbij elk kanaal een 8‑bit byte is. De standaardwaarde is false, omdat niet alle toepassingen de hoge‑precisie kleur ondersteunen. |

 **Result:**



---


### setHighPreciseColor{#setHighPreciseColor}

| Naam | Beschrijving |
| --- | --- |
| setHighPreciseColor(value) | Als dit true is, zal het gegenereerde 3ds‑bestand een hoge‑precisie kleur gebruiken, wat betekent dat elk kanaal van rood/groen/blauw een 32‑bit float is. Anders zal het gegenereerde bestand een 24‑bit kleur gebruiken, waarbij elk kanaal een 8‑bit byte is. De standaardwaarde is false, omdat niet alle toepassingen de hoge‑precisie kleur ondersteunen. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Naam | Beschrijving |
| --- | --- |
| getExportTextures() | Probeer de in de scène gebruikte textures te kopiëren naar de uitvoermap. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Naam | Beschrijving |
| --- | --- |
| setExportTextures(value) | Probeer de in de scène gebruikte textures te kopiëren naar de uitvoermap. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Naam | Beschrijving |
| --- | --- |
| getFileFormat() | Haalt het bestandsformaat op dat is gespecificeerd in de huidige Opslaan/Laden-optie. |

 **Result:**



---


### getEncoding{#getEncoding}

| Naam | Beschrijving |
| --- | --- |
| getEncoding() | Haalt op of stelt de standaardcodering voor tekstgebaseerde bestanden in. Standaardwaarde is null, wat betekent dat de importeur/exporteur beslist welke codering te gebruiken. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Naam | Beschrijving |
| --- | --- |
| getFileSystem() | Sta de gebruiker toe om te bepalen hoe externe afhankelijkheden te beheren tijdens laden/opslaan. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Naam | Beschrijving |
| --- | --- |
| setFileSystem(value) | Sta de gebruiker toe om te bepalen hoe externe afhankelijkheden te beheren tijdens laden/opslaan. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Naam | Beschrijving |
| --- | --- |
| getLookupPaths() | Sommige bestanden, zoals OBJ, zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden. |

 **Result:**



---


### getFileName{#getFileName}

| Naam | Beschrijving |
| --- | --- |
| getFileName() | De bestandsnaam van de exporterende/importerende scène. Dit is optioneel, maar nuttig bij het serialiseren van externe assets zoals het materiaal van OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Naam | Beschrijving |
| --- | --- |
| setFileName(value) | De bestandsnaam van de exporterende/importerende scène. Dit is optioneel, maar nuttig bij het serialiseren van externe assets zoals het materiaal van OBJ. |

 **Result:**



---



