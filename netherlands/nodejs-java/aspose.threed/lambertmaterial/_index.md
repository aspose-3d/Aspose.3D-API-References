---
title: "LambertMaterial"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/lambertmaterial/
---
## LambertMaterial class

Materiaal voor Lambert-shadingmodel


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuw exemplaar van de LambertMaterial-klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(name) | Initialiseert een nieuw exemplaar van de LambertMaterial-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Naam | Beschrijving |
| --- | --- |
| getEmissiveColor() | Haalt op of stelt de emissieve kleur in |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Naam | Beschrijving |
| --- | --- |
| setEmissiveColor(value) | Haalt op of stelt de emissieve kleur in |

 **Result:**



---


### getAmbientColor{#getAmbientColor}

| Naam | Beschrijving |
| --- | --- |
| getAmbientColor() | Haalt op of stelt de omgevingskleur in. Het voorbeeld: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| Naam | Beschrijving |
| --- | --- |
| setAmbientColor(value) | Haalt op of stelt de omgevingskleur in. Het voorbeeld: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| Naam | Beschrijving |
| --- | --- |
| getDiffuseColor() | Haalt de diffuse kleur op of stelt deze in Het voorbeeld: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); diffuus. |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| Naam | Beschrijving |
| --- | --- |
| setDiffuseColor(value) | Haalt de diffuse kleur op of stelt deze in Het voorbeeld: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); diffuus. |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| Naam | Beschrijving |
| --- | --- |
| getTransparentColor() | Haalt de transparante kleur op of stelt deze in. Het voorbeeld: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); kleur van de transparante. |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| Naam | Beschrijving |
| --- | --- |
| setTransparentColor(value) | Haalt de transparante kleur op of stelt deze in. Het voorbeeld: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); kleur van de transparante. |

 **Result:**



---


### getTransparency{#getTransparency}

| Naam | Beschrijving |
| --- | --- |
| getTransparency() | Haalt de transparantiefactor op of stelt deze in. De factor moet liggen tussen 0 (0%, volledig ondoorzichtig) en 1 (100%, volledig transparant). Elke ongeldige factorwaarde wordt begrensd. Het voorbeeld: var mat = new LambertMaterial(); mat.Transparency = 0.3; transparantiefactor. |

 **Result:**



---


### setTransparency{#setTransparency}

| Naam | Beschrijving |
| --- | --- |
| setTransparency(value) | Haalt de transparantiefactor op of stelt deze in. De factor moet liggen tussen 0 (0%, volledig ondoorzichtig) en 1 (100%, volledig transparant). Elke ongeldige factorwaarde wordt begrensd. Het voorbeeld: var mat = new LambertMaterial(); mat.Transparency = 0.3; transparantiefactor. |

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


### getTexture{#getTexture}

| Naam | Beschrijving |
| --- | --- |
| getTexture(slotName) | Haalt de textuur op uit de opgegeven slot, dit kan de naam van een materiaaleigenschap of de naam van een shaderparameter zijn. |

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
| setTexture(slotName, texture) | Stelt de textuur in op de opgegeven slot |

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
| toString() | Formatteert object naar string |

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


### iterator{#iterator}

| Naam | Beschrijving |
| --- | --- |
| iterator() | Gereserveerd voor intern gebruik. |

 **Result:**
Eigenschap


---



