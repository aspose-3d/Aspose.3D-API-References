---
title: "Cylinder"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

Parametriserad cylinder.  Den kan också användas för att representera en kon när antingen radiusTop eller radiusBottom är noll.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Initierar en ny instans av klassen Cylinder. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(radius, height) | Initierar en ny instans av klassen Cylinder. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| radius | Nummer | Radie för den övre och nedre kapseln. |
| height | Nummer | Höjd. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | Initierar en ny instans av klassen Cylinder. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| radiusTop | Nummer | Övre radie. |
| radiusBottom | Nummer | Nedre radie. |
| height | Nummer | Höjd. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | Initierar en ny instans av klassen Cylinder. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| radiusTop | Nummer | Radie för cylinderns övre kapsel. |
| radiusBottom | Nummer | Radie för cylinderns nedre kapsel. |
| height | Nummer | Cylinderns höjd. |
| radialSegments | Nummer | Radiala segment av både övre och nedre cirklar.. |
| heightSegments | Nummer | Höjsegment. |
| openEnded | boolean | Om inställt på |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | Initierar en ny instans av klassen Cylinder. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namnet på detta objekt |
| radiusTop | Nummer | Radie för cylinderns övre kapsel. |
| radiusBottom | Nummer | Radie för cylinderns nedre kapsel. |
| height | Nummer | Cylinderns höjd. |
| radialSegments | Nummer | Radiala segment av både övre och nedre cirklar.. |
| heightSegments | Nummer | Höjsegment. |
| openEnded | boolean | Om inställt på |
| thetaStart | Nummer | Theta start. |
| thetaLength | Nummer | Theta längd. |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| Namn | Beskrivning |
| --- | --- |
| getOffsetBottom() | Hämtar eller anger vertexens transformationsförskjutning för den nedre sidan. |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| Namn | Beskrivning |
| --- | --- |
| setOffsetBottom(value) | Hämtar eller anger vertexens transformationsförskjutning för den nedre sidan. |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| Namn | Beskrivning |
| --- | --- |
| getOffsetTop() | Hämtar eller anger vertexens transformationsförskjutning för den övre sidan. |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| Namn | Beskrivning |
| --- | --- |
| setOffsetTop(value) | Hämtar eller anger vertexens transformationsförskjutning för den övre sidan. |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| Namn | Beskrivning |
| --- | --- |
| getGenerateFanCylinder() | Hämtar eller anger om en fläktstilad cylinder ska genereras när ThetaLength är mindre än 2π, annars kommer modellen inte att kapas. |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| Namn | Beskrivning |
| --- | --- |
| setGenerateFanCylinder(value) | Hämtar eller anger om en fläktstilad cylinder ska genereras när ThetaLength är mindre än 2π, annars kommer modellen inte att kapas. |

 **Result:**



---


### getShearBottom{#getShearBottom}

| Namn | Beskrivning |
| --- | --- |
| getShearBottom() | Hämtar eller anger skjuvtransformen för den nedre sidan, vektorn lagrar (x-axel, z-axel) skjuvvärdet som mäts i radian, standardvärdet är (0, 0). |

 **Result:**



---


### setShearBottom{#setShearBottom}

| Namn | Beskrivning |
| --- | --- |
| setShearBottom(value) | Hämtar eller anger skjuvtransformen för den nedre sidan, vektorn lagrar (x-axel, z-axel) skjuvvärdet som mäts i radian, standardvärdet är (0, 0). |

 **Result:**



---


### getShearTop{#getShearTop}

| Namn | Beskrivning |
| --- | --- |
| getShearTop() | Hämtar eller anger skjuvtransformen för den övre sidan, vektorn lagrar (x-axel, z-axel) skjuvvärdet som mäts i radian, standardvärdet är (0, 0). |

 **Result:**



---


### setShearTop{#setShearTop}

| Namn | Beskrivning |
| --- | --- |
| setShearTop(value) | Hämtar eller anger skjuvtransformen för den övre sidan, vektorn lagrar (x-axel, z-axel) skjuvvärdet som mäts i radian, standardvärdet är (0, 0). |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| Namn | Beskrivning |
| --- | --- |
| getRadiusTop() | Hämtar eller anger radien för cylinderns övre lock. Radien för det övre locket. |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| Namn | Beskrivning |
| --- | --- |
| setRadiusTop(value) | Hämtar eller anger radien för cylinderns övre lock. Radien för det övre locket. |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| Namn | Beskrivning |
| --- | --- |
| getRadiusBottom() | Hämtar eller anger radien för cylinderns nedre lock. Radien för det nedre locket. |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| Namn | Beskrivning |
| --- | --- |
| setRadiusBottom(value) | Hämtar eller anger radien för cylinderns nedre lock. Radien för det nedre locket. |

 **Result:**



---


### getHeight{#getHeight}

| Namn | Beskrivning |
| --- | --- |
| getHeight() | Hämtar eller anger höjden på cylindern. Höjden. |

 **Result:**



---


### setHeight{#setHeight}

| Namn | Beskrivning |
| --- | --- |
| setHeight(value) | Hämtar eller anger höjden på cylindern. Höjden. |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| Namn | Beskrivning |
| --- | --- |
| getRadialSegments() | Hämtar eller anger de radiella segmenten. De radiella segmenten. |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| Namn | Beskrivning |
| --- | --- |
| setRadialSegments(value) | Hämtar eller anger de radiella segmenten. De radiella segmenten. |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Namn | Beskrivning |
| --- | --- |
| getHeightSegments() | Hämtar eller anger höjsegmenten. Höjsegmenten. |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Namn | Beskrivning |
| --- | --- |
| setHeightSegments(value) | Hämtar eller anger höjsegmenten. Höjsegmenten. |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| Namn | Beskrivning |
| --- | --- |
| getOpenEnded() | Hämtar eller anger ett värde som indikerar om denna cylinder är öppen. Standardvärdet är falskt. Sant om öppen; annars finns topp-/bottenlock. |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| Namn | Beskrivning |
| --- | --- |
| setOpenEnded(value) | Hämtar eller anger ett värde som indikerar om denna cylinder är öppen. Standardvärdet är falskt. Sant om öppen; annars finns topp-/bottenlock. |

 **Result:**



---


### getThetaStart{#getThetaStart}

| Namn | Beskrivning |
| --- | --- |
| getThetaStart() | Hämtar eller anger theta-starten. Standardvärdet är 0. Theta-starten. |

 **Result:**



---


### setThetaStart{#setThetaStart}

| Namn | Beskrivning |
| --- | --- |
| setThetaStart(value) | Hämtar eller anger theta-starten. Standardvärdet är 0. Theta-starten. |

 **Result:**



---


### getThetaLength{#getThetaLength}

| Namn | Beskrivning |
| --- | --- |
| getThetaLength() | Hämtar eller anger theta-längden. Standardvärdet är 2π. Theta-längden. |

 **Result:**



---


### setThetaLength{#setThetaLength}

| Namn | Beskrivning |
| --- | --- |
| setThetaLength(value) | Hämtar eller anger theta-längden. Standardvärdet är 2π. Theta-längden. |

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



