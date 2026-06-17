---
title: "Plane"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/plane/
---
## Plane class

Parametriserat plan.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Initierar en ny instans av Plane med standardstorlek 1x1. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(length, width) | Initierar en ny instans av Plane. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| length | Nummer | Längd på planet. |
| bredd | Nummer | Bredd på planet. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload2(name, length, width, lengthSegments, widthSegments) | Initierar en ny instans av Plane. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn. |
| length | Nummer | Längd på planet. |
| bredd | Nummer | Bredd på planet. |
| lengthSegments | Nummer | Längdsegment. |
| widthSegments | Nummer | Breddsegment. |

 **Result:**



---


### getUp{#getUp}

| Namn | Beskrivning |
| --- | --- |
| getUp() | Hämtar eller anger uppvektorn för planet, standardvärdet är (0, 1, 0), detta påverkar genereringen av planet |

 **Result:**



---


### setUp{#setUp}

| Namn | Beskrivning |
| --- | --- |
| setUp(value) | Hämtar eller anger uppvektorn för planet, standardvärdet är (0, 1, 0), detta påverkar genereringen av planet |

 **Result:**



---


### getLength{#getLength}

| Namn | Beskrivning |
| --- | --- |
| getLength() | Hämtar eller anger längden på planet. Längden. |

 **Result:**



---


### setLength{#setLength}

| Namn | Beskrivning |
| --- | --- |
| setLength(value) | Hämtar eller anger längden på planet. Längden. |

 **Result:**



---


### getWidth{#getWidth}

| Namn | Beskrivning |
| --- | --- |
| getWidth() | Hämtar eller anger bredden på planet. Bredden. |

 **Result:**



---


### setWidth{#setWidth}

| Namn | Beskrivning |
| --- | --- |
| setWidth(value) | Hämtar eller anger bredden på planet. Bredden. |

 **Result:**



---


### getLengthSegments{#getLengthSegments}

| Namn | Beskrivning |
| --- | --- |
| getLengthSegments() | Hämtar eller anger längdsegmenten. Längdsegmenten. |

 **Result:**



---


### setLengthSegments{#setLengthSegments}

| Namn | Beskrivning |
| --- | --- |
| setLengthSegments(value) | Hämtar eller anger längdsegmenten. Längdsegmenten. |

 **Result:**



---


### getWidthSegments{#getWidthSegments}

| Namn | Beskrivning |
| --- | --- |
| getWidthSegments() | Hämtar eller anger breddsegmenten. Breddsegmenten. |

 **Result:**



---


### setWidthSegments{#setWidthSegments}

| Namn | Beskrivning |
| --- | --- |
| setWidthSegments(value) | Hämtar eller anger breddsegmenten. Breddsegmenten. |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Namn | Beskrivning |
| --- | --- |
| getCastShadows() | Hämtar eller anger om denna geometri kan kasta skugga |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Namn | Beskrivning |
| --- | --- |
| setCastShadows(value) | Hämtar eller anger om denna geometri kan kasta skugga |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Namn | Beskrivning |
| --- | --- |
| getReceiveShadows() | Hämtar eller anger om denna geometri kan ta emot skugga. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Namn | Beskrivning |
| --- | --- |
| setReceiveShadows(value) | Hämtar eller anger om denna geometri kan ta emot skugga. |

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


### toMesh{#toMesh}

| Namn | Beskrivning |
| --- | --- |
| toMesh() | Konvertera aktuellt objekt till mesh |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Namn | Beskrivning |
| --- | --- |
| getBoundingBox() | Hämtar den omgivande lådan för den aktuella enheten i dess objektrums koordinatsystem. |

 **Result:**
Mesh


---


### getEntityRendererKey{#getEntityRendererKey}

| Namn | Beskrivning |
| --- | --- |
| getEntityRendererKey() | Hämtar nyckeln för enhetens renderare som är registrerad i renderaren |

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



