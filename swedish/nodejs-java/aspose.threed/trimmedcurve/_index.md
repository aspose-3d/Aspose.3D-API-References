---
title: "TrimmedCurve"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/trimmedcurve/
---
## TrimmedCurve class

En begränsad kurva som beskär den grundläggande kurvan i båda ändar.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Konstruktor för TrimmedCurve |

 **Result:**



---


### getBasisCurve{#getBasisCurve}

| Namn | Beskrivning |
| --- | --- |
| getBasisCurve() | Basiskurvan som ska trimmas. |

 **Result:**



---


### setBasisCurve{#setBasisCurve}

| Namn | Beskrivning |
| --- | --- |
| setBasisCurve(value) | Basiskurvan som ska trimmas. |

 **Result:**



---


### getFirst{#getFirst}

| Namn | Beskrivning |
| --- | --- |
| getFirst() | Den första ändpunkten att trimma, kan vara en kartesisk punkt eller en reell parameter. |

 **Result:**



---


### setFirst{#setFirst}

| Namn | Beskrivning |
| --- | --- |
| setFirst(value) | Den första ändpunkten att trimma, kan vara en kartesisk punkt eller en reell parameter. |

 **Result:**



---


### getSecond{#getSecond}

| Namn | Beskrivning |
| --- | --- |
| getSecond() | Den andra ändpunkten att trimma, kan vara en kartesisk punkt eller en reell parameter. |

 **Result:**



---


### setSecond{#setSecond}

| Namn | Beskrivning |
| --- | --- |
| setSecond(value) | Den andra ändpunkten att trimma, kan vara en kartesisk punkt eller en reell parameter. |

 **Result:**



---


### getSameDirection{#getSameDirection}

| Namn | Beskrivning |
| --- | --- |
| getSameDirection() | Hämtar eller anger om det trimmade resultatet använder samma riktning som baskurvan. |

 **Result:**



---


### setSameDirection{#setSameDirection}

| Namn | Beskrivning |
| --- | --- |
| setSameDirection(value) | Hämtar eller anger om det trimmade resultatet använder samma riktning som baskurvan. |

 **Result:**



---


### getColor{#getColor}

| Namn | Beskrivning |
| --- | --- |
| getColor() | Hämtar eller anger färgen på linjen, standardvärdet är vit(1, 1, 1) |

 **Result:**



---


### setColor{#setColor}

| Namn | Beskrivning |
| --- | --- |
| setColor(value) | Hämtar eller anger färgen på linjen, standardvärdet är vit(1, 1, 1) |

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



