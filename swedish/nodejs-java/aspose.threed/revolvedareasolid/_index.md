---
title: "RevolvedAreaSolid"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/revolvedareasolid/
---
## RevolvedAreaSolid class

Denna klass representerar en solid modell genom att rotera ett tvärsnitt som tillhandahålls av en profil kring en axel.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getAngleStart{#getAngleStart}

| Namn | Beskrivning |
| --- | --- |
| getAngleStart() | Hämtar eller anger startvinkeln för rotationsproceduren, mätt i radian, standardvärdet är 0. |

 **Result:**



---


### setAngleStart{#setAngleStart}

| Namn | Beskrivning |
| --- | --- |
| setAngleStart(value) | Hämtar eller anger startvinkeln för rotationsproceduren, mätt i radian, standardvärdet är 0. |

 **Result:**



---


### getAngleEnd{#getAngleEnd}

| Namn | Beskrivning |
| --- | --- |
| getAngleEnd() | Hämtar eller anger slutvinkeln för rotationsproceduren, mätt i radian, standardvärdet är pi. |

 **Result:**



---


### setAngleEnd{#setAngleEnd}

| Namn | Beskrivning |
| --- | --- |
| setAngleEnd(value) | Hämtar eller anger slutvinkeln för rotationsproceduren, mätt i radian, standardvärdet är pi. |

 **Result:**



---


### getAxis{#getAxis}

| Namn | Beskrivning |
| --- | --- |
| getAxis() | Hämtar eller anger axelns riktning, standardvärdet är (0, 1, 0). |

 **Result:**



---


### setAxis{#setAxis}

| Namn | Beskrivning |
| --- | --- |
| setAxis(value) | Hämtar eller anger axelns riktning, standardvärdet är (0, 1, 0). |

 **Result:**



---


### getOrigin{#getOrigin}

| Namn | Beskrivning |
| --- | --- |
| getOrigin() | Hämtar eller anger ursprungspunkten för rotationen, standardvärdet är (0, 0, 0). |

 **Result:**



---


### setOrigin{#setOrigin}

| Namn | Beskrivning |
| --- | --- |
| setOrigin(value) | Hämtar eller anger ursprungspunkten för rotationen, standardvärdet är (0, 0, 0). |

 **Result:**



---


### getShape{#getShape}

| Namn | Beskrivning |
| --- | --- |
| getShape() | Hämtar eller anger basprofilen som används för rotation. |

 **Result:**



---


### setShape{#setShape}

| Namn | Beskrivning |
| --- | --- |
| setShape(value) | Hämtar eller anger basprofilen som används för rotation. |

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
| toMesh() | Konvertera RevolvedAreaSolid till ett nät. |

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



