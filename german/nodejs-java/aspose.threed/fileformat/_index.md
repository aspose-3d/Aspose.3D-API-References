---
title: "FileFormat"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

Dateiformatdefinition  @hideconstructor


## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| MAYA_BINARY | Autodesk Maya im Binärformat |
| STL_BINARY | Binäres STL-Dateiformat |
| STLASCII | ASCII STL-Dateiformat |
| COLLADA | Collada-Dateiformat |
| GLTF | glTF der Khronos Group |
| GLTF_BINARY | glTF der Khronos Group im Binärformat |
| PDF | Portable Document Format von Adobe |
| DXF | AutoCAD DXF |
| PLY | Polygon File Format oder Stanford Triangle Format |
| X_BINARY | DirectX X-Datei im Binärformat |
| X_TEXT | DirectX X-Datei im Binärformat |
| DRACO | Google Draco Mesh |
| RVM_TEXT | AVEVA Plant Design Management System Modell im Textformat |
| RVM_BINARY | AVEVA Plant Design Management System Modell im Binärformat |
| ASE | Das ASCII‑Scene‑Exporter‑Format von 3D Studio Max. |
| IFC | ISO 16739-1 Industry Foundation Classes Datenmodell. |
| AMF | Dateiformat für additive Fertigung |
| VRML | Die Virtual Reality Modeling Language |
| ZIP | Zip-Archiv, das andere 3D-Dateiformate enthält. |
| USD | Universal Scene Description |
| USDZ | Komprimierte Universal Scene Description |
| XYZ | XYZ-Punktwolken-Datei |
| PCD | PCL Point Cloud Data Datei im ASCII‑Modus |
| PCD_BINARY | PCL Point Cloud Data Datei im Binärmodus |

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


### getFormatByExtension{#getFormatByExtension}

| Name | Beschreibung |
| --- | --- |
| getFormatByExtension(extensionName) | Liest das bevorzugte Dateiformat aus dem Dateierweiterungsnamen. Der Erweiterungsname sollte mit einem Punkt ('.') beginnen. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| extensionNam | String | null |

 **Result:**
FileFormat


---


### detect{#detect}

| Name | Beschreibung |
| --- | --- |
| detect(fileName) | Ermittelt das Dateiformat anhand des Dateinamens, die Datei muss lesbar sein, damit Aspose.3D das Dateiformat über den Dateikopf erkennen kann. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
FileFormat


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



