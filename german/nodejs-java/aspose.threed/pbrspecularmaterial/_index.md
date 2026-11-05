---
title: "PbrSpecularMaterial"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Material für physikalisch basiertes Rendering basierend auf Diffusfarbe/Spezular/Glanz


## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| MAP_SPECULAR_GLOSSINESS | Die Texturkarte für spekulare Glanzlichter |

## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Konstruktor von PbrSpecularMaterial |

 **Result:**



---


### getTransparency{#getTransparency}

| Name | Beschreibung |
| --- | --- |
| getTransparency() | Liest oder setzt den Transparenzfaktor. Der Faktor sollte im Bereich zwischen 0 (0 %, vollständig undurchsichtig) und 1 (100 %, vollständig transparent) liegen. Jeder ungültige Faktorwert wird geklemmt. Der Transparenzfaktor. |

 **Result:**



---


### setTransparency{#setTransparency}

| Name | Beschreibung |
| --- | --- |
| setTransparency(value) | Liest oder setzt den Transparenzfaktor. Der Faktor sollte im Bereich zwischen 0 (0 %, vollständig undurchsichtig) und 1 (100 %, vollständig transparent) liegen. Jeder ungültige Faktorwert wird geklemmt. Der Transparenzfaktor. |

 **Result:**



---


### getNormalTexture{#getNormalTexture}

| Name | Beschreibung |
| --- | --- |
| getNormalTexture() | Liest oder setzt die Textur der Normalenabbildung |

 **Result:**



---


### setNormalTexture{#setNormalTexture}

| Name | Beschreibung |
| --- | --- |
| setNormalTexture(value) | Liest oder setzt die Textur der Normalenabbildung |

 **Result:**



---


### getSpecularGlossinessTexture{#getSpecularGlossinessTexture}

| Name | Beschreibung |
| --- | --- |
| getSpecularGlossinessTexture() | Liest oder setzt die Textur für die spekulare Farbe, der RGB‑Kanal speichert die spekulare Farbe und der A‑Kanal speichert den Glanzgrad. |

 **Result:**



---


### setSpecularGlossinessTexture{#setSpecularGlossinessTexture}

| Name | Beschreibung |
| --- | --- |
| setSpecularGlossinessTexture(value) | Liest oder setzt die Textur für die spekulare Farbe, der RGB‑Kanal speichert die spekulare Farbe und der A‑Kanal speichert den Glanzgrad. |

 **Result:**



---


### getGlossinessFactor{#getGlossinessFactor}

| Name | Beschreibung |
| --- | --- |
| getGlossinessFactor() | Liest oder setzt den Glanzgrad (Glätte) des Materials, 1 bedeutet vollkommen glatt und 0 bedeutet vollkommen rau, Standardwert ist 1, Bereich ist [0, 1]. |

 **Result:**



---


### setGlossinessFactor{#setGlossinessFactor}

| Name | Beschreibung |
| --- | --- |
| setGlossinessFactor(value) | Liest oder setzt den Glanzgrad (Glätte) des Materials, 1 bedeutet vollkommen glatt und 0 bedeutet vollkommen rau, Standardwert ist 1, Bereich ist [0, 1]. |

 **Result:**



---


### getSpecular{#getSpecular}

| Name | Beschreibung |
| --- | --- |
| getSpecular() | Liest oder setzt die spekulare Farbe des Materials, Standardwert ist (1, 1, 1). |

 **Result:**



---


### setSpecular{#setSpecular}

| Name | Beschreibung |
| --- | --- |
| setSpecular(value) | Liest oder setzt die spekulare Farbe des Materials, Standardwert ist (1, 1, 1). |

 **Result:**



---


### getDiffuseTexture{#getDiffuseTexture}

| Name | Beschreibung |
| --- | --- |
| getDiffuseTexture() | Liest oder setzt die Textur für diffuse |

 **Result:**



---


