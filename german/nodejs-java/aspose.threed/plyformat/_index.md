---
title: PlyFormat
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

Das PLY-Format.  @hideconstructor


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


### encode{#encode}

| Name | Beschreibung |
| --- | --- |
| encode(entity, fileName) | Kodieren Sie die Entität und speichern Sie das Ergebnis in einer externen Datei. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| entity | Entity | Die zu kodierende Entität |
| fileName | String | Die Datei, in die geschrieben werden soll |

 **Result:**



---


### encode{#encode}

| Name | Beschreibung |
| --- | --- |
| encode(entity, fileName, opt) | Kodieren Sie die Entität und speichern Sie das Ergebnis in einer externen Datei. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| entity | Entity | Die zu kodierende Entität |
| fileName | String | Die Datei, in die geschrieben werden soll |
| opt | PlySaveOptions | Speicheroptionen |

 **Result:**



---


### decode{#decode}

| Name | Beschreibung |
| --- | --- |
| decode(fileName) | Dekodiere eine Punktwolke oder ein Mesh aus dem angegebenen Stream. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Der Eingabestream |

 **Result:**
Geometry


---


### decode{#decode}

| Name | Beschreibung |
| --- | --- |
| decode(fileName, opt) | Dekodiere eine Punktwolke oder ein Mesh aus dem angegebenen Stream. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Der Eingabestream |
| opt | PlyLoadOptions | Die Ladeoption des PLY-Formats |

 **Result:**
Geometry


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



