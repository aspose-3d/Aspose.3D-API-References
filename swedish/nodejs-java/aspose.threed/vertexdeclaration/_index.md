---
title: "VertexDeclaration"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/vertexdeclaration/
---
## VertexDeclaration class

Deklarationen av en anpassad definierad vertexstruktur


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getSealed{#getSealed}

| Namn | Beskrivning |
| --- | --- |
| getSealed() | En VertexDeclaration kommer att förseglas när den har använts av com.aspose.threed.TriMesh`1 eller TriMesh, inga fler ändringar är tillåtna. |

 **Result:**



---


### getCount{#getCount}

| Namn | Beskrivning |
| --- | --- |
| getCount() | Hämtar antalet alla fält som definierats i denna VertexDeclaration |

 **Result:**



---


### getSize{#getSize}

| Namn | Beskrivning |
| --- | --- |
| getSize() | Storleken i byte för vertex-strukturen. |

 **Result:**



---


### get{#get}

| Namn | Beskrivning |
| --- | --- |
| get(index) |  |

 **Result:**



---


### clear{#clear}

| Namn | Beskrivning |
| --- | --- |
| clear() | Rensa alla fält. |

 **Result:**



---


### addField{#addField}

| Namn | Beskrivning |
| --- | --- |
| addField(dataType, semantic, index, alias) | Lägg till ett nytt vertex-fält |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| dataType | Nummer | VertexFieldDataType |
| semantic | VertexFieldSemantic | VertexFieldSemantic |
| index | Nummer | Indexet för samma fältsemantik, -1 för automatisk generering |
| alias | Sträng | Aliasnamnet för fältet |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Namn | Beskrivning |
| --- | --- |
| fromGeometry(geometry, useFloat) | Skapa en VertexDeclaration baserad på en Geometrys layout. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| geometr | Geometry | null |
| useFloat | boolean | Använd float istället för dubbeltyp |

 **Result:**
VertexDeclaration


---


### compareTo{#compareTo}

| Namn | Beskrivning |
| --- | --- |
| compareTo(other) | Jämför detta objekt med ett angivet objekt och returnerar en indikation på deras relativa värden. |

 **Result:**
VertexDeclaration


---


### toString{#toString}

| Namn | Beskrivning |
| --- | --- |
| toString() |  |

 **Result:**
Sträng


---


### hashCode{#hashCode}

| Namn | Beskrivning |
| --- | --- |
| hashCode() |  |

 **Result:**
Nummer


---


### equals{#equals}

| Namn | Beskrivning |
| --- | --- |
| equals(obj) | Bestämmer om detta objekt och ett specificerat objekt, som också måste vara ett VertexDeclaration-objekt, har samma värde. |

 **Result:**
Nummer


---


### iterator{#iterator}

| Namn | Beskrivning |
| --- | --- |
| iterator() | Reserverad för internt bruk. |

 **Result:**
Nummer


---



