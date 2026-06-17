---
title: "DescriptorSetUpdater"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/descriptorsetupdater/
---
## DescriptorSetUpdater class

Deze klasse maakt het mogelijk om de com.aspose.threed.IDescriptorSet bij te werken in een ketenbewerking.  @hideconstructor


## Methoden

### bind{#bind}

| Naam | Beschrijving |
| --- | --- |
| bind(buffer, offset, size) | Koppel de buffer aan de huidige descriptorset |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| buffer | IBuffer | Welke buffer te koppelen |
| offset | Number | Offset van de te koppelen buffer |
| grootte | Number | Grootte van de te koppelen buffer |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Naam | Beschrijving |
| --- | --- |
| bind(buffer) | Koppel de volledige buffer aan de huidige descriptor |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| buffer | IBuffer | null |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Naam | Beschrijving |
| --- | --- |
| bind(binding, buffer) | Koppel de buffer aan de huidige descriptorset op de opgegeven bindlocatie. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| binding | Number | Bindlocatie |
| buffer | IBuffer | De volledige buffer om te koppelen. |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Naam | Beschrijving |
| --- | --- |
| bind(binding, buffer, offset, size) | Koppel de buffer aan de huidige descriptorset op de opgegeven bindlocatie. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| binding | Number | Bindlocatie |
| buffer | IBuffer | De buffer om te koppelen. |
| offset | Number | Offset van de te koppelen buffer |
| grootte | Number | Grootte van de te koppelen buffer |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Naam | Beschrijving |
| --- | --- |
| bind(texture) | Koppel de texture-eenheid aan de huidige descriptorset. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| texture | ITextureUnit | De texture-eenheid om te koppelen. |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Naam | Beschrijving |
| --- | --- |
| bind(binding, texture) | Koppel de texture-eenheid aan de huidige descriptorset. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| binding | Number | De bindlocatie. |
| texture | ITextureUnit | De texture-eenheid om te koppelen. |

 **Result:**
DescriptorSetUpdater


---



