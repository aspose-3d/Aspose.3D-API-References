---
title: "RvmFormat"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/rvmformat/
---
## RvmFormat class

RVM-formatet  @hideconstructor


## Metoder

### getVersion{#getVersion}

| Namn | Beskrivning |
| --- | --- |
| getVersion() | Hämtar filformatversion |

 **Result:**



---


### getExtension{#getExtension}

| Namn | Beskrivning |
| --- | --- |
| getExtension() | Hämtar filändelsens namn för den här typen. |

 **Result:**



---


### getExtensions{#getExtensions}

| Namn | Beskrivning |
| --- | --- |
| getExtensions() | Hämtar filändelserna för den här typen. |

 **Result:**



---


### getContentType{#getContentType}

| Namn | Beskrivning |
| --- | --- |
| getContentType() | Hämtar filformatets innehållstyp. Värdet på egenskapen är heltalskonstanten FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Namn | Beskrivning |
| --- | --- |
| getFileFormatType() | Hämtar filformattyp |

 **Result:**



---


### loadAttributes{#loadAttributes}

| Namn | Beskrivning |
| --- | --- |
| loadAttributes(scene, fileName, prefix) | Läs in attributen från angivet filnamn |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| scen | Scene | Scenen där attributen kommer att tillämpas på |
| fileName | Sträng | Filens namn som innehåller attributen |
| prefix | Sträng | Prefixet för attributen som används för att undvika namnkonflikter, standardvärdet är "rvm:" |

 **Result:**



---


### createLoadOptions{#createLoadOptions}

| Namn | Beskrivning |
| --- | --- |
| createLoadOptions() | Skapa standardalternativ för inläsning för detta filformat. |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Namn | Beskrivning |
| --- | --- |
| createSaveOptions() | Skapa standardalternativ för sparning för detta filformat. |

 **Result:**
SaveOptions


---


### toString{#toString}

| Namn | Beskrivning |
| --- | --- |
| toString() | Formaterar till sträng |

 **Result:**
Sträng


---



