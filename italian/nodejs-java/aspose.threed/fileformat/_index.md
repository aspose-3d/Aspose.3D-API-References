---
title: "FileFormat"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

Definizione del formato file  @hideconstructor


## Proprietà

| Nome | Descrizione |
| --- | --- |
| MAYA_BINARY | Autodesk Maya in formato binario |
| STL_BINARY | Formato file STL binario |
| STLASCII | Formato file STL ASCII |
| COLLADA | Formato file Collada |
| GLTF | glTF di Khronos Group |
| GLTF_BINARY | glTF di Khronos Group in formato binario |
| PDF | Formato Documento Portatile di Adobe |
| DXF | AutoCAD DXF |
| PLY | Formato file poligonale o Formato triangolare di Stanford |
| X_BINARY | File DirectX X in formato binario |
| X_TEXT | File DirectX X in formato binario |
| DRACO | Mesh Draco di Google |
| RVM_TEXT | Modello del sistema di gestione della progettazione di impianti AVEVA in formato testo |
| RVM_BINARY | Modello del sistema di gestione della progettazione di impianti AVEVA in formato binario |
| ASE | Formato ASCII Scene Exporter di 3D Studio Max. |
| IFC | Modello di dati Industry Foundation Classes ISO 16739-1. |
| AMF | Formato file per la manifattura additiva |
| VRML | Il Linguaggio di Modellazione per la Realtà Virtuale |
| ZIP | Archivio Zip che contiene altri formati di file 3D. |
| USD | Descrizione Universale della Scena |
| USDZ | Descrizione Universale della Scena compressa |
| XYZ | File di nuvola di punti Xyz |
| PCD | File PCL Point Cloud Data in modalità ASCII |
| PCD_BINARY | File PCL Point Cloud Data in modalità binaria |

## Metodi

### getVersion{#getVersion}

| Nome | Descrizione |
| --- | --- |
| getVersion() | Restituisce la versione del formato file |

 **Result:**



---


### getExtension{#getExtension}

| Nome | Descrizione |
| --- | --- |
| getExtension() | Restituisce il nome dell'estensione di questo tipo. |

 **Result:**



---


### getExtensions{#getExtensions}

| Nome | Descrizione |
| --- | --- |
| getExtensions() | Restituisce i nomi delle estensioni di questo tipo. |

 **Result:**



---


### getContentType{#getContentType}

| Nome | Descrizione |
| --- | --- |
| getContentType() | Restituisce il tipo di contenuto del formato file. Il valore della proprietà è la costante intera FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Nome | Descrizione |
| --- | --- |
| getFileFormatType() | Restituisce il tipo di formato file |

 **Result:**



---


### getFormatByExtension{#getFormatByExtension}

| Nome | Descrizione |
| --- | --- |
| getFormatByExtension(extensionName) | Restituisce il formato file preferito dal nome dell'estensione. Il nome dell'estensione deve iniziare con un punto ('.'). |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| extensionNam | String | null |

 **Result:**
FileFormat


---


### detect{#detect}

| Nome | Descrizione |
| --- | --- |
| detect(fileName) | Rileva il formato file dal nome del file; il file deve essere leggibile affinché Aspose.3D possa rilevare il formato file tramite l'intestazione del file. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
FileFormat


---


### createLoadOptions{#createLoadOptions}

| Nome | Descrizione |
| --- | --- |
| createLoadOptions() | Crea un'opzione di caricamento predefinita per questo formato file |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Nome | Descrizione |
| --- | --- |
| createSaveOptions() | Crea un'opzione di salvataggio predefinita per questo formato file |

 **Result:**
SaveOptions


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Formati in stringa |

 **Result:**
String


---



