---
title: "ShaderMaterial"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/shadermaterial/
---
## ShaderMaterial class

Ett shader‑material tillåter att beskriva materialet med en extern renderingsmotor eller shader‑språk.  ShaderMaterial använder ShaderTechnique för att beskriva de konkreta renderingsdetaljerna,  och den mest lämpliga kommer att användas enligt den slutgiltiga renderingsplattformen.  Till exempel kan din ShaderMaterial‑instans ha två tekniker, en definierad av HLSL och en annan definierad av GLSL.  På icke‑Windows‑plattform bör GLSL användas istället för HLSL.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Initierar en ny instans av ShaderMaterial‑klassen. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(name) | Initierar en ny instans av ShaderMaterial‑klassen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn |

 **Result:**



---


### getTechniques{#getTechniques}

| Namn | Beskrivning |
| --- | --- |
| getTechniques() | Hämtar alla tillgängliga tekniker som definieras i detta material. |

 **Result:**



---


### getName{#getName}

| Namn | Beskrivning |
| --- | --- |
| getName() | Hämtar eller anger namnet. Namnet. |

 **Result:**



---


### setName{#setName}

| Namn | Beskrivning |
| --- | --- |
| setName(value) | Hämtar eller anger namnet. Namnet. |

 **Result:**



---


### getProperties{#getProperties}

| Namn | Beskrivning |
| --- | --- |
| getProperties() | Hämtar samlingen av alla egenskaper. |

 **Result:**



---


### getTexture{#getTexture}

| Namn | Beskrivning |
| --- | --- |
| getTexture(slotName) | Hämtar texturen från den angivna sloten, den kan vara materialets egenskapsnamn eller shaderns parameternamn |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| slotName | Sträng | Slotnamn. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| Namn | Beskrivning |
| --- | --- |
| setTexture(slotName, texture) | Anger texturen till den angivna sloten |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| slotName | Sträng | Slotnamn. |
| texture | TextureBase | Textur. |

 **Result:**
TextureBase


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


### iterator{#iterator}

| Namn | Beskrivning |
| --- | --- |
| iterator() | Reserverad för internt bruk. |

 **Result:**
Property


---



