---
title: "LambertMaterial"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/lambertmaterial/
---
## LambertMaterial class

Material för lambert-skuggningsmodell


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Initierar en ny instans av klassen LambertMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(name) | Initierar en ny instans av klassen LambertMaterial. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Namn | Beskrivning |
| --- | --- |
| getEmissiveColor() | Hämtar eller anger den emissiva färgen |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Namn | Beskrivning |
| --- | --- |
| setEmissiveColor(value) | Hämtar eller anger den emissiva färgen |

 **Result:**



---


### getAmbientColor{#getAmbientColor}

| Namn | Beskrivning |
| --- | --- |
| getAmbientColor() | Hämtar eller anger den omgivande färgen. Exempel: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| Namn | Beskrivning |
| --- | --- |
| setAmbientColor(value) | Hämtar eller anger den omgivande färgen. Exempel: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| Namn | Beskrivning |
| --- | --- |
| getDiffuseColor() | Hämtar eller anger den diffusa färgen Exempel: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); diffus. |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| Namn | Beskrivning |
| --- | --- |
| setDiffuseColor(value) | Hämtar eller anger den diffusa färgen Exempel: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); diffus. |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| Namn | Beskrivning |
| --- | --- |
| getTransparentColor() | Hämtar eller anger den transparenta färgen. Exempel: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); färgen på den transparenta. |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| Namn | Beskrivning |
| --- | --- |
| setTransparentColor(value) | Hämtar eller anger den transparenta färgen. Exempel: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); färgen på den transparenta. |

 **Result:**



---


### getTransparency{#getTransparency}

| Namn | Beskrivning |
| --- | --- |
| getTransparency() | Hämtar eller anger transparensfaktorn. Faktorn bör ligga mellan 0 (0 %, helt ogenomskinlig) och 1 (100 %, helt genomskinlig). Alla ogiltiga faktorer kommer att klippas. Exempel: var mat = new LambertMaterial(); mat.Transparency = 0.3; transparensfaktor. |

 **Result:**



---


### setTransparency{#setTransparency}

| Namn | Beskrivning |
| --- | --- |
| setTransparency(value) | Hämtar eller anger transparensfaktorn. Faktorn bör ligga mellan 0 (0 %, helt ogenomskinlig) och 1 (100 %, helt genomskinlig). Alla ogiltiga faktorer kommer att klippas. Exempel: var mat = new LambertMaterial(); mat.Transparency = 0.3; transparensfaktor. |

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



