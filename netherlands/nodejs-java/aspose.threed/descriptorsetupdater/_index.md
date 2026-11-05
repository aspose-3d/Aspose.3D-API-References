---
title: "DescriptorSetUpdater"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/descriptorsetupdater/
---
## DescriptorSetUpdater class

Deze klasse maakt het mogelijk om de com.aspose.threed.IDescriptorSet bij te werken in een ketenoperatie.  @hideconstructor


## Methoden

### bind{#bind}

| Naam | Beschrijving |
| --- | --- |
| bind(buffer, offset, size) | Koppel de buffer aan de huidige descriptor set |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| buffer | IBuffer | Welke buffer moet worden gebonden |
| offset | Nummer | Offset van de te binden buffer |
| grootte | Nummer | Grootte van de te binden buffer |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Naam | Beschrijving |
| --- | --- |
| bind(buffer) | Bind de volledige buffer aan de huidige descriptor |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| buffe | IBuffer | null |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Naam | Beschrijving |
| --- | --- |
| bind(binding, buffer) | Bind de buffer aan de huidige descriptorset op de opgegeven bindlocatie. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| binding | Nummer | Bindlocatie |
| buffer | IBuffer | De volledige buffer om te binden |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Naam | Beschrijving |
| --- | --- |
| bind(binding, buffer, offset, size) | Bind de buffer aan de huidige descriptorset op de opgegeven bindlocatie. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| binding | Nummer | Bindlocatie |
| buffer | IBuffer | De buffer om te binden |
| offset | Nummer | Offset van de te binden buffer |
| grootte | Nummer | Grootte van de te binden buffer |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Naam | Beschrijving |
| --- | --- |
| bind(texture) | Bind de texture-eenheid aan de huidige descriptorset |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| texture | ITextureUnit | De texture-eenheid om te binden |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Naam | Beschrijving |
| --- | --- |
| bind(binding, texture) | Bind de texture-eenheid aan de huidige descriptorset |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| binding | Nummer | De bindlocatie |
| texture | ITextureUnit | De texture-eenheid om te binden |

 **Result:**
DescriptorSetUpdater


---



