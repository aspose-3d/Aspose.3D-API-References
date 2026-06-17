---
title: "AnimationClip"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

De animatie‑clip is een verzameling animaties.  De scène kan één of meer animatie‑clips hebben.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuw exemplaar van de klasse AnimationClip. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(name) | Initialiseert een nieuw exemplaar van de klasse AnimationClip. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam |

 **Result:**



---


### getAnimations{#getAnimations}

| Naam | Beschrijving |
| --- | --- |
| getAnimations() | Haalt de animaties op die zich binnen de clip bevinden. De lagen. |

 **Result:**



---


### getDescription{#getDescription}

| Naam | Beschrijving |
| --- | --- |
| getDescription() | Haalt de beschrijving op of stelt deze in van deze animatieclip |

 **Result:**



---


### setDescription{#setDescription}

| Naam | Beschrijving |
| --- | --- |
| setDescription(value) | Haalt de beschrijving op of stelt deze in van deze animatieclip |

 **Result:**



---


### getStart{#getStart}

| Naam | Beschrijving |
| --- | --- |
| getStart() | Haalt de tijd in seconden op of stelt deze in voor het begin van de clip. |

 **Result:**



---


### setStart{#setStart}

| Naam | Beschrijving |
| --- | --- |
| setStart(value) | Haalt de tijd in seconden op of stelt deze in voor het begin van de clip. |

 **Result:**



---


### getStop{#getStop}

| Naam | Beschrijving |
| --- | --- |
| getStop() | Haalt de tijd in seconden op of stelt deze in voor het einde van de clip. |

 **Result:**



---


### setStop{#setStop}

| Naam | Beschrijving |
| --- | --- |
| setStop(value) | Haalt de tijd in seconden op of stelt deze in voor het einde van de clip. |

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


### createAnimationNode{#createAnimationNode}

| Naam | Beschrijving |
| --- | --- |
| createAnimationNode(nodeName) | Een verkorte functie om de animatieknoop te maken en te registreren op de huidige clip. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| nodeName | String | Naam van de nieuwe animatieknoop |

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



