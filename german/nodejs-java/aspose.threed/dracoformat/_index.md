---
title: DracoFormat
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Google‑Draco‑Format  @hideconstructor


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


### decode{#decode}

| Name | Beschreibung |
| --- | --- |
| decode(fileName) | Dekodieren Sie die Punktwolke oder das Mesh aus dem angegebenen Dateinamen. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Der Dateiname enthält die drc‑Datei. |

 **Result:**
Geometry


---


### decode{#decode}

| Name | Beschreibung |
| --- | --- |
| decode(data) | Dekodieren Sie die Punktwolke oder das Mesh aus dem Speicherinhalt. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die rohen drc‑Bytes |

 **Result:**
Geometry


---


### encode{#encode}

| Name | Beschreibung |
| --- | --- |
| encode(entity, fileName, options) | Kodieren Sie das Objekt in die angegebene Datei. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| entity | Entity | Das zu kodierende Objekt. |
| fileName | String | Der zu schreibende Dateiname. |
| options | DracoSaveOptions | Zusätzliche Optionen für die Kodierung der Punktwolke. |

 **Result:**
Geometry


---


### encode{#encode}

| Name | Beschreibung |
| --- | --- |
| encode(entity, options) | Kodieren Sie das Objekt in rohe Draco‑Daten. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| entity | Entity | Das zu kodierende Objekt. |
| options | DracoSaveOptions | Zusätzliche Optionen für die Kodierung der Punktwolke. |

 **Result:**
byte[]


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



