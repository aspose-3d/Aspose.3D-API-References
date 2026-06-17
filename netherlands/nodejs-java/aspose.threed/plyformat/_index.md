---
title: "PlyFormat"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

Het PLY-formaat.  @hideconstructor


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


### encode{#encode}

| Naam | Beschrijving |
| --- | --- |
| encode(entity, fileName) | Encodeer de entiteit en sla het resultaat op in een extern bestand. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| entity | Entity | De te coderen entiteit |
| fileName | String | Het bestand om naar te schrijven |

 **Result:**



---


### encode{#encode}

| Naam | Beschrijving |
| --- | --- |
| encode(entity, fileName, opt) | Encodeer de entiteit en sla het resultaat op in een extern bestand. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| entity | Entity | De te coderen entiteit |
| fileName | String | Het bestand om naar te schrijven |
| opt | PlySaveOptions | Opslagopties |

 **Result:**



---


### decode{#decode}

| Naam | Beschrijving |
| --- | --- |
| decode(fileName) | Decodeer een puntenwolk of mesh van de opgegeven stream. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | De invoerstream |

 **Result:**
Geometrie


---


### decode{#decode}

| Naam | Beschrijving |
| --- | --- |
| decode(fileName, opt) | Decodeer een puntenwolk of mesh van de opgegeven stream. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | De invoerstream |
| opt | PlyLoadOptions | De laadoptie van het PLY-formaat |

 **Result:**
Geometrie


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



