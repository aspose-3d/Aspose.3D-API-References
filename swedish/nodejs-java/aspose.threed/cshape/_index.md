---
title: "CShape"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/cshape/
---
## CShape class

IFC-kompatibel C-form profil som definieras av parametrar.  Profilens mittposition är i mitten av omgivningsrutan.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Konstruktor för CShape |

 **Result:**



---


### getDepth{#getDepth}

| Namn | Beskrivning |
| --- | --- |
| getDepth() | Hämtar eller sätter djupet på profilen. |

 **Result:**



---


### setDepth{#setDepth}

| Namn | Beskrivning |
| --- | --- |
| setDepth(value) | Hämtar eller sätter djupet på profilen. |

 **Result:**



---


### getWidth{#getWidth}

| Namn | Beskrivning |
| --- | --- |
| getWidth() | Hämtar eller sätter bredden på profilen. |

 **Result:**



---


### setWidth{#setWidth}

| Namn | Beskrivning |
| --- | --- |
| setWidth(value) | Hämtar eller sätter bredden på profilen. |

 **Result:**



---


### getGirth{#getGirth}

| Namn | Beskrivning |
| --- | --- |
| getGirth() | Hämtar eller sätter längden på omkretsen. |

 **Result:**



---


### setGirth{#setGirth}

| Namn | Beskrivning |
| --- | --- |
| setGirth(value) | Hämtar eller sätter längden på omkretsen. |

 **Result:**



---


### getWallThickness{#getWallThickness}

| Namn | Beskrivning |
| --- | --- |
| getWallThickness() | Hämtar eller sätter tjockleken på väggen. |

 **Result:**



---


### setWallThickness{#setWallThickness}

| Namn | Beskrivning |
| --- | --- |
| setWallThickness(value) | Hämtar eller sätter tjockleken på väggen. |

 **Result:**



---


### getInternalFilletRadius{#getInternalFilletRadius}

| Namn | Beskrivning |
| --- | --- |
| getInternalFilletRadius() | Hämtar eller sätter den interna avrundningsradien. |

 **Result:**



---


### setInternalFilletRadius{#setInternalFilletRadius}

| Namn | Beskrivning |
| --- | --- |
| setInternalFilletRadius(value) | Hämtar eller sätter den interna avrundningsradien. |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Namn | Beskrivning |
| --- | --- |
| getParentNodes() | Hämtar alla föräldranoder, en entitet kan fästas vid flera föräldranoder för geometri‑instansering. Noderna. |

 **Result:**



---


### getExcluded{#getExcluded}

| Namn | Beskrivning |
| --- | --- |
| getExcluded() | Hämtar eller anger om denna enhet ska exkluderas vid export. |

 **Result:**



---


### setExcluded{#setExcluded}

| Namn | Beskrivning |
| --- | --- |
| setExcluded(value) | Hämtar eller anger om denna enhet ska exkluderas vid export. |

 **Result:**



---


### getParentNode{#getParentNode}

| Namn | Beskrivning |
| --- | --- |
| getParentNode() | Hämtar eller anger den första föräldranoden, om den första föräldranoden anges kommer denna enhet att frikopplas från andra föräldranoder. Föräldranoden. |

 **Result:**



---


### setParentNode{#setParentNode}

| Namn | Beskrivning |
| --- | --- |
| setParentNode(value) | Hämtar eller anger den första föräldranoden, om den första föräldranoden anges kommer denna enhet att frikopplas från andra föräldranoder. Föräldranoden. |

 **Result:**



---


### getScene{#getScene}

| Namn | Beskrivning |
| --- | --- |
| getScene() | Hämtar scenen som detta objekt tillhör |

 **Result:**



---


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


### getExtent{#getExtent}

| Namn | Beskrivning |
| --- | --- |
| getExtent() | Hämtar omfattningen i x- och y-dimension. |

 **Result:**
Vector2


---


### getEntityRendererKey{#getEntityRendererKey}

| Namn | Beskrivning |
| --- | --- |
| getEntityRendererKey() | Hämtar nyckeln för enhetens renderare som är registrerad i renderaren |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Namn | Beskrivning |
| --- | --- |
| getBoundingBox() | Hämtar den omgivande lådan för den aktuella enheten i dess objektrums koordinatsystem. |

 **Result:**
EntityRendererKey


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



