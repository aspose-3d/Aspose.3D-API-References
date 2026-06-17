---
title: "BindPoint"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

En BindPoint skapas vanligtvis på ett objekts egenskap, vissa egenskapstyper innehåller flera komponentfält (som ett Vector3-fält),  BindPoint kommer att generera en kanal för varje komponentfält och ansluter fältet till en eller flera nyckelramsekvensinstans(er) via kanalerna.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor(scene, prop) | Initierar en ny instans av klassen BindPoint. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| scen | Scene | Scenen som innehåller animationen. |
| prop | Property | Egenskap. |

 **Result:**



---


### getProperty{#getProperty}

| Namn | Beskrivning |
| --- | --- |
| getProperty() | Hämtar egenskapen som är associerad med CurveMapping |

 **Result:**



---


### setProperty{#setProperty}

| Namn | Beskrivning |
| --- | --- |
| setProperty(value) | Hämtar egenskapen som är associerad med CurveMapping |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| Namn | Beskrivning |
| --- | --- |
| getChannelsCount() | Hämtar det totala antalet egenskapskanaler som definierats i denna animation CurveMapping. |

 **Result:**
Nummer


---


### getName{#getName}

| Namn | Beskrivning |
| --- | --- |
| getName() | Hämtar eller anger namnet. Namnet. |

 **Result:**
Nummer


---


### setName{#setName}

| Namn | Beskrivning |
| --- | --- |
| setName(value) | Hämtar eller anger namnet. Namnet. |

 **Result:**
Nummer


---


### getProperties{#getProperties}

| Namn | Beskrivning |
| --- | --- |
| getProperties() | Hämtar samlingen av alla egenskaper. |

 **Result:**
Nummer


---


### get{#get}

| Namn | Beskrivning |
| --- | --- |
| get(channelName) |  |

 **Result:**
Nummer


---


### getKeyframeSequence{#getKeyframeSequence}

| Namn | Beskrivning |
| --- | --- |
| getKeyframeSequence(channelName) | Hämtar den första nyckelramsekvensen i angiven kanal |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| channelName | Sträng | Kanalnamnet att hitta |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| Namn | Beskrivning |
| --- | --- |
| getKeyframeSequences(channelName) | Hämtar alla nyckelramsekvenser i angiven kanal |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| channelName | Sträng | Kanalnamnet att hitta |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| Namn | Beskrivning |
| --- | --- |
| createKeyframeSequence(name) | Skapar en ny kurva och ansluter den till den första kanalen i kurvavbildningen |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Det nya sekvensens namn. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| Namn | Beskrivning |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | Koppla nyckelramsekvensen till den angivna kanalen |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| channelName | Sträng | Vilken kanal nyckelramsekvensen kommer att bindas till |
| sekvens | KeyframeSequence | Nyckelramsekvensen att binda |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| Namn | Beskrivning |
| --- | --- |
| getChannel(channelName) | Hämtar kanal med angivet namn |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| channelName | Sträng | Kanalnamnet att hitta |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| Namn | Beskrivning |
| --- | --- |
| addChannel(name, value) | Lägger till den angivna kanalegenskapen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn. |
| värde | Objekt | Värde. |

 **Result:**
boolean


---


### addChannel{#addChannel}

| Namn | Beskrivning |
| --- | --- |
| addChannel(name, type, value) | Lägger till den angivna kanalegenskapen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn. |
| typ | Klass | Typ. |
| värde | Objekt | Värde. |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| Namn | Beskrivning |
| --- | --- |
| resetChannels() | Tömmer egenskapskanalerna i denna animationskurvavbildning. |

 **Result:**
boolean


---


### toString{#toString}

| Namn | Beskrivning |
| --- | --- |
| toString() | Formaterar objekt till sträng. |

 **Result:**
Sträng


---


### removeProperty{#removeProperty}

| Namn | Beskrivning |
| --- | --- |
| removeProperty(property) | Tar bort en dynamisk egenskap. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| property | Property | Vilken egenskap som ska tas bort |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Namn | Beskrivning |
| --- | --- |
| removeProperty(property) | Ta bort den angivna egenskapen som identifieras med namn |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| propert | Sträng | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Namn | Beskrivning |
| --- | --- |
| getProperty(property) | Hämta värdet för den angivna egenskapen |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| property | Sträng | Egenskapsnamn |

 **Result:**
Objekt


---


### setProperty{#setProperty}

| Namn | Beskrivning |
| --- | --- |
| setProperty(property, value) | Sätter värdet för den angivna egenskapen |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| property | Sträng | Egenskapsnamn |
| värde | Objekt | Värdet för egenskapen |

 **Result:**
Objekt


---


### findProperty{#findProperty}

| Namn | Beskrivning |
| --- | --- |
| findProperty(propertyName) | Hittar egenskapen. Det kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad av dess namn) |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| propertyName | Sträng | Egenskapsnamn. |

 **Result:**
Property


---



