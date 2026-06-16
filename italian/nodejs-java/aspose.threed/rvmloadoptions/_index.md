---
title: "RvmLoadOptions"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/rvmloadoptions/
---
## RvmLoadOptions class

Opzioni di caricamento per il file RVM di AVEVA Plant Design Management System.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(contentType) | Crea un'istanza di RvmLoadOptions |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload() | Crea un'istanza di RvmLoadOptions |

 **Result:**



---


### getGenerateMaterials{#getGenerateMaterials}

| Nome | Descrizione |
| --- | --- |
| getGenerateMaterials() | Genera materiali con colori casuali per ogni oggetto nella scena se la tavola dei colori non è esportata nel file RVM. Il valore predefinito è true. |

 **Result:**



---


### setGenerateMaterials{#setGenerateMaterials}

| Nome | Descrizione |
| --- | --- |
| setGenerateMaterials(value) | Genera materiali con colori casuali per ogni oggetto nella scena se la tavola dei colori non è esportata nel file RVM. Il valore predefinito è true. |

 **Result:**



---


### getCylinderRadialSegments{#getCylinderRadialSegments}

| Nome | Descrizione |
| --- | --- |
| getCylinderRadialSegments() | Ottiene o imposta il numero di segmenti radiali del cilindro, valore predefinito è 16. |

 **Result:**



---


### setCylinderRadialSegments{#setCylinderRadialSegments}

| Nome | Descrizione |
| --- | --- |
| setCylinderRadialSegments(value) | Ottiene o imposta il numero di segmenti radiali del cilindro, valore predefinito è 16. |

 **Result:**



---


### getDishLongitudeSegments{#getDishLongitudeSegments}

| Nome | Descrizione |
| --- | --- |
| getDishLongitudeSegments() | Ottiene o imposta il numero di segmenti di longitudine del piatto, valore predefinito è 12. |

 **Result:**



---


### setDishLongitudeSegments{#setDishLongitudeSegments}

| Nome | Descrizione |
| --- | --- |
| setDishLongitudeSegments(value) | Ottiene o imposta il numero di segmenti di longitudine del piatto, valore predefinito è 12. |

 **Result:**



---


### getDishLatitudeSegments{#getDishLatitudeSegments}

| Nome | Descrizione |
| --- | --- |
| getDishLatitudeSegments() | Ottiene o imposta il numero di segmenti di latitudine del piatto, valore predefinito è 8. |

 **Result:**



---


### setDishLatitudeSegments{#setDishLatitudeSegments}

| Nome | Descrizione |
| --- | --- |
| setDishLatitudeSegments(value) | Ottiene o imposta il numero di segmenti di latitudine del piatto, valore predefinito è 8. |

 **Result:**



---


### getTorusTubularSegments{#getTorusTubularSegments}

| Nome | Descrizione |
| --- | --- |
| getTorusTubularSegments() | Ottiene o imposta il numero di segmenti tubolari del toro, valore predefinito è 20. |

 **Result:**



---


### setTorusTubularSegments{#setTorusTubularSegments}

| Nome | Descrizione |
| --- | --- |
| setTorusTubularSegments(value) | Ottiene o imposta il numero di segmenti tubolari del toro, valore predefinito è 20. |

 **Result:**



---


### getRectangularTorusSegments{#getRectangularTorusSegments}

| Nome | Descrizione |
| --- | --- |
| getRectangularTorusSegments() | Ottiene o imposta il numero di segmenti radiali del toro rettangolare, valore predefinito è 20. |

 **Result:**



---


### setRectangularTorusSegments{#setRectangularTorusSegments}

| Nome | Descrizione |
| --- | --- |
| setRectangularTorusSegments(value) | Ottiene o imposta il numero di segmenti radiali del toro rettangolare, valore predefinito è 20. |

 **Result:**



---


### getCenterScene{#getCenterScene}

| Nome | Descrizione |
| --- | --- |
| getCenterScene() | Centra la scena dopo che è stata caricata. |

 **Result:**



---


### setCenterScene{#setCenterScene}

| Nome | Descrizione |
| --- | --- |
| setCenterScene(value) | Centra la scena dopo che è stata caricata. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Nome | Descrizione |
| --- | --- |
| getAttributePrefix() | Ottiene o imposta il prefisso degli attributi che sono stati definiti nei file di attributi esterni, Il prefisso è usato per evitare conflitti di nome, il valore predefinito è "rvm:" |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Nome | Descrizione |
| --- | --- |
| setAttributePrefix(value) | Ottiene o imposta il prefisso degli attributi che sono stati definiti nei file di attributi esterni, Il prefisso è usato per evitare conflitti di nome, il valore predefinito è "rvm:" |

 **Result:**



---


### getLookupAttributes{#getLookupAttributes}

| Nome | Descrizione |
| --- | --- |
| getLookupAttributes() | Ottiene o imposta se caricare gli attributi da file di elenco attributi esterni (.att/.attrib/.txt), il valore predefinito è true. |

 **Result:**



---


### setLookupAttributes{#setLookupAttributes}

| Nome | Descrizione |
| --- | --- |
| setLookupAttributes(value) | Ottiene o imposta se caricare gli attributi da file di elenco attributi esterni (.att/.attrib/.txt), il valore predefinito è true. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Nome | Descrizione |
| --- | --- |
| getFileFormat() | Ottiene il formato file specificato nell'opzione Salva/Carica corrente. |

 **Result:**



---


### getEncoding{#getEncoding}

| Nome | Descrizione |
| --- | --- |
| getEncoding() | Ottiene o imposta la codifica predefinita per i file di testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Nome | Descrizione |
| --- | --- |
| getFileSystem() | Consente all'utente di gestire come amministrare le dipendenze esterne durante il caricamento/salvataggio. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Nome | Descrizione |
| --- | --- |
| setFileSystem(value) | Consente all'utente di gestire come amministrare le dipendenze esterne durante il caricamento/salvataggio. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Nome | Descrizione |
| --- | --- |
| getLookupPaths() | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare i file esterni da caricare. |

 **Result:**



---


### getFileName{#getFileName}

| Nome | Descrizione |
| --- | --- |
| getFileName() | Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Nome | Descrizione |
| --- | --- |
| setFileName(value) | Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ. |

 **Result:**



---



