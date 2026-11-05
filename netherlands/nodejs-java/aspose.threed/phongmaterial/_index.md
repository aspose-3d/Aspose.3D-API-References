---
title: "PhongMaterial"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/phongmaterial/
---
## PhongMaterial class

Materiaal voor het Blinn‑Phong shading‑model.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuw exemplaar van de PhongMaterial-klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(name) | Initialiseert een nieuw exemplaar van de PhongMaterial-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam |

 **Result:**



---


### getSpecularColor{#getSpecularColor}

| Naam | Beschrijving |
| --- | --- |
| getSpecularColor() | Haalt op of stelt de speculaire kleur in. |

 **Result:**



---


### setSpecularColor{#setSpecularColor}

| Naam | Beschrijving |
| --- | --- |
| setSpecularColor(value) | Haalt op of stelt de speculaire kleur in. |

 **Result:**



---


### getSpecularFactor{#getSpecularFactor}

| Naam | Beschrijving |
| --- | --- |
| getSpecularFactor() | Haalt op of stelt de speculaire factor in. De formule van specular: SpecularColor SpecularFactor (N dot H) ^ Shininess |

 **Result:**



---


### setSpecularFactor{#setSpecularFactor}

| Naam | Beschrijving |
| --- | --- |
| setSpecularFactor(value) | Haalt op of stelt de speculaire factor in. De formule van specular: SpecularColor SpecularFactor (N dot H) ^ Shininess |

 **Result:**



---


### getShininess{#getShininess}

| Naam | Beschrijving |
| --- | --- |
| getShininess() | Haalt op of stelt de glans in, dit bepaalt de grootte van de speculaire highlight. De formule van specular: SpecularColor SpecularFactor (N dot H) ^ Shininess De glans. |

 **Result:**



---


### setShininess{#setShininess}

| Naam | Beschrijving |
| --- | --- |
| setShininess(value) | Haalt op of stelt de glans in, dit bepaalt de grootte van de speculaire highlight. De formule van specular: SpecularColor SpecularFactor (N dot H) ^ Shininess De glans. |

 **Result:**



---


### getReflectionColor{#getReflectionColor}

| Naam | Beschrijving |
| --- | --- |
| getReflectionColor() | Haalt op of stelt de reflectiekleur in. De reflectie. |

 **Result:**



---


### setReflectionColor{#setReflectionColor}

| Naam | Beschrijving |
| --- | --- |
| setReflectionColor(value) | Haalt op of stelt de reflectiekleur in. De reflectie. |

 **Result:**



---


### getReflectionFactor{#getReflectionFactor}

| Naam | Beschrijving |
| --- | --- |
| getReflectionFactor() | Haalt op of stelt de demping van de reflectiekleur in. De reflectiefactor. |

 **Result:**



---


### setReflectionFactor{#setReflectionFactor}

| Naam | Beschrijving |
| --- | --- |
| setReflectionFactor(value) | Haalt op of stelt de demping van de reflectiekleur in. De reflectiefactor. |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Naam | Beschrijving |
| --- | --- |
| getEmissiveColor() | Haalt of stelt de emissieve kleur in |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Naam | Beschrijving |
| --- | --- |
| setEmissiveColor(value) | Haalt of stelt de emissieve kleur in |

 **Result:**



---


### getAmbientColor{#getAmbientColor}

| Naam | Beschrijving |
| --- | --- |
| getAmbientColor() | Haalt of stelt de omgevingskleur in Voorbeeld: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| Naam | Beschrijving |
| --- | --- |
| setAmbientColor(value) | Haalt of stelt de omgevingskleur in Voorbeeld: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| Naam | Beschrijving |
| --- | --- |
| getDiffuseColor() | Haalt of stelt de diffuse kleur in Voorbeeld: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); diffuse. |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| Naam | Beschrijving |
| --- | --- |
| setDiffuseColor(value) | Haalt of stelt de diffuse kleur in Voorbeeld: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); diffuse. |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| Naam | Beschrijving |
| --- | --- |
| getTransparentColor() | Haalt of stelt de transparante kleur in. Voorbeeld: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); kleur van de transparante. |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| Naam | Beschrijving |
| --- | --- |
| setTransparentColor(value) | Haalt of stelt de transparante kleur in. Voorbeeld: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); kleur van de transparante. |

 **Result:**



---


### getTransparency{#getTransparency}

| Naam | Beschrijving |
| --- | --- |
| getTransparency() | Haalt of stelt de transparantiefactor in. De factor moet liggen tussen 0 (0%, volledig ondoorzichtig) en 1 (100%, volledig transparant). Elke ongeldige factorwaarde wordt begrensd. Voorbeeld: var mat = new LambertMaterial(); mat.Transparency = 0.3; transparantiefactor. |

 **Result:**



---


### setTransparency{#setTransparency}

| Naam | Beschrijving |
| --- | --- |
| setTransparency(value) | Haalt of stelt de transparantiefactor in. De factor moet liggen tussen 0 (0%, volledig ondoorzichtig) en 1 (100%, volledig transparant). Elke ongeldige factorwaarde wordt begrensd. Voorbeeld: var mat = new LambertMaterial(); mat.Transparency = 0.3; transparantiefactor. |

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



