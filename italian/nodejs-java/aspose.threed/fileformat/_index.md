---
title: "FormatoFile"
second_title: "Aspose.3D per Node.js via Java API Reference"
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
| GLTF | glTF del Khronos Group |
| GLTF_BINARY | glTF del Khronos Group in formato binario |
| PDF | Formato documento portatile di Adobe |
| DXF | AutoCAD DXF |
| PLY | Formato file Poligono o Formato Triangolo Stanford |
| X_BINARY | File X DirectX in formato binario |
| X_TEXT | File X DirectX in formato binario |
| DRACO | Mesh Draco di Google |
| RVM_TEXT | Modello del sistema di gestione della progettazione di impianti AVEVA in formato testo |
| RVM_BINARY | Modello del sistema di gestione della progettazione di impianti AVEVA in formato binario |
| ASE | Formato ASCII Scene Exporter di 3D Studio Max. |
| IFC | Modello di dati ISO 16739-1 Industry Foundation Classes. |
| AMF | Formato file per la manifattura additiva |
| VRML | Il Linguaggio di Modellazione per la Realtà Virtuale |
| ZIP | Archivio Zip che contiene altri formati di file 3d. |
| USD | Descrizione Universale della Scena |
| USDZ | Descrizione Universale della Scena compressa |
| XYZ | File di nuvola di punti Xyz |
| PCD | File PCL Point Cloud Data in modalità ASCII |
| PCD_BINARY | File PCL Point Cloud Data in modalità binaria |

## Metodi

### getVersion{#getVersion}

| Nome | Descrizione |
| --- | --- |
| getVersion() | Ottiene la versione del formato file |

 **Result:**



---


### getExtension{#getExtension}

| Nome | Descrizione |
| --- | --- |
| getExtension() | Ottiene il nome dell'estensione di questo tipo. |

 **Result:**



---


### getExtensions{#getExtensions}

| Nome | Descrizione |
| --- | --- |
| getExtensions() | Ottiene i nomi delle estensioni di questo tipo. |

 **Result:**



---


### getContentType{#getContentType}

| Nome | Descrizione |
| --- | --- |
| getContentType() | Ottiene il tipo di contenuto del formato file. Il valore della proprietà è la costante intera FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Nome | Descrizione |
| --- | --- |
| getFileFormatType() | Ottiene il tipo di formato file |

 **Result:**



---


### getFormatByExtension{#getFormatByExtension}

| Nome | Descrizione |
| --- | --- |
| getFormatByExtension(extensionName) | Ottiene il formato file preferito dal nome dell'estensione del file. Il nome dell'estensione dovrebbe iniziare con un punto ('.'). |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| extensionNam | Stringa | null |

 **Result:**
FormatoFile


---


### detect{#detect}

| Nome | Descrizione |
| --- | --- |
| detect(fileName) | Rileva il formato del file dal nome del file; il file deve essere leggibile affinché Aspose.3D possa rilevare il formato del file tramite l'intestazione del file. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileNam | Stringa | null |

 **Result:**
FormatoFile


---


### createLoadOptions{#createLoadOptions}

| Nome | Descrizione |
| --- | --- |
| createLoadOptions() | Crea le opzioni di caricamento predefinite per questo formato file |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Nome | Descrizione |
| --- | --- |
| createSaveOptions() | Crea le opzioni di salvataggio predefinite per questo formato file |

 **Result:**
SaveOptions


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Formati in stringa |

 **Result:**
Stringa


---



