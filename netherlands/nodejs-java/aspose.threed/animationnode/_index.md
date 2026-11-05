---
title: "AnimationNode"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Aspose.3D ondersteunt animatie‑hiërarchie; elke animatie kan worden samengesteld uit meerdere animaties en de key‑frame‑definitie van een animatie.  AnimationNode definieert de transformatie van een eigenschapswaarde in de tijd; bijvoorbeeld, een animatie‑node kan worden gebruikt om de transformatie van een node of andere numerieke eigenschappen van een A3DObject‑object te regelen.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor(name) | Initialiseert een nieuw exemplaar van de AnimationNode-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload() | Initialiseert een nieuw exemplaar van de AnimationNode-klasse. |

 **Result:**



---


### getBindPoints{#getBindPoints}

| Naam | Beschrijving |
| --- | --- |
| getBindPoints() | Haalt de huidige bindpunten van de eigenschap op |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| Naam | Beschrijving |
| --- | --- |
| getSubAnimations() | Haalt de sub-animatienodes op onder de huidige animaties |

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
| getProperties() | Haalt de verzameling van alle eigenschappen op. |

 **Result:**



---


### findBindPoint{#findBindPoint}

| Naam | Beschrijving |
| --- | --- |
| findBindPoint(name) | Zoekt het bindpunt op naam. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam van het bindpunt om te zoeken. |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| Naam | Beschrijving |
| --- | --- |
| getBindPoint(target, propName, create) | Haalt het animatie‑bindpunt op voor de opgegeven eigenschap. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| target | A3DObject | Op welk object het bindpunt moet worden gemaakt. |
| propName | String | De naam van de eigenschap. |
| create | boolean | Indien ingesteld op |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Naam | Beschrijving |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | Haalt de keyframe‑reeks op voor de opgegeven eigenschap en kanaal. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| target | A3DObject | Op welke instantie de keyframe‑reeks moet worden gemaakt. |
| propName | String | De naam van de eigenschap. |
| channelName | String | De kanaalnaam. |
| create | boolean | Indien ingesteld op |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| Naam | Beschrijving |
| --- | --- |
| getKeyframeSequence(target, propName, create) | Haalt de keyframe‑reeks op voor de opgegeven eigenschap. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| target | A3DObject | Op welke instantie de keyframe‑reeks moet worden gemaakt. |
| propName | String | De naam van de eigenschap. |
| create | boolean | Indien ingesteld op |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| Naam | Beschrijving |
| --- | --- |
| createBindPoint(obj, propName) | Maakt een BindPoint aan op basis van het gegevenstype van de eigenschap. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| obj | A3DObject | Object. |
| propName | String | Naam van eigenschap. |

 **Result:**
BindPoint


---


### removeProperty{#removeProperty}

| Naam | Beschrijving |
| --- | --- |
| removeProperty(property) | Verwijdert een dynamische eigenschap. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| property | Eigenschap | Welke eigenschap moet worden verwijderd |

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
| eigenschap | String | null |

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
| property | String | Naam van eigenschap |

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
| property | String | Naam van eigenschap |
| waarde | Object | De waarde van de eigenschap |

 **Result:**
Object


---


### findProperty{#findProperty}

| Naam | Beschrijving |
| --- | --- |
| findProperty(propertyName) | Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (Created by CreateDynamicProperty/SetProperty) of een native eigenschap (Identified by its name) |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| propertyName | String | Naam van eigenschap. |

 **Result:**
Eigenschap


---



