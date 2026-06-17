---
title: "Pose"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/pose/
---
## Pose class

De pose wordt gebruikt om de transformatie-matrix op te slaan wanneer de geometrie geskinnd is. De pose is een verzameling van BonePose; elke BonePose slaat de concrete transformatie-informatie van de botknoop op.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor(name) | Initialiseert een nieuw exemplaar van de Pose-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload() | Initialiseert een nieuw exemplaar van de Pose-klasse. |

 **Result:**



---


### getPoseType{#getPoseType}

| Naam | Beschrijving |
| --- | --- |
| getPoseType() | Haalt het type van de pose op of stelt dit in. De waarde van de eigenschap is de PoseType-integerconstante. Het type van de pose. |

 **Result:**



---


### setPoseType{#setPoseType}

| Naam | Beschrijving |
| --- | --- |
| setPoseType(value) | Haalt het type van de pose op of stelt dit in. De waarde van de eigenschap is de PoseType-integerconstante. Het type van de pose. |

 **Result:**



---


### getBonePoses{#getBonePoses}

| Naam | Beschrijving |
| --- | --- |
| getBonePoses() | Haalt alle BonePose op. De knooppunten. |

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


### addBonePose{#addBonePose}

| Naam | Beschrijving |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | Slaat de pose-transformatie-matrix op voor de opgegeven botknooppunt. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| node | Node | Botknooppunt. |
| matrix | Matrix4 | Transformatie-matrix. |
| localMatrix | boolean | Indien ingesteld op |

 **Result:**



---


### addBonePose{#addBonePose}

| Naam | Beschrijving |
| --- | --- |
| addBonePose(node, matrix) | Slaat de pose-transformatiematrix op voor de opgegeven botknoop. De globale transformatiematrix wordt geïmpliceerd. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| node | Node | Botknooppunt. |
| matrix | Matrix4 | Transformatie-matrix. |

 **Result:**



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



