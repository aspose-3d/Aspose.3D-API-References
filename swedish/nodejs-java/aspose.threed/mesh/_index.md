---
title: "Mesh"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/mesh/
---
## Mesh class

Ett nätverk består av många n-sidiga polygoner.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Initierar en ny instans av Mesh-klassen. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(name) | Initierar en ny instans av Mesh-klassen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn. |

 **Result:**



---


### getEdges{#getEdges}

| Namn | Beskrivning |
| --- | --- |
| getEdges() | Hämtar kanter av Mesh. Kant är valfri i mesh, så den kan vara tom. |

 **Result:**



---


### getPolygonCount{#getPolygonCount}

| Namn | Beskrivning |
| --- | --- |
| getPolygonCount() | Hämtar antalet polygoner. Polygonantalet. |

 **Result:**



---


### getPolygons{#getPolygons}

| Namn | Beskrivning |
| --- | --- |
| getPolygons() | Hämtar polygondefinitionen för mesh |

 **Result:**



---


### getVisible{#getVisible}

| Namn | Beskrivning |
| --- | --- |
| getVisible() | Hämtar eller anger om geometrin är synlig |

 **Result:**



---


### setVisible{#setVisible}

| Namn | Beskrivning |
| --- | --- |
| setVisible(value) | Hämtar eller anger om geometrin är synlig |

 **Result:**



---


### getDeformers{#getDeformers}

| Namn | Beskrivning |
| --- | --- |
| getDeformers() | Hämtar alla deformers som är associerade med denna geometri. Deformers. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Namn | Beskrivning |
| --- | --- |
| getControlPoints() | Hämtar alla kontrollpunkter |

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


### getVertexElements{#getVertexElements}

| Namn | Beskrivning |
| --- | --- |
| getVertexElements() | Hämtar alla vertex elements |

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


### getPolygonSize{#getPolygonSize}

| Namn | Beskrivning |
| --- | --- |
| getPolygonSize(index) | Hämtar antalet hörn i den angivna polygonen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| index | Nummer | Index. |

 **Result:**
Nummer


---


### createPolygon{#createPolygon}

| Namn | Beskrivning |
| --- | --- |
| createPolygon(indices, offset, length) | Skapar en ny polygon med alla hörn definierade i index. För att skapa polygon hörn för hörn, använd PolygonBuilder. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| indices | Number[] | Array av polygonens index, där varje index pekar på en kontrollpunkt som bildar polygonen. |
| offset | Nummer | Förskjutningen för det första polygonindexet |
| length | Nummer | Längden på indexen |

 **Result:**
Nummer


---


### createPolygon{#createPolygon}

| Namn | Beskrivning |
| --- | --- |
| createPolygon(indices) | Skapar en ny polygon med alla hörn definierade i index. För att skapa polygon hörn för hörn, använd PolygonBuilder. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| indices | Number[] | Array av polygonens index, där varje index pekar på en kontrollpunkt som bildar polygonen. |

 **Result:**
Nummer


---


### createPolygon{#createPolygon}

| Namn | Beskrivning |
| --- | --- |
| createPolygon(v1, v2, v3, v4) | Skapa en polygon med 4 hörn(quad) |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| v1 | Nummer | Index för det första hörnet |
| v2 | Nummer | Index för det andra hörnet |
| v3 | Nummer | Index för det tredje hörnet |
| v4 | Nummer | Index för det fjärde hörnet |

 **Result:**
Nummer


---


### createPolygon{#createPolygon}

| Namn | Beskrivning |
| --- | --- |
| createPolygon(v1, v2, v3) | Skapa en polygon med 3 hörn(triangel) |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| v1 | Nummer | Index för det första hörnet |
| v2 | Nummer | Index för det andra hörnet |
| v3 | Nummer | Index för det tredje hörnet |

 **Result:**
Nummer


---


### toMesh{#toMesh}

| Namn | Beskrivning |
| --- | --- |
| toMesh() | Hämtar Mesh-instansen från den aktuella enheten. |

 **Result:**
Mesh


---


### getElement{#getElement}

| Namn | Beskrivning |
| --- | --- |
| getElement(type) | Hämtar ett vertex element med angiven typ |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| typ | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| Namn | Beskrivning |
| --- | --- |
| getVertexElementOfUV(textureMapping) | Hämtar en VertexElementUV-instans med given texture mapping-typ |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| textureMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| Namn | Beskrivning |
| --- | --- |
| createElement(type) | Skapar ett vertex element med angiven typ och lägger till det i geometrin. Om typen är VertexElementType.UV, skapas ett VertexElementUV med texture mapping-typ till TextureMapping.DIFFUSE. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| typ | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| Namn | Beskrivning |
| --- | --- |
| addElement(element) | Lägger till ett befintligt vertex element i den aktuella geometrin |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| element | VertexElement | Vertex elementet att lägga till |

 **Result:**
VertexElement


---


### createElement{#createElement}

| Namn | Beskrivning |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | Skapar ett vertex element med angiven typ och lägger till det i geometrin. Om typen är VertexElementType.UV, skapas ett VertexElementUV med texture mapping-typ till TextureMapping.DIFFUSE. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| typ | VertexElementType | VertexElementType |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| Namn | Beskrivning |
| --- | --- |
| createElementUV(uvMapping) | Skapar ett VertexElementUV med given texturkartläggningstyp. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| Namn | Beskrivning |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | Skapar ett VertexElementUV med given texturkartläggningstyp. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| Namn | Beskrivning |
| --- | --- |
| getBoundingBox() | Hämtar den omgivande lådan för den aktuella enheten i dess objektrums koordinatsystem. |

 **Result:**
VertexElementUV


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


### iterator{#iterator}

| Namn | Beskrivning |
| --- | --- |
| iterator() | Reserverad för internt bruk. |

 **Result:**
Property


---



