---
title: "ShaderMaterial"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/shadermaterial/
---
## ShaderMaterial class

Een shader‑materiaal maakt het mogelijk om het materiaal te beschrijven met een externe renderengine of shader‑taal.  ShaderMaterial gebruikt ShaderTechnique om de concrete renderdetails te beschrijven,  en de meest geschikte wordt gebruikt op basis van het uiteindelijke renderplatform.  Bijvoorbeeld, uw ShaderMaterial‑instantie kan twee technieken hebben, één gedefinieerd door HLSL en een andere gedefinieerd door GLSL.  Op niet‑Windows‑platforms moet de GLSL in plaats van de HLSL worden gebruikt.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuw exemplaar van de ShaderMaterial-klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(name) | Initialiseert een nieuw exemplaar van de ShaderMaterial-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam |

 **Result:**



---


### getTechniques{#getTechniques}

| Naam | Beschrijving |
| --- | --- |
| getTechniques() | Haalt alle beschikbare technieken op die in dit materiaal zijn gedefinieerd. |

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


### getTexture{#getTexture}

| Naam | Beschrijving |
| --- | --- |
| getTexture(slotName) | Haalt de textuur op uit de opgegeven slot, dit kan de eigenschapsnaam van het materiaal of de parameternaam van de shader zijn. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| slotName | String | Slotnaam. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| Naam | Beschrijving |
| --- | --- |
| setTexture(slotName, texture) | Stelt de textuur in voor de opgegeven slot. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| slotName | String | Slotnaam. |
| texture | TextureBase | Textuur. |

 **Result:**
TextureBase


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


### iterator{#iterator}

| Naam | Beschrijving |
| --- | --- |
| iterator() | Gereserveerd voor intern gebruik. |

 **Result:**
Eigenschap


---



