---
title: FileFormat
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

Dateiformatdefinition  @hideconstructor


## Properties

| Name | Beschreibung |
| --- | --- |
| MAYA_BINARY | Autodesk Maya im Binärformat |
| STL_BINARY | Binäres STL-Dateiformat |
| STLASCII | ASCII STL-Dateiformat |
| COLLADA | Collada‑Dateiformat |
| GLTF | glTF der Khronos Group |
| GLTF_BINARY | glTF der Khronos Group im Binärformat |
| PDF | Adobe Portable Document Format |
| DXF | AutoCAD DXF |
| PLY | Polygon File Format oder Stanford Triangle Format |
| X_BINARY | DirectX X-Datei im Binärformat |
| X_TEXT | DirectX X-Datei im Binärformat |
| DRACO | Google Draco Mesh |
| RVM_TEXT | AVEVA Plant Design Management System Modell im Textformat |
| RVM_BINARY | AVEVA Plant Design Management System Modell im Binärformat |
| ASE | ASCII‑Szenenexporter‑Format von 3D Studio Max. |
| IFC | ISO 16739-1 Industry Foundation Classes Datenmodell. |
| AMF | Dateiformat für additive Fertigung |
| VRML | Die Virtual Reality Modeling Language |
| ZIP | Zip-Archiv, das andere 3D-Dateiformate enthält. |
| USD | Universelle Szenenbeschreibung |
| USDZ | Komprimierte Universelle Szenenbeschreibung |
| XYZ | Xyz-Punktwolken-Datei |
| PCD | PCL Point Cloud Data-Datei im ASCII-Modus |
| PCD_BINARY | PCL Point Cloud Data-Datei im Binärmodus |

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


### getFormatByExtension{#getFormatByExtension}

| Name | Beschreibung |
| --- | --- |
| getFormatByExtension(extensionName) | Ermittelt das bevorzugte Dateiformat anhand des Dateierweiterungsnamens. Der Erweiterungsname sollte mit einem Punkt ('.') beginnen. |

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
| detect(fileName) | Erkennen Sie das Dateiformat anhand des Dateinamens, die Datei muss lesbar sein, damit Aspose.3D das Dateiformat über den Dateikopf erkennen kann. |

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



