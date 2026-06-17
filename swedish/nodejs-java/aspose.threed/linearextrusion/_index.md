---
title: "LinearExtrusion"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/linearextrusion/
---
## LinearExtrusion class

Linjär extrusion tar en 2D-form som indata och förlänger formen i den tredje dimensionen.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Konstruktor för instansen LinearExtrusion. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(shape, height) | Konstruktor för instansen LinearExtrusion. |

 **Result:**



---


### getShape{#getShape}

| Namn | Beskrivning |
| --- | --- |
| getShape() | Den grundläggande formen som ska extruderas. |

 **Result:**



---


### setShape{#setShape}

| Namn | Beskrivning |
| --- | --- |
| setShape(value) | Den grundläggande formen som ska extruderas. |

 **Result:**



---


### getDirection{#getDirection}

| Namn | Beskrivning |
| --- | --- |
| getDirection() | Extruderingsriktningen, standardvärdet är (0, 0, 1) |

 **Result:**



---


### setDirection{#setDirection}

| Namn | Beskrivning |
| --- | --- |
| setDirection(value) | Extruderingsriktningen, standardvärdet är (0, 0, 1) |

 **Result:**



---


### getHeight{#getHeight}

| Namn | Beskrivning |
| --- | --- |
| getHeight() | Höjden på den extruderade geometrin, standardvärdet är 1.0 |

 **Result:**



---


### setHeight{#setHeight}

| Namn | Beskrivning |
| --- | --- |
| setHeight(value) | Höjden på den extruderade geometrin, standardvärdet är 1.0 |

 **Result:**



---


### getSlices{#getSlices}

| Namn | Beskrivning |
| --- | --- |
| getSlices() | Skivorna av den vridna extruderade geometrin, standardvärdet är 1. |

 **Result:**



---


### setSlices{#setSlices}

| Namn | Beskrivning |
| --- | --- |
| setSlices(value) | Skivorna av den vridna extruderade geometrin, standardvärdet är 1. |

 **Result:**



---


### getCenter{#getCenter}

| Namn | Beskrivning |
| --- | --- |
| getCenter() | Om detta värde är falskt är Z-intervallet för den linjära extrusionen från 0 till höjden, annars är intervallet från -höjd/2 till höjd/2. |

 **Result:**



---


### setCenter{#setCenter}

| Namn | Beskrivning |
| --- | --- |
| setCenter(value) | Om detta värde är falskt är Z-intervallet för den linjära extrusionen från 0 till höjden, annars är intervallet från -höjd/2 till höjd/2. |

 **Result:**



---


### getTwistOffset{#getTwistOffset}

| Namn | Beskrivning |
| --- | --- |
| getTwistOffset() | Offseten som används vid vridning, standardvärdet är (0, 0, 0). |

 **Result:**



---


### setTwistOffset{#setTwistOffset}

| Namn | Beskrivning |
| --- | --- |
| setTwistOffset(value) | Offseten som används vid vridning, standardvärdet är (0, 0, 0). |

 **Result:**



---


### getTwist{#getTwist}

| Namn | Beskrivning |
| --- | --- |
| getTwist() | Antalet grader som formen extruderas genom. |

 **Result:**



---


### setTwist{#setTwist}

| Namn | Beskrivning |
| --- | --- |
| setTwist(value) | Antalet grader som formen extruderas genom. |

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
| toMesh() | Konvertera extrusionen till mesh. |

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



