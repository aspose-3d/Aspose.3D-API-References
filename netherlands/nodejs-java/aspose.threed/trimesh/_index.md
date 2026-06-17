---
title: "TriMesh"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

Een TriMesh bevat ruwe data die direct door de GPU kan worden gebruikt.  Deze klasse is een hulpprogramma om een mesh te construeren die alleen per‑vertex data bevat.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor(name, declaration) | Initialiseer een instantie van TriMesh |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | De naam van deze TriMesh |
| declaratie | VertexDeclaration | De declaratie van de vertex |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| Naam | Beschrijving |
| --- | --- |
| getVertexDeclaration() | De vertexlay-out van de TriMesh. |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| Naam | Beschrijving |
| --- | --- |
| getVerticesCount() | Het aantal vertices in deze TriMesh |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| Naam | Beschrijving |
| --- | --- |
| getIndicesCount() | Het aantal indexen in deze TriMesh |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| Naam | Beschrijving |
| --- | --- |
| getUnmergedVerticesCount() | Het aantal niet- samengevoegde vertices dat is doorgegeven door beginVertex() en endVertex(). |

 **Result:**



---


### getCapacity{#getCapacity}

| Naam | Beschrijving |
| --- | --- |
| getCapacity() | De capaciteit van vooraf toegewezen vertices. |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| Naam | Beschrijving |
| --- | --- |
| getVerticesSizeInBytes() | De totale grootte van alle vertices in bytes |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Naam | Beschrijving |
| --- | --- |
| getParentNodes() | Haalt alle bovenliggende knooppunten op, een entiteit kan aan meerdere bovenliggende knooppunten worden gekoppeld voor geometrie‑instantiatie. De knooppunten. |

 **Result:**



---


### getExcluded{#getExcluded}

| Naam | Beschrijving |
| --- | --- |
| getExcluded() | Haalt op of stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |

 **Result:**



---


### setExcluded{#setExcluded}

| Naam | Beschrijving |
| --- | --- |
| setExcluded(value) | Haalt op of stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |

 **Result:**



---


### getParentNode{#getParentNode}

| Naam | Beschrijving |
| --- | --- |
| getParentNode() | Haalt op of stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. De bovenliggende knoop. |

 **Result:**



---


### setParentNode{#setParentNode}

| Naam | Beschrijving |
| --- | --- |
| setParentNode(value) | Haalt op of stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. De bovenliggende knoop. |

 **Result:**



---


### getScene{#getScene}

| Naam | Beschrijving |
| --- | --- |
| getScene() | Haalt de scène op waartoe dit object behoort. |

 **Result:**



---


### getName{#getName}

| Naam | Beschrijving |
| --- | --- |
| getName() | Haalt de naam op of stelt deze in. De naam. |

 **Result:**



---


### setName{#setName}

| Naam | Beschrijving |
| --- | --- |
| setName(value) | Haalt de naam op of stelt deze in. De naam. |

 **Result:**



---


### getProperties{#getProperties}

| Naam | Beschrijving |
| --- | --- |
| getProperties() | Haalt de collectie van alle eigenschappen op. |

 **Result:**



---


### fromMesh{#fromMesh}

| Naam | Beschrijving |
| --- | --- |
| fromMesh(declaration, mesh) | Maak een TriMesh van het opgegeven mesh-object met de opgegeven vertex-indeling. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |
| mes | Mesh | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| Naam | Beschrijving |
| --- | --- |
| copyFrom(input, vd) | Kopieer de TriMesh van de invoer met een nieuwe vertex-indeling |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| input | TriMesh | De invoer TriMesh voor kopiëren |
| vd | VertexDeclaration | De nieuwe vertex-declaratie van de uitvoer TriMesh |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| Naam | Beschrijving |
| --- | --- |
| fromMesh(mesh, useFloat) | Maak een TriMesh van het opgegeven mesh-object, de vertex-declaratie is gebaseerd op de structuur van de invoer mesh. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| mes | Mesh | null |
| useFloat | boolean | Gebruik het float-type in plaats van het double-type voor elk vertex-elementcomponent. |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| Naam | Beschrijving |
| --- | --- |
| beginVertex() | Begin met het toevoegen van een vertex |

 **Result:**
Vertex


---


### endVertex{#endVertex}

| Naam | Beschrijving |
| --- | --- |
| endVertex() | End van het toevoegen van vertex |

 **Result:**
Vertex


---


### verticesToArray{#verticesToArray}

| Naam | Beschrijving |
| --- | --- |
| verticesToArray() | Converteer de vertexgegevens naar een byte-array |

 **Result:**
byte[]


