---
title: "PbrSpecularMaterial"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Material för fysiskt baserad rendering baserat på diffus färg/specular/glossiness


## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| MAP_SPECULAR_GLOSSINESS | Texturkartan för spekulär glans |

## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Konstruktor för PbrSpecularMaterial |

 **Result:**



---


### getTransparency{#getTransparency}

| Namn | Beskrivning |
| --- | --- |
| getTransparency() | Hämtar eller anger transparensfaktorn. Faktorn bör ligga mellan 0 (0 %, helt ogenomskinlig) och 1 (100 %, helt genomskinlig). Eventuellt ogiltigt faktorsvärde kommer att klippas. Transparensfaktorn. |

 **Result:**



---


### setTransparency{#setTransparency}

| Namn | Beskrivning |
| --- | --- |
| setTransparency(value) | Hämtar eller anger transparensfaktorn. Faktorn bör ligga mellan 0 (0 %, helt ogenomskinlig) och 1 (100 %, helt genomskinlig). Eventuellt ogiltigt faktorsvärde kommer att klippas. Transparensfaktorn. |

 **Result:**



---


### getNormalTexture{#getNormalTexture}

| Namn | Beskrivning |
| --- | --- |
| getNormalTexture() | Hämtar eller anger texturen för normalmappning |

 **Result:**



---


### setNormalTexture{#setNormalTexture}

| Namn | Beskrivning |
| --- | --- |
| setNormalTexture(value) | Hämtar eller anger texturen för normalmappning |

 **Result:**



---


### getSpecularGlossinessTexture{#getSpecularGlossinessTexture}

| Namn | Beskrivning |
| --- | --- |
| getSpecularGlossinessTexture() | Hämtar eller anger texturen för spekulär färg, kanal RGB lagrar den spekulära färgen och kanal A lagrar glansigheten. |

 **Result:**



---


### setSpecularGlossinessTexture{#setSpecularGlossinessTexture}

| Namn | Beskrivning |
| --- | --- |
| setSpecularGlossinessTexture(value) | Hämtar eller anger texturen för spekulär färg, kanal RGB lagrar den spekulära färgen och kanal A lagrar glansigheten. |

 **Result:**



---


### getGlossinessFactor{#getGlossinessFactor}

| Namn | Beskrivning |
| --- | --- |
| getGlossinessFactor() | Hämtar eller anger glansigheten (slätheten) för materialet, 1 betyder helt slät och 0 betyder helt grov, standardvärdet är 1, intervallet är [0, 1] |

 **Result:**



---


### setGlossinessFactor{#setGlossinessFactor}

| Namn | Beskrivning |
| --- | --- |
| setGlossinessFactor(value) | Hämtar eller anger glansigheten (slätheten) för materialet, 1 betyder helt slät och 0 betyder helt grov, standardvärdet är 1, intervallet är [0, 1] |

 **Result:**



---


### getSpecular{#getSpecular}

| Namn | Beskrivning |
| --- | --- |
| getSpecular() | Hämtar eller anger den spekulära färgen för materialet, standardvärdet är (1, 1, 1). |

 **Result:**



---


### setSpecular{#setSpecular}

| Namn | Beskrivning |
| --- | --- |
| setSpecular(value) | Hämtar eller anger den spekulära färgen för materialet, standardvärdet är (1, 1, 1). |

 **Result:**



---


### getDiffuseTexture{#getDiffuseTexture}

| Namn | Beskrivning |
| --- | --- |
| getDiffuseTexture() | Hämtar eller anger texturen för diffus |

 **Result:**



---


### setDiffuseTexture{#setDiffuseTexture}

| Namn | Beskrivning |
| --- | --- |
| setDiffuseTexture(value) | Hämtar eller anger texturen för diffus |

 **Result:**



---


### getDiffuse{#getDiffuse}

| Namn | Beskrivning |
| --- | --- |
| getDiffuse() | Hämtar eller anger den diffusa färgen för materialet, standardvärdet är (1, 1, 1) |

 **Result:**



---


### setDiffuse{#setDiffuse}

| Namn | Beskrivning |
| --- | --- |
| setDiffuse(value) | Hämtar eller anger den diffusa färgen för materialet, standardvärdet är (1, 1, 1) |

 **Result:**



---


### getEmissiveTexture{#getEmissiveTexture}

| Namn | Beskrivning |
| --- | --- |
| getEmissiveTexture() | Hämtar eller anger texturen för emissiv |

 **Result:**



---


### setEmissiveTexture{#setEmissiveTexture}

| Namn | Beskrivning |
| --- | --- |
| setEmissiveTexture(value) | Hämtar eller anger texturen för emissiv |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Namn | Beskrivning |
| --- | --- |
| getEmissiveColor() | Hämtar eller anger den emissiva färgen, standardvärdet är (0, 0, 0) |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Namn | Beskrivning |
| --- | --- |
| setEmissiveColor(value) | Hämtar eller anger den emissiva färgen, standardvärdet är (0, 0, 0) |

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



