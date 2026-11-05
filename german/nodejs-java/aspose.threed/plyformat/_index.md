---
title: "PlyFormat"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
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
| getVersion() | Gibt die Dateiformatversion zurück |

 **Result:**



---


### getExtension{#getExtension}

| Name | Beschreibung |
| --- | --- |
| getExtension() | Gibt den Erweiterungsnamen dieses Typs zurück. |

 **Result:**



---


### getExtensions{#getExtensions}

| Name | Beschreibung |
| --- | --- |
| getExtensions() | Gibt die Erweiterungsnamen dieses Typs zurück. |

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
| getFileFormatType() | Liest den Dateiformattyp |

 **Result:**



---


### encode{#encode}

| Name | Beschreibung |
| --- | --- |
| encode(entity, fileName) | Kodiert das Entity und speichert das Ergebnis in einer externen Datei. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Das zu kodierende Entity. |
| fileName | String | Die Datei, in die geschrieben werden soll |

 **Result:**



---


### encode{#encode}

| Name | Beschreibung |
| --- | --- |
| encode(entity, fileName, opt) | Kodiert das Entity und speichert das Ergebnis in einer externen Datei. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Das zu kodierende Entity. |
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
| createLoadOptions() | Erstellt Standard-Ladeoptionen für dieses Dateiformat |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Name | Beschreibung |
| --- | --- |
| createSaveOptions() | Erstellt Standard-Speicheroptionen für dieses Dateiformat |

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



