---
title: "MorphTargetChannel"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

Een MorphTargetChannel wordt gebruikt door MorphTargetDeformer om de doelgeometrieën te organiseren.  Sommige bestandsformaten zoals FBX ondersteunen meerdere kanalen parallel.  Gewicht ligt tussen 0 en 1.0, en het standaardgewicht voor het doel is 0.0;


## Properties

| Naam | Beschrijving |
| --- | --- |
| DEFAULT_WEIGHT | Standaardgewicht voor morph target. |

## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor(name) | Initialiseert een nieuw exemplaar van de MorphTargetChannel-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload() | Initialiseert een nieuw exemplaar van de MorphTargetChannel-klasse. |

 **Result:**



---


### getWeights{#getWeights}

| Naam | Beschrijving |
| --- | --- |
| getWeights() | Haalt de volledige gewichtswaarden van doelgeometrieën op. De volledige gewichten. |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| Naam | Beschrijving |
| --- | --- |
| getChannelWeight() | Haalt op of stelt het deformer-gewicht van dit kanaal in. Het gewicht ligt tussen 0,0 en 1,0 |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| Naam | Beschrijving |
| --- | --- |
| setChannelWeight(value) | Haalt op of stelt het deformer-gewicht van dit kanaal in. Het gewicht ligt tussen 0,0 en 1,0 |

 **Result:**



---


### getTargets{#getTargets}

| Naam | Beschrijving |
| --- | --- |
| getTargets() | Haalt alle doelen op die aan het kanaal zijn gekoppeld. |

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


### get{#get}

| Naam | Beschrijving |
| --- | --- |
| get(target) |  |

 **Result:**



---


### set{#set}

| Naam | Beschrijving |
| --- | --- |
| set(target, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| Naam | Beschrijving |
| --- | --- |
| getWeight(target) | Haalt het gewicht op voor het opgegeven doel, als het doel niet tot dit kanaal behoort, wordt de standaardwaarde 0 geretourneerd. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| targe | Shape | null |

 **Result:**
Number


---


### setWeight{#setWeight}

| Naam | Beschrijving |
| --- | --- |
| setWeight(target, weight) | Stelt het gewicht in voor het opgegeven doel, de standaardwaarde is 1, het bereik moet tussen 0 en 1 liggen. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| targe | Shape | null |
| weigh | Number | null |

 **Result:**
Number


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



