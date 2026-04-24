---
title: PdfFormat
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/pdfformat/
---
## PdfFormat class

Adobes Portable Document Format  @hideconstructor


## Methoden

### getVersion{#getVersion}

| Name | Beschreibung |
| --- | --- |
| getVersion() | Ermittelt die Dateiformatversion |

 **Result:**



---


### getExtension{#getExtension}

| Name | Beschreibung |
| --- | --- |
| getExtension() | Ermittelt den Erweiterungsnamen dieses Typs. |

 **Result:**



---


### getExtensions{#getExtensions}

| Name | Beschreibung |
| --- | --- |
| getExtensions() | Ermittelt die Erweiterungsnamen dieses Typs. |

 **Result:**



---


### getContentType{#getContentType}

| Name | Beschreibung |
| --- | --- |
| getContentType() | Liest den Inhaltstyp des Dateiformats. Der Wert der Eigenschaft ist die Ganzzahlkonstante FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Name | Beschreibung |
| --- | --- |
| getFileFormatType() | Ermittelt den Dateiformattyp |

 **Result:**



---


### extract{#extract}

| Name | Beschreibung |
| --- | --- |
| extract(fileName, password) | Roh‑3D‑Inhalt aus PDF‑Datei extrahieren. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileNam | String | null |
| Passwort | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### extractScene{#extractScene}

| Name | Beschreibung |
| --- | --- |
| extractScene(fileName) | 3D‑Szenen aus PDF‑Datei extrahieren. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### extractScene{#extractScene}

| Name | Beschreibung |
| --- | --- |
| extractScene(fileName, password) | 3D‑Szenen aus PDF‑Datei extrahieren. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileNam | String | null |
| Passwort | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createLoadOptions{#createLoadOptions}

| Name | Beschreibung |
| --- | --- |
| createLoadOptions() | Standard-Ladeoptionen für dieses Dateiformat erstellen |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Name | Beschreibung |
| --- | --- |
| createSaveOptions() | Standard-Speicheroptionen für dieses Dateiformat erstellen |

 **Result:**
SaveOptions


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Formate in Zeichenkette |

 **Result:**
String


---



