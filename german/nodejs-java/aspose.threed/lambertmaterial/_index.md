---
title: LambertMaterial
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/lambertmaterial/
---
## LambertMaterial class

Material für das Lambert-Shading-Modell


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der Klasse LambertMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(name) | Initialisiert eine neue Instanz der Klasse LambertMaterial. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Name | Beschreibung |
| --- | --- |
| getEmissiveColor() | Liest oder setzt die emittierende Farbe |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Name | Beschreibung |
| --- | --- |
| setEmissiveColor(value) | Liest oder setzt die emittierende Farbe |

 **Result:**



---


### getAmbientColor{#getAmbientColor}

| Name | Beschreibung |
| --- | --- |
| getAmbientColor() | Liest oder setzt die Umgebungsfarbe. Beispiel: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); Umgebung. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| Name | Beschreibung |
| --- | --- |
| setAmbientColor(value) | Liest oder setzt die Umgebungsfarbe. Beispiel: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); Umgebung. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| Name | Beschreibung |
| --- | --- |
| getDiffuseColor() | Liest oder setzt die diffuse Farbe. Beispiel: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); diffus. |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| Name | Beschreibung |
| --- | --- |
| setDiffuseColor(value) | Liest oder setzt die diffuse Farbe. Beispiel: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); diffus. |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| Name | Beschreibung |
| --- | --- |
| getTransparentColor() | Liest oder setzt die transparente Farbe. Beispiel: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); Farbe der Transparenz. |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| Name | Beschreibung |
| --- | --- |
| setTransparentColor(value) | Liest oder setzt die transparente Farbe. Beispiel: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); Farbe der Transparenz. |

 **Result:**



---


### getTransparency{#getTransparency}

| Name | Beschreibung |
| --- | --- |
| getTransparency() | Liest oder setzt den Transparenzfaktor. Der Faktor sollte zwischen 0 (0 %, vollständig undurchsichtig) und 1 (100 %, vollständig transparent) liegen. Jeder ungültige Faktorwert wird geklemmt. Beispiel: var mat = new LambertMaterial(); mat.Transparency = 0.3; Transparenzfaktor. |

 **Result:**



---


### setTransparency{#setTransparency}

| Name | Beschreibung |
| --- | --- |
| setTransparency(value) | Liest oder setzt den Transparenzfaktor. Der Faktor sollte zwischen 0 (0 %, vollständig undurchsichtig) und 1 (100 %, vollständig transparent) liegen. Jeder ungültige Faktorwert wird geklemmt. Beispiel: var mat = new LambertMaterial(); mat.Transparency = 0.3; Transparenzfaktor. |

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



