---
title: "Eigenschap"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/property/
---
## Property class

Klasse om door de gebruiker gedefinieerde eigenschappen vast te houden.  @hideconstructor


## Methoden

### getValue{#getValue}

| Naam | Beschrijving |
| --- | --- |
| getValue() | Haalt de waarde op of stelt deze in. De waarde. |

 **Result:**



---


### setValue{#setValue}

| Naam | Beschrijving |
| --- | --- |
| setValue(value) | Haalt de waarde op of stelt deze in. De waarde. |

 **Result:**



---


### setName{#setName}

| Naam | Beschrijving |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| Naam | Beschrijving |
| --- | --- |
| getValueType() | Haalt het type van de eigenschapswaarde op. Het type van de waarde. |

 **Result:**



---


### getProperties{#getProperties}

| Naam | Beschrijving |
| --- | --- |
| getProperties() | Haalt de collectie van alle eigenschappen op. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Naam | Beschrijving |
| --- | --- |
| getBindPoint(anim, create) | Haalt het bindpunt van de eigenschap op in de opgegeven animatie‑instantie. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| anim | AnimationNode | Op welke animatie moet het bind point worden gemaakt. |
| maken | boolean | Maak het property bind point aan als het niet wordt gevonden. |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Naam | Beschrijving |
| --- | --- |
| getKeyframeSequence(anim, create) | Haalt de keyframe sequence op van de opgegeven animatie‑instantie. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| anim | AnimationNode | Op welke animatie moet de keyframe sequence worden gemaakt. |
| maken | boolean | Maak de keyframe sequence aan als deze niet wordt gevonden. |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() | Retourneert een string die de huidige Property weergeeft. |

 **Result:**
String


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



