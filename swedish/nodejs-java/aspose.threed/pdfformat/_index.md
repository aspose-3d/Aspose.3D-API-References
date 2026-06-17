---
title: "PdfFormat"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/pdfformat/
---
## PdfFormat class

Adobes Portable Document Format  @hideconstructor


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


### extract{#extract}

| Namn | Beskrivning |
| --- | --- |
| extract(fileName, password) | Extrahera rå 3D-innehåll från PDF-fil. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileNam | Sträng | null |
| lösenord | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### extractScene{#extractScene}

| Namn | Beskrivning |
| --- | --- |
| extractScene(fileName) | Extrahera 3D-scener från PDF-fil. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileNam | Sträng | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### extractScene{#extractScene}

| Namn | Beskrivning |
| --- | --- |
| extractScene(fileName, password) | Extrahera 3D-scener från PDF-fil. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileNam | Sträng | null |
| lösenord | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


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



