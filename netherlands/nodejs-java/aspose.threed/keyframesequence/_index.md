---
title: "KeyframeSequence"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

De reeks van keyframes, die de transformatie van een bemonsterde waarde over tijd beschrijft.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor(name) | Initialiseert een nieuw exemplaar van de KeyframeSequence-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload() | Initialiseert een nieuw exemplaar van de KeyframeSequence-klasse. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Naam | Beschrijving |
| --- | --- |
| getBindPoint() | Haalt het bindpunt van de eigenschap op dat deze curve bezit |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| Naam | Beschrijving |
| --- | --- |
| getKeyFrames() | Haalt de keyframes van deze curve op. De sleutels. |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| Naam | Beschrijving |
| --- | --- |
| getPostBehavior() | Haalt het postgedrag op, dat aangeeft wat de bemonsterde waarde moet zijn na het laatste keyframe. |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| Naam | Beschrijving |
| --- | --- |
| getPreBehavior() | Haalt het pregedrag op, dat aangeeft wat de bemonsterde waarde moet zijn vóór de eerste sleutel. |

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


### add{#add}

| Naam | Beschrijving |
| --- | --- |
| add(time, value) | Maak een nieuw keyframe met de opgegeven waarde |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| tijd | Number | Tijdpositie(gemeten in seconden) |
| value | Number | De waarde op deze tijdpositie |

 **Result:**



---


### add{#add}

| Naam | Beschrijving |
| --- | --- |
| add(time, value, interpolation) | Maak een nieuw keyframe met de opgegeven waarde |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| tijd | Number | Tijdpositie(gemeten in seconden) |
| value | Number | De waarde op deze tijdpositie |
| interpolatie | Interpolatie | Interpolatie |

 **Result:**



---


### reset{#reset}

| Naam | Beschrijving |
| --- | --- |
| reset() | Verwijdert alle keyframes en reset de post/pre-gedragingen. |

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


### iterator{#iterator}

| Naam | Beschrijving |
| --- | --- |
| iterator() | Gereserveerd voor intern gebruik. |

 **Result:**
Eigenschap


---



