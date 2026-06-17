---
title: "Property"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/property/
---
## Property class

Klass för att hålla användardefinierade egenskaper.  @hideconstructor


## Metoder

### getValue{#getValue}

| Namn | Beskrivning |
| --- | --- |
| getValue() | Hämtar eller anger värdet. Värdet. |

 **Result:**



---


### setValue{#setValue}

| Namn | Beskrivning |
| --- | --- |
| setValue(value) | Hämtar eller anger värdet. Värdet. |

 **Result:**



---


### setName{#setName}

| Namn | Beskrivning |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| Namn | Beskrivning |
| --- | --- |
| getValueType() | Hämtar typen av egenskapsvärdet. Typen av värdet. |

 **Result:**



---


### getProperties{#getProperties}

| Namn | Beskrivning |
| --- | --- |
| getProperties() | Hämtar samlingen av alla egenskaper. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Namn | Beskrivning |
| --- | --- |
| getBindPoint(anim, create) | Hämtar egenskapens bindningspunkt på den angivna animationsinstansen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| anim | AnimationNode | På vilken animation som bindpunkten ska skapas. |
| skapa | boolean | Skapa egenskapsbindpunkten om den inte finns. |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Namn | Beskrivning |
| --- | --- |
| getKeyframeSequence(anim, create) | Hämtar nyckelbildssekvensen för den angivna animationsinstansen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| anim | AnimationNode | På vilken animation som nyckelbildssekvensen ska skapas. |
| skapa | boolean | Skapa nyckelbildssekvensen om den inte finns. |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| Namn | Beskrivning |
| --- | --- |
| toString() | Returnerar en sträng som representerar den aktuella egenskapen. |

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



