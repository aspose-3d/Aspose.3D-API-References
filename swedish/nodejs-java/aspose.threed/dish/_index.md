---
title: "Dish"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/dish/
---
## Dish class

Parametriserad skål.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Skapa en ny dish-instans med standardradie(10) och standardhöjd(5) |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(radius, height) | Skapa en ny dish-instans med angiven radie och höjd |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| radius | Nummer | Radien på dish |
| height | Nummer | Höjden på dish |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload2(name, radius, height, widthSegments, heightSegments) | Skapa en ny dish-instans med angiven radie och höjd |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namnet på dish |
| radius | Nummer | Radien på dish |
| height | Nummer | Höjden på dish |
| widthSegments | Nummer | Breddsegmentet för dish |
| heightSegments | Nummer | Höjdsegmentet för skålen |

 **Result:**



---


### getHeight{#getHeight}

| Namn | Beskrivning |
| --- | --- |
| getHeight() | Höjd på skålen |

 **Result:**



---


### setHeight{#setHeight}

| Namn | Beskrivning |
| --- | --- |
| setHeight(value) | Höjd på skålen |

 **Result:**



---


### getRadius{#getRadius}

| Namn | Beskrivning |
| --- | --- |
| getRadius() | Radie på skålen |

 **Result:**



---


### setRadius{#setRadius}

| Namn | Beskrivning |
| --- | --- |
| setRadius(value) | Radie på skålen |

 **Result:**



---


### getWidthSegments{#getWidthSegments}

| Namn | Beskrivning |
| --- | --- |
| getWidthSegments() | Hämtar eller anger breddsegmenten |

 **Result:**



---


### setWidthSegments{#setWidthSegments}

| Namn | Beskrivning |
| --- | --- |
| setWidthSegments(value) | Hämtar eller anger breddsegmenten |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Namn | Beskrivning |
| --- | --- |
| getHeightSegments() | Hämtar eller anger höjdsegmenten |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Namn | Beskrivning |
| --- | --- |
| setHeightSegments(value) | Hämtar eller anger höjdsegmenten |

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



