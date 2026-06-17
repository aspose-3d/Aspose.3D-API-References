---
title: "DracoFormat"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Google Draco-format  @hideconstructor


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


### decode{#decode}

| Namn | Beskrivning |
| --- | --- |
| decode(fileName) | Dekoda punktmolnet eller meshen från angivet filnamn |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileName | Sträng | Filnamnet innehåller drc-filen |

 **Result:**
Geometry


---


### decode{#decode}

| Namn | Beskrivning |
| --- | --- |
| decode(data) | Dekoda punktmolnet eller meshen från minnesdata |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | De råa drc-byterna |

 **Result:**
Geometry


---


### encode{#encode}

| Namn | Beskrivning |
| --- | --- |
| encode(entity, fileName, options) | Koda enheten till angiven fil |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| entitet | Entitet | Entiteten som ska kodas |
| fileName | Sträng | Filnamnet som ska skrivas |
| alternativ | DracoSaveOptions | Extra alternativ för kodning av punktmolnet |

 **Result:**
Geometry


---


### encode{#encode}

| Namn | Beskrivning |
| --- | --- |
| encode(entity, options) | Koda enheten till Draco rådata |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| entitet | Entitet | Entiteten som ska kodas |
| alternativ | DracoSaveOptions | Extra alternativ för kodning av punktmolnet |

 **Result:**
byte[]


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



