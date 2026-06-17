---
title: "Filformat"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

Filformatdefinition  @hideconstructor


## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| MAYA_BINARY | Autodesk Maya i binärt format |
| STL_BINARY | Binärt STL-filformat |
| STLASCII | ASCII STL-filformat |
| COLLADA | Collada-filformat |
| GLTF | Khronos Groups glTF |
| GLTF_BINARY | Khronos Groups glTF i binärt format |
| PDF | Adobes Portable Document Format |
| DXF | AutoCAD DXF |
| PLY | Polygonfilformat eller Stanford Triangle Format |
| X_BINARY | DirectX X-fil i binärt format |
| X_TEXT | DirectX X-fil i binärt format |
| DRACO | Google Draco Mesh |
| RVM_TEXT | AVEVA Plant Design Management System-modell i textformat |
| RVM_BINARY | AVEVA Plant Design Management System-modell i binärformat |
| ASE | 3D Studio Max:s ASCII Scene Exporter-format. |
| IFC | ISO 16739-1 Industry Foundation Classes-datamodell. |
| AMF | Additiv tillverkningsfilformat |
| VRML | Det virtuella verklighetsmodellspråket |
| ZIP | Zip-arkiv som innehåller andra 3d-filformat. |
| USD | Universell scenbeskrivning |
| USDZ | Komprimerad universell scenbeskrivning |
| XYZ | Xyz-punktmolnsfil |
| PCD | PCL Point Cloud Data-fil i ASCII-läge |
| PCD_BINARY | PCL Point Cloud Data-fil i binärt läge |

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


### getFormatByExtension{#getFormatByExtension}

| Namn | Beskrivning |
| --- | --- |
| getFormatByExtension(extensionName) | Hämtar det föredragna filformatet från filändelsen. Filändelsen bör börja med en punkt ('.'). |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| extensionNam | Sträng | null |

 **Result:**
Filformat


---


### detect{#detect}

| Namn | Beskrivning |
| --- | --- |
| detect(fileName) | Detektera filformatet från filnamnet, filen måste vara läsbar så att Aspose.3D kan identifiera filformatet via filhuvudet. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileNam | Sträng | null |

 **Result:**
Filformat


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



