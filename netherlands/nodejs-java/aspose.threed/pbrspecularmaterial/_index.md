---
title: "PbrSpecularMaterial"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Materiaal voor fysiek gebaseerd renderen gebaseerd op diffuse kleur/specular/glans


## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| MAP_SPECULAR_GLOSSINESS | De textuurkaart voor speculaire glans |

## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Constructor van de PbrSpecularMaterial |

 **Result:**



---


### getTransparency{#getTransparency}

| Naam | Beschrijving |
| --- | --- |
| getTransparency() | Haalt of stelt de transparantiefactor in. De factor moet liggen tussen 0 (0%, volledig ondoorzichtig) en 1 (100%, volledig transparant). Elke ongeldige factorwaarde wordt begrensd. De transparantiefactor. |

 **Result:**



---


### setTransparency{#setTransparency}

| Naam | Beschrijving |
| --- | --- |
| setTransparency(value) | Haalt of stelt de transparantiefactor in. De factor moet liggen tussen 0 (0%, volledig ondoorzichtig) en 1 (100%, volledig transparant). Elke ongeldige factorwaarde wordt begrensd. De transparantiefactor. |

 **Result:**



---


### getNormalTexture{#getNormalTexture}

| Naam | Beschrijving |
| --- | --- |
| getNormalTexture() | Haalt of stelt de textuur van normale mapping in |

 **Result:**



---


### setNormalTexture{#setNormalTexture}

| Naam | Beschrijving |
| --- | --- |
| setNormalTexture(value) | Haalt of stelt de textuur van normale mapping in |

 **Result:**



---


### getSpecularGlossinessTexture{#getSpecularGlossinessTexture}

| Naam | Beschrijving |
| --- | --- |
| getSpecularGlossinessTexture() | Haalt of stelt de textuur voor speculaire kleur in, kanaal RGB slaat de speculaire kleur op en kanaal A slaat de glans op. |

 **Result:**



---


### setSpecularGlossinessTexture{#setSpecularGlossinessTexture}

| Naam | Beschrijving |
| --- | --- |
| setSpecularGlossinessTexture(value) | Haalt of stelt de textuur voor speculaire kleur in, kanaal RGB slaat de speculaire kleur op en kanaal A slaat de glans op. |

 **Result:**



---


### getGlossinessFactor{#getGlossinessFactor}

| Naam | Beschrijving |
| --- | --- |
| getGlossinessFactor() | Haalt of stelt de glans (gladheid) van het materiaal in, 1 betekent perfect glad en 0 betekent perfect ruw, standaardwaarde is 1, bereik is [0, 1] |

 **Result:**



---


### setGlossinessFactor{#setGlossinessFactor}

| Naam | Beschrijving |
| --- | --- |
| setGlossinessFactor(value) | Haalt of stelt de glans (gladheid) van het materiaal in, 1 betekent perfect glad en 0 betekent perfect ruw, standaardwaarde is 1, bereik is [0, 1] |

 **Result:**



---


### getSpecular{#getSpecular}

| Naam | Beschrijving |
| --- | --- |
| getSpecular() | Haalt of stelt de speculaire kleur van het materiaal in, standaardwaarde is (1, 1, 1). |

 **Result:**



---


### setSpecular{#setSpecular}

| Naam | Beschrijving |
| --- | --- |
| setSpecular(value) | Haalt of stelt de speculaire kleur van het materiaal in, standaardwaarde is (1, 1, 1). |

 **Result:**



---


### getDiffuseTexture{#getDiffuseTexture}

| Naam | Beschrijving |
| --- | --- |
| getDiffuseTexture() | Haalt of stelt de textuur voor diffuse in |

 **Result:**



---


### setDiffuseTexture{#setDiffuseTexture}

| Naam | Beschrijving |
| --- | --- |
| setDiffuseTexture(value) | Haalt of stelt de textuur voor diffuse in |

 **Result:**



---


### getDiffuse{#getDiffuse}

| Naam | Beschrijving |
| --- | --- |
| getDiffuse() | Haalt of stelt de diffuse kleur van het materiaal in, standaardwaarde is (1, 1, 1) |

 **Result:**



---


### setDiffuse{#setDiffuse}

| Naam | Beschrijving |
| --- | --- |
| setDiffuse(value) | Haalt of stelt de diffuse kleur van het materiaal in, standaardwaarde is (1, 1, 1) |

 **Result:**



---


### getEmissiveTexture{#getEmissiveTexture}

| Naam | Beschrijving |
| --- | --- |
| getEmissiveTexture() | Haalt op of stelt de emissieve textuur in |

 **Result:**



---


### setEmissiveTexture{#setEmissiveTexture}

| Naam | Beschrijving |
| --- | --- |
| setEmissiveTexture(value) | Haalt op of stelt de emissieve textuur in |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Naam | Beschrijving |
| --- | --- |
| getEmissiveColor() | Haalt op of stelt de emissieve kleur in, standaardwaarde is (0, 0, 0) |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Naam | Beschrijving |
| --- | --- |
| setEmissiveColor(value) | Haalt op of stelt de emissieve kleur in, standaardwaarde is (0, 0, 0) |

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



