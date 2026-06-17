---
title: "Bestandsformaat"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

Bestandsformaatdefinitie @hideconstructor


## Properties

| Naam | Beschrijving |
| --- | --- |
| MAYA_BINARY | Autodesk Maya in binair formaat |
| STL_BINARY | Binair STL-bestandsformaat |
| STLASCII | ASCII STL-bestandsformaat |
| COLLADA | Collada-bestandsformaat |
| GLTF | glTF van Khronos Group |
| GLTF_BINARY | glTF van Khronos Group in binair formaat |
| PDF | Portable Document Format van Adobe |
| DXF | AutoCAD DXF |
| PLY | Polygon File Format of Stanford Triangle Format |
| X_BINARY | DirectX X-bestand in binair formaat |
| X_TEXT | DirectX X-bestand in binair formaat |
| DRACO | Google Draco Mesh |
| RVM_TEXT | AVEVA Plant Design Management System Model in tekstformaat |
| RVM_BINARY | AVEVA Plant Design Management System Model in binair formaat |
| ASE | 3D Studio Max's ASCII Scene Exporter-formaat. |
| IFC | ISO 16739-1 Industry Foundation Classes-gegevensmodel. |
| AMF | Additive manufacturing-bestandformaat |
| VRML | De Virtual Reality Modeling Language |
| ZIP | Zip-archief dat andere 3d-bestandsformaten bevat. |
| USD | Universele Scenebeschrijving |
| USDZ | Gecomprimeerde Universele Scenebeschrijving |
| XYZ | Xyz-puntwolkbestand |
| PCD | PCL Point Cloud Data-bestand in ASCII-modus |
| PCD_BINARY | PCL Point Cloud Data-bestand in binaire modus |

## Methoden

### getVersion{#getVersion}

| Naam | Beschrijving |
| --- | --- |
| getVersion() | Haalt bestandsformaatversie op |

 **Result:**



---


### getExtension{#getExtension}

| Naam | Beschrijving |
| --- | --- |
| getExtension() | Haalt de extensienaam van dit type op. |

 **Result:**



---


### getExtensions{#getExtensions}

| Naam | Beschrijving |
| --- | --- |
| getExtensions() | Haalt de extensienamen van dit type op. |

 **Result:**



---


### getContentType{#getContentType}

| Naam | Beschrijving |
| --- | --- |
| getContentType() | Haalt bestandsformaatinhoudstype op. De waarde van de eigenschap is de integer‑constante FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Naam | Beschrijving |
| --- | --- |
| getFileFormatType() | Haalt bestandsformaattype op |

 **Result:**



---


### getFormatByExtension{#getFormatByExtension}

| Naam | Beschrijving |
| --- | --- |
| getFormatByExtension(extensionName) | Haalt het voorkeursbestandsformaat op basis van de bestandsextensie. De extensienaam moet beginnen met een punt ('.'). |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| extensionNam | String | null |

 **Result:**
Bestandsformaat


---


### detect{#detect}

| Naam | Beschrijving |
| --- | --- |
| detect(fileName) | Detecteer het bestandsformaat op basis van de bestandsnaam; het bestand moet leesbaar zijn zodat Aspose.3D het bestandsformaat via de bestandsheader kan detecteren. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
Bestandsformaat


---


### createLoadOptions{#createLoadOptions}

| Naam | Beschrijving |
| --- | --- |
| createLoadOptions() | Maak standaard laadopties voor dit bestandsformaat. |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Naam | Beschrijving |
| --- | --- |
| createSaveOptions() | Maak standaard opslagopties voor dit bestandsformaat. |

 **Result:**
SaveOptions


---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() | Formaten naar tekenreeks |

 **Result:**
String


---



