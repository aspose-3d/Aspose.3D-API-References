---
title: "DescriptorSetUpdater"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/descriptorsetupdater/
---
## DescriptorSetUpdater class

Diese Klasse ermöglicht das Aktualisieren von com.aspose.threed.IDescriptorSet in einer Kettenoperation.  @hideconstructor


## Methoden

### bind{#bind}

| Name | Beschreibung |
| --- | --- |
| bind(buffer, offset, size) | Binde den buffer an das aktuelle descriptor set |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| buffer | IBuffer | Welcher buffer soll gebunden werden |
| offset | Zahl | Versatz des buffer zum Binden |
| Größe | Zahl | Größe des buffer zum Binden |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Name | Beschreibung |
| --- | --- |
| bind(buffer) | Binde den gesamten buffer an das aktuelle descriptor |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| buffe | IBuffer | null |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Name | Beschreibung |
| --- | --- |
| bind(binding, buffer) | Binde den buffer an das aktuelle descriptor set an der angegebenen binding location. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| binding | Zahl | Binding location |
| buffer | IBuffer | Der gesamte Puffer zum Binden |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Name | Beschreibung |
| --- | --- |
| bind(binding, buffer, offset, size) | Binde den buffer an das aktuelle descriptor set an der angegebenen binding location. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| binding | Zahl | Binding location |
| buffer | IBuffer | Der Puffer zum Binden |
| offset | Zahl | Versatz des buffer zum Binden |
| Größe | Zahl | Größe des buffer zum Binden |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Name | Beschreibung |
| --- | --- |
| bind(texture) | Binde die Textureinheit an den aktuellen Deskriptorsatz |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Textur | ITextureUnit | Die Textureinheit zum Binden |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Name | Beschreibung |
| --- | --- |
| bind(binding, texture) | Binde die Textureinheit an den aktuellen Deskriptorsatz |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| binding | Zahl | Der Bindungsort |
| Textur | ITextureUnit | Die Textureinheit zum Binden |

 **Result:**
DescriptorSetUpdater


---



