---
title: "PlyFormat"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

PLY-formatet.  @hideconstructor


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


### encode{#encode}

| Namn | Beskrivning |
| --- | --- |
| encode(entity, fileName) | Koda enheten och spara resultatet i en extern fil. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| entitet | Entitet | Entiteten att koda |
| fileName | Sträng | Filen att skriva till |

 **Result:**



---


### encode{#encode}

| Namn | Beskrivning |
| --- | --- |
| encode(entity, fileName, opt) | Koda enheten och spara resultatet i en extern fil. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| entitet | Entitet | Entiteten att koda |
| fileName | Sträng | Filen att skriva till |
| opt | PlySaveOptions | Spara alternativ |

 **Result:**



---


### decode{#decode}

| Namn | Beskrivning |
| --- | --- |
| decode(fileName) | Dekoda ett punktmoln eller nät från den angivna strömmen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileName | Sträng | Inmatningsströmmen |

 **Result:**
Geometry


---


### decode{#decode}

| Namn | Beskrivning |
| --- | --- |
| decode(fileName, opt) | Dekoda ett punktmoln eller nät från den angivna strömmen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileName | Sträng | Inmatningsströmmen |
| opt | PlyLoadOptions | Laddningsalternativ för PLY-format |

 **Result:**
Geometry


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



