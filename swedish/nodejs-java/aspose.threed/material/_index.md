---
title: "Material"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/material/
---
## Material class

Material definierar de parametrar som behövs för geometrins visuella utseende. Aspose.3D tillhandahåller skuggningsmodeller för LambertMaterial, PhongMaterial och ShaderMaterial  @hideconstructor


## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| MAP_SPECULAR | Används i setTexture(java.lang.String, com.aspose.threed.TextureBase) för att tilldela en spekulär texturkartläggning. |
| MAP_DIFFUSE | Används i setTexture(java.lang.String, com.aspose.threed.TextureBase) för att tilldela en diffus texturkartläggning. |
| MAP_EMISSIVE | Används i setTexture(java.lang.String, com.aspose.threed.TextureBase) för att tilldela en emissiv texturkartläggning. |
| MAP_AMBIENT | Används i setTexture(java.lang.String, com.aspose.threed.TextureBase) för att tilldela en ambient texturkartläggning. |
| MAP_NORMAL | Används i setTexture(java.lang.String, com.aspose.threed.TextureBase) för att tilldela en normal texturkartläggning. |

## Metoder

### getName{#getName}

| Namn | Beskrivning |
| --- | --- |
| getName() | Hämtar eller anger namnet. Namnet. |

 **Result:**



---


### setName{#setName}

| Namn | Beskrivning |
| --- | --- |
| setName(value) | Hämtar eller anger namnet. Namnet. |

 **Result:**



---


### getProperties{#getProperties}

| Namn | Beskrivning |
| --- | --- |
| getProperties() | Hämtar samlingen av alla egenskaper. |

 **Result:**



---


### getTexture{#getTexture}

| Namn | Beskrivning |
| --- | --- |
| getTexture(slotName) | Hämtar texturen från den angivna sloten, den kan vara materialets egenskapsnamn eller shaderns parameternamn |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| slotName | Sträng | Slotnamn. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| Namn | Beskrivning |
| --- | --- |
| setTexture(slotName, texture) | Anger texturen till den angivna sloten |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| slotName | Sträng | Slotnamn. |
| texture | TextureBase | Textur. |

 **Result:**
TextureBase


---


### toString{#toString}

| Namn | Beskrivning |
| --- | --- |
| toString() | Formaterar objekt till sträng. |

 **Result:**
Sträng


---


### removeProperty{#removeProperty}

| Namn | Beskrivning |
| --- | --- |
| removeProperty(property) | Tar bort en dynamisk egenskap. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| property | Property | Vilken egenskap som ska tas bort |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Namn | Beskrivning |
| --- | --- |
| removeProperty(property) | Ta bort den angivna egenskapen som identifieras med namn |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| propert | Sträng | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Namn | Beskrivning |
| --- | --- |
| getProperty(property) | Hämta värdet för den angivna egenskapen |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| property | Sträng | Egenskapsnamn |

 **Result:**
Objekt


---


### setProperty{#setProperty}

| Namn | Beskrivning |
| --- | --- |
| setProperty(property, value) | Sätter värdet för den angivna egenskapen |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| property | Sträng | Egenskapsnamn |
| värde | Objekt | Värdet för egenskapen |

 **Result:**
Objekt


---


### findProperty{#findProperty}

| Namn | Beskrivning |
| --- | --- |
| findProperty(propertyName) | Hittar egenskapen. Det kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad av dess namn) |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| propertyName | Sträng | Egenskapsnamn. |

 **Result:**
Property


---


### iterator{#iterator}

| Namn | Beskrivning |
| --- | --- |
| iterator() | Reserverad för internt bruk. |

 **Result:**
Property


---



