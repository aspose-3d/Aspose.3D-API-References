---
title: "Skeleton"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/skeleton/
---
## Skeleton class

De Skeleton wordt voornamelijk gebruikt door CAD‑software om ontwerpers te helpen de transformatie van een skeletstructuur te manipuleren; hij is meestal nutteloos buiten CAD‑software. Om de skelet‑hiërarchie als één object in CAD‑software te laten functioneren, moet het bovenste Skeleton‑knooppunt als root worden gemarkeerd door Type in te stellen op SkeletonType.SKELETON, en alle kinderen op SkeletonType.BONE.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuw exemplaar van de Skeleton-klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(name) | Initialiseert een nieuw exemplaar van de Skeleton-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam. |

 **Result:**



---


### getSize{#getSize}

| Naam | Beschrijving |
| --- | --- |
| getSize() | Haalt op of stelt de grootte van de ledemaatknoop in, die wordt gebruikt in CAD-software om de grootte van het bot weer te geven. |

 **Result:**



---


### setSize{#setSize}

| Naam | Beschrijving |
| --- | --- |
| setSize(value) | Haalt op of stelt de grootte van de ledemaatknoop in, die wordt gebruikt in CAD-software om de grootte van het bot weer te geven. |

 **Result:**



---


### getType{#getType}

| Naam | Beschrijving |
| --- | --- |
| getType() | Haalt op of stelt het type van het skelet in. De waarde van de eigenschap is de gehele constante SkeletonType. Het type van het skelet. |

 **Result:**



---


### setType{#setType}

| Naam | Beschrijving |
| --- | --- |
| setType(value) | Haalt op of stelt het type van het skelet in. De waarde van de eigenschap is de gehele constante SkeletonType. Het type van het skelet. |

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


### getBoundingBox{#getBoundingBox}

| Naam | Beschrijving |
| --- | --- |
| getBoundingBox() | Haalt het begrenzingsvak op van de huidige entiteit in zijn objectruimte-coördinatensysteem. |

 **Result:**



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



