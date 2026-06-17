---
title: "DescriptorSetUpdater"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/descriptorsetupdater/
---
## DescriptorSetUpdater class

Denna klass möjliggör att uppdatera com.aspose.threed.IDescriptorSet i en kedjeoperation.  @hideconstructor


## Metoder

### bind{#bind}

| Namn | Beskrivning |
| --- | --- |
| bind(buffer, offset, size) | Bind bufferten till aktuellt descriptor set |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| buffer | IBuffer | Vilken buffer som ska bindas |
| offset | Nummer | Offset för bufferten som ska bindas |
| storlek | Nummer | Storlek för bufferten som ska bindas |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Namn | Beskrivning |
| --- | --- |
| bind(buffer) | Bind hela bufferten till aktuellt descriptor |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| buffert | IBuffer | null |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Namn | Beskrivning |
| --- | --- |
| bind(binding, buffer) | Koppla bufferten till aktuella descriptor set på angiven bindningsplats. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| bindning | Nummer | Bindningsplats |
| buffer | IBuffer | Hela bufferten som ska bindas |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Namn | Beskrivning |
| --- | --- |
| bind(binding, buffer, offset, size) | Koppla bufferten till aktuella descriptor set på angiven bindningsplats. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| bindning | Nummer | Bindningsplats |
| buffer | IBuffer | Bufferten som ska bindas |
| offset | Nummer | Offset för bufferten som ska bindas |
| storlek | Nummer | Storlek för bufferten som ska bindas |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Namn | Beskrivning |
| --- | --- |
| bind(texture) | Koppla texturenheten till aktuella descriptor set |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| texture | ITextureUnit | Texturenheten som ska bindas |

 **Result:**
DescriptorSetUpdater


---


### bind{#bind}

| Namn | Beskrivning |
| --- | --- |
| bind(binding, texture) | Koppla texturenheten till aktuella descriptor set |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| bindning | Nummer | Bindningsplatsen |
| texture | ITextureUnit | Texturenheten som ska bindas |

 **Result:**
DescriptorSetUpdater


---



