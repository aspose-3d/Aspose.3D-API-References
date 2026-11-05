---
title: "DracoFormat"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Google Draco-indeling  @hideconstructor


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


### decode{#decode}

| Naam | Beschrijving |
| --- | --- |
| decode(fileName) | Decodeer de puntwolk of mesh van de opgegeven bestandsnaam |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | De bestandsnaam bevat het drc-bestand |

 **Result:**
Geometry


---


### decode{#decode}

| Naam | Beschrijving |
| --- | --- |
| decode(data) | Decodeer de puntwolk of mesh uit geheugengegevens |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] | De ruwe drc-bytes |

 **Result:**
Geometry


---


### encode{#encode}

| Naam | Beschrijving |
| --- | --- |
| encode(entity, fileName, options) | Encodeer de entiteit naar het opgegeven bestand |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| entiteit | Entiteit | De te coderen entiteit |
| fileName | String | De te schrijven bestandsnaam |
| options | DracoSaveOptions | Extra opties voor het coderen van de puntwolk |

 **Result:**
Geometry


---


### encode{#encode}

| Naam | Beschrijving |
| --- | --- |
| encode(entity, options) | Encodeer de entiteit naar ruwe Draco-gegevens |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| entiteit | Entiteit | De te coderen entiteit |
| options | DracoSaveOptions | Extra opties voor het coderen van de puntwolk |

 **Result:**
byte[]


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



