---
title: "Bone"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/bone/
---
## Bone class

Een bot definieert een subset van de controlepunten van de geometrie en bepaalt het blend‑gewicht voor elk controlepunt.  Het Bone‑object kan niet direct worden gebruikt; een SkinDeformer‑instantie wordt gebruikt om de geometrie te deformereren, en SkinDeformer wordt geleverd met een set botten, waarbij elke bot is gekoppeld aan een node.  OPMERKING: Een controlepunt van een geometrie kan aan meer dan één bot worden gekoppeld.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor(name) | Initialiseert een nieuw exemplaar van de Bone-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload() | Initialiseert een nieuw exemplaar van de Bone-klasse. |

 **Result:**



---


### getWeightCount{#getWeightCount}

| Naam | Beschrijving |
| --- | --- |
| getWeightCount() | Haalt het aantal gewichten op, dit wordt automatisch uitgebreid door setWeight(int, double) |

 **Result:**



---


### getTransform{#getTransform}

| Naam | Beschrijving |
| --- | --- |
| getTransform() | Haalt op of stelt de transformatiesmatrix in van het knooppunt dat het bot bevat. |

 **Result:**



---


### setTransform{#setTransform}

| Naam | Beschrijving |
| --- | --- |
| setTransform(value) | Haalt op of stelt de transformatiesmatrix in van het knooppunt dat het bot bevat. |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| Naam | Beschrijving |
| --- | --- |
| getBoneTransform() | Haalt op of stelt de transformatiesmatrix van het bot in. |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| Naam | Beschrijving |
| --- | --- |
| setBoneTransform(value) | Haalt op of stelt de transformatiesmatrix van het bot in. |

 **Result:**



---


### getNode{#getNode}

| Naam | Beschrijving |
| --- | --- |
| getNode() | Haalt op of stelt het knooppunt in. Het botknooppunt is het bot waaraan de huid is bevestigd; de SkinDeformer zal het botknooppunt gebruiken om de verplaatsing van de controlepunten te beïnvloeden. Het botknooppunt heeft meestal een Skeleton gekoppeld, maar dit is niet vereist. Een gekoppelde Skeleton wordt meestal door DCC-software gebruikt om het skelet aan de gebruiker te tonen. |

 **Result:**



---


### setNode{#setNode}

| Naam | Beschrijving |
| --- | --- |
| setNode(value) | Haalt op of stelt het knooppunt in. Het botknooppunt is het bot waaraan de huid is bevestigd; de SkinDeformer zal het botknooppunt gebruiken om de verplaatsing van de controlepunten te beïnvloeden. Het botknooppunt heeft meestal een Skeleton gekoppeld, maar dit is niet vereist. Een gekoppelde Skeleton wordt meestal door DCC-software gebruikt om het skelet aan de gebruiker te tonen. |

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


### get{#get}

| Naam | Beschrijving |
| --- | --- |
| get(index) |  |

 **Result:**



---


### set{#set}

| Naam | Beschrijving |
| --- | --- |
| set(index, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| Naam | Beschrijving |
| --- | --- |
| getWeight(index) | Haalt het gewicht op voor het controlepunt gespecificeerd door de index |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| index | Nummer | Index van het controlepunt |

 **Result:**
Nummer


---


### setWeight{#setWeight}

| Naam | Beschrijving |
| --- | --- |
| setWeight(index, weight) | Stelt het gewicht in voor het controlepunt gespecificeerd door de index |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| index | Nummer | Index van het controlepunt |
| gewicht | Nummer | Nieuw gewicht |

 **Result:**
Nummer


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



