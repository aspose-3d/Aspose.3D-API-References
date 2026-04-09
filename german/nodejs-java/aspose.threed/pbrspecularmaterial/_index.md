---
title: PbrSpecularMaterial
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Material für physikalisch basiertes Rendering basierend auf Diffusfarbe/Specular/Glanz


## Properties

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
| getTransparency() | Ruft den Transparenzfaktor ab oder legt ihn fest. Der Faktor sollte im Bereich zwischen 0 (0%, vollständig undurchsichtig) und 1 (100%, vollständig transparent) liegen. Jeder ungültige Faktorwert wird geklemmt. Der Transparenzfaktor. |

 **Result:**



---


### setTransparency{#setTransparency}

| Name | Beschreibung |
| --- | --- |
| setTransparency(value) | Ruft den Transparenzfaktor ab oder legt ihn fest. Der Faktor sollte im Bereich zwischen 0 (0%, vollständig undurchsichtig) und 1 (100%, vollständig transparent) liegen. Jeder ungültige Faktorwert wird geklemmt. Der Transparenzfaktor. |

 **Result:**



---


### getNormalTexture{#getNormalTexture}

| Name | Beschreibung |
| --- | --- |
| getNormalTexture() | Ruft die Textur des Normal Mapping ab oder legt sie fest |

 **Result:**



---


### setNormalTexture{#setNormalTexture}

| Name | Beschreibung |
| --- | --- |
| setNormalTexture(value) | Ruft die Textur des Normal Mapping ab oder legt sie fest |

 **Result:**



---


### getSpecularGlossinessTexture{#getSpecularGlossinessTexture}

| Name | Beschreibung |
| --- | --- |
| getSpecularGlossinessTexture() | Ruft die Textur für die spekulare Farbe ab oder legt sie fest, der Kanal RGB speichert die spekulare Farbe und der Kanal A speichert die Glanzlichkeit. |

 **Result:**



---


### setSpecularGlossinessTexture{#setSpecularGlossinessTexture}

| Name | Beschreibung |
| --- | --- |
| setSpecularGlossinessTexture(value) | Ruft die Textur für die spekulare Farbe ab oder legt sie fest, der Kanal RGB speichert die spekulare Farbe und der Kanal A speichert die Glanzlichkeit. |

 **Result:**



---


### getGlossinessFactor{#getGlossinessFactor}

| Name | Beschreibung |
| --- | --- |
| getGlossinessFactor() | Ruft die Glanzlichkeit (Glätte) des Materials ab oder legt sie fest, 1 bedeutet vollkommen glatt und 0 bedeutet vollkommen rau, Standardwert ist 1, Bereich ist [0, 1] |

 **Result:**



---


### setGlossinessFactor{#setGlossinessFactor}

| Name | Beschreibung |
| --- | --- |
| setGlossinessFactor(value) | Ruft die Glanzlichkeit (Glätte) des Materials ab oder legt sie fest, 1 bedeutet vollkommen glatt und 0 bedeutet vollkommen rau, Standardwert ist 1, Bereich ist [0, 1] |

 **Result:**



---


### getSpecular{#getSpecular}

| Name | Beschreibung |
| --- | --- |
| getSpecular() | Ruft die spekulare Farbe des Materials ab oder legt sie fest, Standardwert ist (1, 1, 1). |

 **Result:**



---


### setSpecular{#setSpecular}

| Name | Beschreibung |
| --- | --- |
| setSpecular(value) | Ruft die spekulare Farbe des Materials ab oder legt sie fest, Standardwert ist (1, 1, 1). |

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
| getEmissiveTexture() | Liest oder setzt die Textur für emissive |

 **Result:**



---


### setEmissiveTexture{#setEmissiveTexture}

| Name | Beschreibung |
| --- | --- |
| setEmissiveTexture(value) | Liest oder setzt die Textur für emissive |

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
| getName() | Gibt den Namen zurück oder legt ihn fest. Der Name. |

 **Result:**



---


### setName{#setName}

| Name | Beschreibung |
| --- | --- |
| setName(value) | Gibt den Namen zurück oder legt ihn fest. Der Name. |

 **Result:**



---


### getProperties{#getProperties}

| Name | Beschreibung |
| --- | --- |
| getProperties() | Liefert die Sammlung aller Eigenschaften. |

 **Result:**



---


### getTexture{#getTexture}

| Name | Beschreibung |
| --- | --- |
| getTexture(slotName) | Gibt die Textur aus dem angegebenen Slot zurück, sie kann der Name einer Materialeigenschaft oder ein Shader-Parametername sein. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| slotName | String | Slot-Name. |

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
| slotName | String | Slot-Name. |
| Textur | TextureBase | Textur. |

 **Result:**
TextureBase


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Formatiert das Objekt in einen String |

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
| Eigenschaft | Property | Welche Eigenschaft zu entfernen ist |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Name | Beschreibung |
| --- | --- |
| removeProperty(property) | Entferne die angegebene Eigenschaft, die durch ihren Namen identifiziert wird |

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
| getProperty(property) | Liefere den Wert der angegebenen Eigenschaft |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |

 **Result:**
Object


---


### setProperty{#setProperty}

| Name | Beschreibung |
| --- | --- |
| setProperty(property, value) | Setzt den Wert der angegebenen Eigenschaft |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |
| Wert | Object | Der Wert der Eigenschaft |

 **Result:**
Object


---


### findProperty{#findProperty}

| Name | Beschreibung |
| --- | --- |
| findProperty(propertyName) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| propertyName | String | Eigenschaftsname. |

 **Result:**
Property


---


### iterator{#iterator}

| Name | Beschreibung |
| --- | --- |
| iterator() | Für den internen Gebrauch reserviert. |

 **Result:**
Property


---