---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### fromRawData{#fromRawData}

| Naam | Beschrijving |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | Maak een TriMesh aan vanuit ruwe gegevens. De geretourneerde TriMesh zal de invoer-byte-array niet kopiëren voor prestaties; externe wijzigingen in de array worden weerspiegeld in deze instantie. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| vd | VertexDeclaration | Vertex-declaratie moet minstens één veld bevatten. |
| vertices | byte[] | De invoer-vertex-gegevens, de minimale lengte van de vertices moet groter of gelijk zijn aan de grootte van de vertex-declaratie. |
| indices | Number[] | De driehoekindices |
| generateVertexMapping | boolean | Genereren |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| Naam | Beschrijving |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | Laad vertices vanuit bytes, de lengte van de bytes moet een geheel veelvoud zijn van de vertex-grootte. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| Naam | Beschrijving |
| --- | --- |
| readVector4(idx, field) | Lees het vector4-veld |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| idx | Number | De index van de te lezen vertex |
| field | VertexField | Het veld met een Vector4/FVector4-datatype |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| Naam | Beschrijving |
| --- | --- |
| readFVector4(idx, field) | Lees het vector4-veld |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| idx | Number | De index van de te lezen vertex |
| field | VertexField | Het veld met een Vector4/FVector4-datatype |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| Naam | Beschrijving |
| --- | --- |
| readVector3(idx, field) | Lees het vector3-veld |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| idx | Number | De index van de te lezen vertex |
| field | VertexField | Het veld met een Vector3/FVector3 datatype |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| Naam | Beschrijving |
| --- | --- |
| readFVector3(idx, field) | Lees het vector3-veld |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| idx | Number | De index van de te lezen vertex |
| field | VertexField | Het veld met een Vector3/FVector3 datatype |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| Naam | Beschrijving |
| --- | --- |
| readVector2(idx, field) | Lees het vector2-veld |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| idx | Number | De index van de te lezen vertex |
| field | VertexField | Het veld met een Vector2/FVector2 datatype |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| Naam | Beschrijving |
| --- | --- |
| readFVector2(idx, field) | Lees het vector2-veld |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| idx | Number | De index van de te lezen vertex |
| field | VertexField | Het veld met een Vector2/FVector2 datatype |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| Naam | Beschrijving |
| --- | --- |
| readDouble(idx, field) | Lees het double-veld |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| idx | Number | De index van de te lezen vertex |
| field | VertexField | Het veld met een float/double-compatibel datatype |

 **Result:**
Number


---


### readFloat{#readFloat}

| Naam | Beschrijving |
| --- | --- |
| readFloat(idx, field) | Lees het float-veld |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| idx | Number | De index van de te lezen vertex |
| field | VertexField | Het veld met een float/double-compatibel datatype |

 **Result:**
Number


---


### getBoundingBox{#getBoundingBox}

| Naam | Beschrijving |
| --- | --- |
| getBoundingBox() | Haalt het begrenzingsvak op van de huidige entiteit in zijn objectruimte-coördinatensysteem. |

 **Result:**
Number


---


### getEntityRendererKey{#getEntityRendererKey}

| Naam | Beschrijving |
| --- | --- |
| getEntityRendererKey() | Haalt de sleutel op van de entiteit-renderer die is geregistreerd in de renderer. |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| Naam | Beschrijving |
| --- | --- |
| removeProperty(property) | Verwijdert een dynamische eigenschap. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | Eigenschap | Welke eigenschap moet worden verwijderd |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Naam | Beschrijving |
| --- | --- |
| removeProperty(property) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Naam | Beschrijving |
| --- | --- |
| getProperty(property) | Haal de waarde van de opgegeven eigenschap op |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | String | Naam van eigenschap |

 **Result:**
Object


---


### setProperty{#setProperty}

| Naam | Beschrijving |
| --- | --- |
| setProperty(property, value) | Stelt de waarde van de opgegeven eigenschap in |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | String | Naam van eigenschap |
| value | Object | De waarde van de eigenschap |

 **Result:**
Object


---


### findProperty{#findProperty}

| Naam | Beschrijving |
| --- | --- |
| findProperty(propertyName) | Zoekt de eigenschap. Het kan een dynamische eigenschap (Gemaakt door CreateDynamicProperty/SetProperty) of een native eigenschap(Geadresseerd aan de hand van zijn naam) |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| propertyName | String | Naam van eigenschap. |

 **Result:**
Eigenschap


---


### iterator{#iterator}

| Naam | Beschrijving |
| --- | --- |
| iterator() | Gereserveerd voor intern gebruik. |

 **Result:**
Eigenschap


---



