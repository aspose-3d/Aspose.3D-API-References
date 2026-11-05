---
title: "DracoFormat"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Google Draco-Format  @hideconstructor


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


### decode{#decode}

| Name | Beschreibung |
| --- | --- |
| decode(fileName) | Dekodiere die Punktwolke oder das Mesh aus dem angegebenen Dateinamen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Der Dateiname enthält die drc-Datei |

 **Result:**
Geometry


---


### decode{#decode}

| Name | Beschreibung |
| --- | --- |
| decode(data) | Dekodiere die Punktwolke oder das Mesh aus den Speicherdaten |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die rohen drc-Bytes |

 **Result:**
Geometry


---


### encode{#encode}

| Name | Beschreibung |
| --- | --- |
| encode(entity, fileName, options) | Kodieren Sie die Entität in die angegebene Datei |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Die zu kodierende Entität |
| fileName | String | Der zu schreibende Dateiname |
| Optionen | DracoSaveOptions | Zusätzliche Optionen zum Kodieren der Punktwolke |

 **Result:**
Geometry


---


### encode{#encode}

| Name | Beschreibung |
| --- | --- |
| encode(entity, options) | Kodieren Sie die Entität in rohe Draco-Daten |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Die zu kodierende Entität |
| Optionen | DracoSaveOptions | Zusätzliche Optionen zum Kodieren der Punktwolke |

 **Result:**
byte[]


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



