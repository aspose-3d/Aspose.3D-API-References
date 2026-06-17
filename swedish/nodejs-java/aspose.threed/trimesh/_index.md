---
title: "TriMesh"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

En TriMesh innehåller rådata som kan användas direkt av GPU. Denna klass är ett verktyg för att hjälpa till att konstruera ett mesh som endast innehåller per-vertex‑data.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor(name, declaration) | Initiera en instans av TriMesh |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namnet på detta TriMesh |
| deklaration | VertexDeclaration | Vertexens deklaration |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| Namn | Beskrivning |
| --- | --- |
| getVertexDeclaration() | Vertexlayouten för TriMesh. |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| Namn | Beskrivning |
| --- | --- |
| getVerticesCount() | Antalet vertexar i detta TriMesh |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| Namn | Beskrivning |
| --- | --- |
| getIndicesCount() | Antalet index i detta TriMesh |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| Namn | Beskrivning |
| --- | --- |
| getUnmergedVerticesCount() | Antalet icke-sammanfogade vertexar som passerade in via beginVertex() och endVertex(). |

 **Result:**



---


### getCapacity{#getCapacity}

| Namn | Beskrivning |
| --- | --- |
| getCapacity() | Kapaciteten för förallokerade vertexar. |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| Namn | Beskrivning |
| --- | --- |
| getVerticesSizeInBytes() | Den totala storleken på alla vertexar i byte |

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


### fromMesh{#fromMesh}

| Namn | Beskrivning |
| --- | --- |
| fromMesh(declaration, mesh) | Skapa ett TriMesh från ett givet mesh-objekt med given vertex-layout. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |
| mes | Mesh | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| Namn | Beskrivning |
| --- | --- |
| copyFrom(input, vd) | Kopiera TriMesh från input med ny vertex-layout |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| input | TriMesh | Inmatnings-TriMesh för kopiering |
| vd | VertexDeclaration | Den nya vertex-deklarationen för utdata-TriMesh |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| Namn | Beskrivning |
| --- | --- |
| fromMesh(mesh, useFloat) | Skapa ett TriMesh från ett givet mesh-objekt, vertex-deklarationen baseras på input-meshens struktur. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| mes | Mesh | null |
| useFloat | boolean | Använd float-typ istället för double-typ för varje vertex-elementkomponent. |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| Namn | Beskrivning |
| --- | --- |
| beginVertex() | Börja lägga till vertex |

 **Result:**
Vertex


---


### endVertex{#endVertex}

| Namn | Beskrivning |
| --- | --- |
| endVertex() | Avsluta att lägga till vertex |

 **Result:**
Vertex


---


### verticesToArray{#verticesToArray}

| Namn | Beskrivning |
| --- | --- |
| verticesToArray() | Konvertera vertexdata till bytearray |

 **Result:**
byte[]


---


### toString{#toString}

| Namn | Beskrivning |
| --- | --- |
| toString() |  |

 **Result:**
Sträng


---


### fromRawData{#fromRawData}

| Namn | Beskrivning |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | Skapa TriMesh från rådata. Den returnerade TriMesh kommer inte att kopiera den inmatade bytearrayen för prestanda, externa förändringar av arrayen kommer att återspeglas i detta objekt. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| vd | VertexDeclaration | Vertexdeklaration, måste innehålla minst ett fält. |
| vertices | byte[] | Den inmatade vertexdata, den minsta längden på vertexerna måste vara större än eller lika med storleken på vertexdeklarationen. |
| indices | Number[] | Triangelindexen |
| generateVertexMapping | boolean | Generera |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| Namn | Beskrivning |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | Läs in vertexar från byte, längden på byte måste vara ett heltalsmultipel av vertexstorleken. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| Namn | Beskrivning |
| --- | --- |
| readVector4(idx, field) | Läs vector4-fältet |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| idx | Nummer | Indexet för vertex att läsa |
| field | VertexField | Fältet med datatypen Vector4/FVector4 |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| Namn | Beskrivning |
| --- | --- |
| readFVector4(idx, field) | Läs vector4-fältet |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| idx | Nummer | Indexet för vertex att läsa |
| field | VertexField | Fältet med datatypen Vector4/FVector4 |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| Namn | Beskrivning |
| --- | --- |
| readVector3(idx, field) | Läs vector3-fältet |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| idx | Nummer | Indexet för vertex att läsa |
| field | VertexField | Fältet med en Vector3/FVector3-datatyp |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| Namn | Beskrivning |
| --- | --- |
| readFVector3(idx, field) | Läs vector3-fältet |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| idx | Nummer | Indexet för vertex att läsa |
| field | VertexField | Fältet med en Vector3/FVector3-datatyp |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| Namn | Beskrivning |
| --- | --- |
| readVector2(idx, field) | Läs vector2-fältet |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| idx | Nummer | Indexet för vertex att läsa |
| field | VertexField | Fältet med en Vector2/FVector2-datatyp |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| Namn | Beskrivning |
| --- | --- |
| readFVector2(idx, field) | Läs vector2-fältet |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| idx | Nummer | Indexet för vertex att läsa |
| field | VertexField | Fältet med en Vector2/FVector2-datatyp |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| Namn | Beskrivning |
| --- | --- |
| readDouble(idx, field) | Läs double-fältet |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| idx | Nummer | Indexet för vertex att läsa |
| field | VertexField | Fältet med en float/double-kompatibel datatyp |

 **Result:**
Nummer


---


### readFloat{#readFloat}

| Namn | Beskrivning |
| --- | --- |
| readFloat(idx, field) | Läs float-fältet |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| idx | Nummer | Indexet för vertex att läsa |
| field | VertexField | Fältet med en float/double-kompatibel datatyp |

 **Result:**
Nummer


---


### getBoundingBox{#getBoundingBox}

| Namn | Beskrivning |
| --- | --- |
| getBoundingBox() | Hämtar den omgivande lådan för den aktuella enheten i dess objektrums koordinatsystem. |

 **Result:**
Nummer


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



