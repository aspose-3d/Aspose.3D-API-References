---
title: "BindPoint"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

Een BindPoint wordt meestal aangemaakt op een eigenschap van een object; sommige eigenschapstypen bevatten meerdere componentvelden (zoals een Vector3‑veld).  BindPoint genereert een kanaal voor elk componentveld en verbindt het veld via de kanalen met één of meer keyframe‑sequentie‑instanties.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor(scene, prop) | Initialiseert een nieuw exemplaar van de BindPoint‑klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| scene | Scene | De scène die de animatie bevat. |
| prop | Eigenschap | Eigenschap. |

 **Result:**



---


### getProperty{#getProperty}

| Naam | Beschrijving |
| --- | --- |
| getProperty() | Haalt de eigenschap op die geassocieerd is met de CurveMapping |

 **Result:**



---


### setProperty{#setProperty}

| Naam | Beschrijving |
| --- | --- |
| setProperty(value) | Haalt de eigenschap op die geassocieerd is met de CurveMapping |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| Naam | Beschrijving |
| --- | --- |
| getChannelsCount() | Haalt het totale aantal eigenschapskanalen op dat is gedefinieerd in deze animatiecurve-mapping. |

 **Result:**
Nummer


---


### getName{#getName}

| Naam | Beschrijving |
| --- | --- |
| getName() | Haalt de naam op of stelt deze in. De naam. |

 **Result:**
Nummer


---


### setName{#setName}

| Naam | Beschrijving |
| --- | --- |
| setName(value) | Haalt de naam op of stelt deze in. De naam. |

 **Result:**
Nummer


---


### getProperties{#getProperties}

| Naam | Beschrijving |
| --- | --- |
| getProperties() | Haalt de verzameling van alle eigenschappen op. |

 **Result:**
Nummer


---


### get{#get}

| Naam | Beschrijving |
| --- | --- |
| get(channelName) |  |

 **Result:**
Nummer


---


### getKeyframeSequence{#getKeyframeSequence}

| Naam | Beschrijving |
| --- | --- |
| getKeyframeSequence(channelName) | Haalt de eerste keyframe-reeks op in het opgegeven kanaal |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| channelName | String | De kanaalnaam om te vinden |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| Naam | Beschrijving |
| --- | --- |
| getKeyframeSequences(channelName) | Haalt alle keyframe-reeksen op in het opgegeven kanaal |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| channelName | String | De kanaalnaam om te vinden |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| Naam | Beschrijving |
| --- | --- |
| createKeyframeSequence(name) | Maakt een nieuwe curve aan en verbindt deze met het eerste kanaal van de curve-mapping |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | De naam van de nieuwe reeks. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| Naam | Beschrijving |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | Koppel de keyframe-reeks aan het opgegeven kanaal |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| channelName | String | Welk kanaal de keyframe-reeks aan gekoppeld zal worden |
| reeks | KeyframeSequence | De te koppelen keyframe-reeks |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| Naam | Beschrijving |
| --- | --- |
| getChannel(channelName) | Haalt kanaal op op basis van de opgegeven naam |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| channelName | String | De kanaalnaam om te vinden |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| Naam | Beschrijving |
| --- | --- |
| addChannel(name, value) | Voegt de opgegeven kanaaleigenschap toe. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam. |
| waarde | Object | Waarde. |

 **Result:**
boolean


---


### addChannel{#addChannel}

| Naam | Beschrijving |
| --- | --- |
| addChannel(name, type, value) | Voegt de opgegeven kanaaleigenschap toe. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam. |
| type | Klasse | Type. |
| waarde | Object | Waarde. |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| Naam | Beschrijving |
| --- | --- |
| resetChannels() | Leegt de eigenschap channels van deze animatiecurve-mapping. |

 **Result:**
boolean


---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() | Formatteert object naar string. |

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



