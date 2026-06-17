---
title: "VertexDeclaration"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/vertexdeclaration/
---
## VertexDeclaration class

De declaratie van een aangepast gedefinieerde vertex-structuur


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getSealed{#getSealed}

| Naam | Beschrijving |
| --- | --- |
| getSealed() | Een VertexDeclaration wordt verzegeld wanneer deze is gebruikt door com.aspose.threed.TriMesh`1 of TriMesh; verdere wijzigingen zijn niet toegestaan. |

 **Result:**



---


### getCount{#getCount}

| Naam | Beschrijving |
| --- | --- |
| getCount() | Haalt het aantal van alle velden op die zijn gedefinieerd in deze VertexDeclaration. |

 **Result:**



---


### getSize{#getSize}

| Naam | Beschrijving |
| --- | --- |
| getSize() | De grootte in bytes van de vertexstructuur. |

 **Result:**



---


### get{#get}

| Naam | Beschrijving |
| --- | --- |
| get(index) |  |

 **Result:**



---


### clear{#clear}

| Naam | Beschrijving |
| --- | --- |
| clear() | Wis alle velden. |

 **Result:**



---


### addField{#addField}

| Naam | Beschrijving |
| --- | --- |
| addField(dataType, semantic, index, alias) | Voeg een nieuw vertexveld toe |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| dataType | Number | VertexFieldDataType |
| semantic | VertexFieldSemantic | VertexFieldSemantic |
| index | Number | De index voor dezelfde veldsemantic, -1 voor automatische generatie. |
| alias | String | De aliasnaam van het veld. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Naam | Beschrijving |
| --- | --- |
| fromGeometry(geometry, useFloat) | Maak een VertexDeclaration op basis van de lay-out van een Geometry. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| geometr | Geometrie | null |
| useFloat | boolean | Gebruik float in plaats van het type double. |

 **Result:**
VertexDeclaration


---


### compareTo{#compareTo}

| Naam | Beschrijving |
| --- | --- |
| compareTo(other) | Vergelijkt deze instantie met een opgegeven object en geeft een indicatie van hun relatieve waarden terug. |

 **Result:**
VertexDeclaration


---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### hashCode{#hashCode}

| Naam | Beschrijving |
| --- | --- |
| hashCode() |  |

 **Result:**
Number


---


### equals{#equals}

| Naam | Beschrijving |
| --- | --- |
| equals(obj) | Bepaalt of deze instantie en een opgegeven object, dat ook een VertexDeclaration-object moet zijn, dezelfde waarde hebben. |

 **Result:**
Number


---


### iterator{#iterator}

| Naam | Beschrijving |
| --- | --- |
| iterator() | Gereserveerd voor intern gebruik. |

 **Result:**
Number


---



