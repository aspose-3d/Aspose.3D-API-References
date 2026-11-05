---
title: "FileFormat"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

Bestandsformaatdefinitie @hideconstructor


## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| MAYA_BINARY | Autodesk Maya in binair formaat |
| STL_BINARY | Binair STL-bestandsformaat |
| STLASCII | ASCII STL-bestandsformaat |
| COLLADA | Collada-bestandsformaat |
| GLTF | glTF van de Khronos Group |
| GLTF_BINARY | glTF van de Khronos Group in binair formaat |
| PDF | Portable Document Format van Adobe |
| DXF | AutoCAD DXF |
| PLY | Polygon File Format of Stanford Triangle Format |
| X_BINARY | DirectX X-bestand in binair formaat |
| X_TEXT | DirectX X-bestand in binair formaat |
| DRACO | Google Draco Mesh |
| RVM_TEXT | AVEVA Plant Design Management System-model in tekstformaat |
| RVM_BINARY | AVEVA Plant Design Management System-model in binair formaat |
| ASE | 3D Studio Max's ASCII-scène-exportformaat. |
| IFC | ISO 16739-1 Industry Foundation Classes-gegevensmodel. |
| AMF | Bestandformaat voor additieve productie |
| VRML | De Virtual Reality Modeling Language |
| ZIP | Zip-archief dat andere 3d-bestandsformaat bevat. |
| USD | Universele Scene Beschrijving |
| USDZ | Gecomprimeerde Universele Scene Beschrijving |
| XYZ | Xyz-puntenwolkbestand |
| PCD | PCL Point Cloud Data-bestand in ASCII-modus |
| PCD_BINARY | PCL Point Cloud Data-bestand in Binaire modus |

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
| getContentType() | Haalt het inhoudstype van het bestandsformaat op. De waarde van de eigenschap is de gehele constante FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Naam | Beschrijving |
| --- | --- |
| getFileFormatType() | Haalt bestandsformaattype op. |

 **Result:**



---


### getFormatByExtension{#getFormatByExtension}

| Naam | Beschrijving |
| --- | --- |
| getFormatByExtension(extensionName) | Haalt het voorkeursbestandsformaat op basis van de extensienaam. De extensienaam moet beginnen met een punt ('.'). |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| extensionNam | String | null |

 **Result:**
FileFormat


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
FileFormat


---


### createLoadOptions{#createLoadOptions}

| Naam | Beschrijving |
| --- | --- |
| createLoadOptions() | Maak standaard laadopties voor dit bestandsformaat |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Naam | Beschrijving |
| --- | --- |
| createSaveOptions() | Maak standaard opslaanopties voor dit bestandsformaat |

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



