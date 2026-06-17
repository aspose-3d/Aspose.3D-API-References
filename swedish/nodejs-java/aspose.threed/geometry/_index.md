---
title: "Geometry"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/geometry/
---
## Geometry class

Bas-klassen för alla renderbara geometriska objekt (som Mesh, NurbsSurface, Patch osv.).  Geometry-bas-klassen stödjer:  Hantering av kontrollpunkter, kontrollpunkter definierar den grundläggande 3D-rymdstrukturen för geometrin, olika geometrityper har olika sätt att definiera konkreta 3D-modeller. Definition av vertex-element, vertex-element tillför extra information som normaler/uv-koordinater/vertex-färger till geometrin, se VertexElement för mer detaljer. Objektdeformation, Deformer kan bindas för att animera geometrins form.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor(name) | Initierar en ny instans av klassen Geometry. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn |

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