### setDiffuseTexture{#setDiffuseTexture}

| Name | Beschreibung |
| --- | --- |
| setDiffuseTexture(value) | Liest oder setzt die Textur für diffuse |

 **Result:**



---


### getDiffuse{#getDiffuse}

| Name | Beschreibung |
| --- | --- |
| getDiffuse() | Liest oder setzt die diffuse Farbe des Materials, Standardwert ist (1, 1, 1) |

 **Result:**



---


### setDiffuse{#setDiffuse}

| Name | Beschreibung |
| --- | --- |
| setDiffuse(value) | Liest oder setzt die diffuse Farbe des Materials, Standardwert ist (1, 1, 1) |

 **Result:**



---


### getEmissiveTexture{#getEmissiveTexture}

| Name | Beschreibung |
| --- | --- |
| getEmissiveTexture() | Liest oder setzt die Textur für emissiv |

 **Result:**



---


### setEmissiveTexture{#setEmissiveTexture}

| Name | Beschreibung |
| --- | --- |
| setEmissiveTexture(value) | Liest oder setzt die Textur für emissiv |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Name | Beschreibung |
| --- | --- |
| getEmissiveColor() | Liest oder setzt die emissive Farbe, Standardwert ist (0, 0, 0) |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Name | Beschreibung |
| --- | --- |
| setEmissiveColor(value) | Liest oder setzt die emissive Farbe, Standardwert ist (0, 0, 0) |

 **Result:**



---


### getName{#getName}

| Name | Beschreibung |
| --- | --- |
| getName() | Liest oder setzt den Namen. Der Name. |

 **Result:**



---


### setName{#setName}

| Name | Beschreibung |
| --- | --- |
| setName(value) | Liest oder setzt den Namen. Der Name. |

 **Result:**



---


### getProperties{#getProperties}

| Name | Beschreibung |
| --- | --- |
| getProperties() | Ruft die Sammlung aller Eigenschaften ab. |

 **Result:**



---


### getTexture{#getTexture}

| Name | Beschreibung |
| --- | --- |
| getTexture(slotName) | Liest die Textur aus dem angegebenen Slot, es kann der Name einer Material‑Eigenschaft oder ein Shader‑Parametername sein. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| slotName | String | Slot‑Name. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| Name | Beschreibung |
| --- | --- |
| setTexture(slotName, texture) | Setzt die Textur in den angegebenen Slot. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| slotName | String | Slot‑Name. |
| Textur | TextureBase | Textur. |

 **Result:**
TextureBase


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Formatiert das Objekt zu einem String. |

 **Result:**
String


---


### removeProperty{#removeProperty}

| Name | Beschreibung |
| --- | --- |
| removeProperty(property) | Entfernt eine dynamische Eigenschaft. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | Eigenschaft | Welche Eigenschaft entfernt werden soll |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Name | Beschreibung |
| --- | --- |
| removeProperty(property) | Entfernt die angegebene Eigenschaft, die durch den Namen identifiziert wird. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Name | Beschreibung |
| --- | --- |
| getProperty(property) | Rufe den Wert der angegebenen Eigenschaft ab. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |

 **Result:**
Objekt


---


### setProperty{#setProperty}

| Name | Beschreibung |
| --- | --- |
| setProperty(property, value) | Setzt den Wert der angegebenen Eigenschaft |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |
| value | Objekt | Der Wert der Eigenschaft |

 **Result:**
Objekt


---


### findProperty{#findProperty}

| Name | Beschreibung |
| --- | --- |
| findProperty(propertyName) | Findet die Eigenschaft. Es kann eine dynamische Eigenschaft (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) sein. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| propertyName | String | Eigenschaftsname. |

 **Result:**
Eigenschaft


---


### iterator{#iterator}

| Name | Beschreibung |
| --- | --- |
| iterator() | Für die interne Verwendung reserviert. |

 **Result:**
Eigenschaft


---



