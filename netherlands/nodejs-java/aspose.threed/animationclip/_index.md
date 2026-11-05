---
title: "AnimationClip"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

De animatie‑clip is een verzameling animaties.  De scène kan één of meer animatie‑clips bevatten.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuw exemplaar van de AnimationClip-klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(name) | Initialiseert een nieuw exemplaar van de AnimationClip-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam |

 **Result:**



---


### getAnimations{#getAnimations}

| Naam | Beschrijving |
| --- | --- |
| getAnimations() | Haalt de animaties op die in de clip zitten. De lagen. |

 **Result:**



---


### getDescription{#getDescription}

| Naam | Beschrijving |
| --- | --- |
| getDescription() | Haalt op of stelt de beschrijving van deze animatieclip in |

 **Result:**



---


### setDescription{#setDescription}

| Naam | Beschrijving |
| --- | --- |
| setDescription(value) | Haalt op of stelt de beschrijving van deze animatieclip in |

 **Result:**



---


### getStart{#getStart}

| Naam | Beschrijving |
| --- | --- |
| getStart() | Haalt op of stelt de tijd in seconden van het begin van de clip in. |

 **Result:**



---


### setStart{#setStart}

| Naam | Beschrijving |
| --- | --- |
| setStart(value) | Haalt op of stelt de tijd in seconden van het begin van de clip in. |

 **Result:**



---


### getStop{#getStop}

| Naam | Beschrijving |
| --- | --- |
| getStop() | Haalt op of stelt de tijd in seconden van het einde van de clip in. |

 **Result:**



---


### setStop{#setStop}

| Naam | Beschrijving |
| --- | --- |
| setStop(value) | Haalt op of stelt de tijd in seconden van het einde van de clip in. |

 **Result:**



---


### getScene{#getScene}

| Naam | Beschrijving |
| --- | --- |
| getScene() | Haalt de scène op waartoe dit object behoort |

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


### createAnimationNode{#createAnimationNode}

| Naam | Beschrijving |
| --- | --- |
| createAnimationNode(nodeName) | Een verkorte functie om het animatieknooppunt op de huidige clip te maken en te registreren. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| nodeName | String | Naam van nieuw animatieknooppunt |

 **Result:**
AnimationNode


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



