---
title: "PbrMaterial"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/pbrmaterial/
---
## PbrMaterial class

Material für physikalisch basiertes Rendering basierend auf Albedo-Farbe/Metallisch/Rauheit


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Erstelle eine Standard-PBR-Materialinstanz |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(albedo) | Erstelle ein Standard-PBR-Material mit angegebenem Albedo-Farbwert. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| albedo | Vector3 | Der Standard-Albedo-Farbwert |

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


### getSpecularTexture{#getSpecularTexture}

| Name | Beschreibung |
| --- | --- |
| getSpecularTexture() | Liest oder setzt die Textur für die spekulare Farbe |

 **Result:**



---


### setSpecularTexture{#setSpecularTexture}

| Name | Beschreibung |
| --- | --- |
| setSpecularTexture(value) | Liest oder setzt die Textur für die spekulare Farbe |

 **Result:**



---


### getAlbedoTexture{#getAlbedoTexture}

| Name | Beschreibung |
| --- | --- |
| getAlbedoTexture() | Liest oder setzt die Textur für Albedo |

 **Result:**



---


### setAlbedoTexture{#setAlbedoTexture}

| Name | Beschreibung |
| --- | --- |
| setAlbedoTexture(value) | Liest oder setzt die Textur für Albedo |

 **Result:**



---


### getAlbedo{#getAlbedo}

| Name | Beschreibung |
| --- | --- |
| getAlbedo() | Liest oder setzt die Grundfarbe des Materials |

 **Result:**



---


### setAlbedo{#setAlbedo}

| Name | Beschreibung |
| --- | --- |
| setAlbedo(value) | Liest oder setzt die Grundfarbe des Materials |

 **Result:**



---


### getOcclusionTexture{#getOcclusionTexture}

| Name | Beschreibung |
| --- | --- |
| getOcclusionTexture() | Liest oder setzt die Textur für die Umgebungsokklusion |

 **Result:**



---


### setOcclusionTexture{#setOcclusionTexture}

| Name | Beschreibung |
| --- | --- |
| setOcclusionTexture(value) | Liest oder setzt die Textur für die Umgebungsokklusion |

 **Result:**



---


### getOcclusionFactor{#getOcclusionFactor}

| Name | Beschreibung |
| --- | --- |
| getOcclusionFactor() | Liest oder setzt den Faktor der Umgebungsokklusion |

 **Result:**



---


### setOcclusionFactor{#setOcclusionFactor}

| Name | Beschreibung |
| --- | --- |
| setOcclusionFactor(value) | Liest oder setzt den Faktor der Umgebungsokklusion |

 **Result:**



---


### getMetallicFactor{#getMetallicFactor}

| Name | Beschreibung |
| --- | --- |
| getMetallicFactor() | Liest oder setzt den Metallanteil des Materials, ein Wert von 1 bedeutet, dass das Material ein Metall ist, und ein Wert von 0 bedeutet, dass das Material ein Dielektrikum ist. |

 **Result:**



---


### setMetallicFactor{#setMetallicFactor}

| Name | Beschreibung |
| --- | --- |
| setMetallicFactor(value) | Liest oder setzt den Metallanteil des Materials, ein Wert von 1 bedeutet, dass das Material ein Metall ist, und ein Wert von 0 bedeutet, dass das Material ein Dielektrikum ist. |

 **Result:**



---


### getRoughnessFactor{#getRoughnessFactor}

| Name | Beschreibung |
| --- | --- |
| getRoughnessFactor() | Liest oder setzt die Rauheit des Materials, ein Wert von 1 bedeutet, dass das Material völlig rau ist, und ein Wert von 0 bedeutet, dass das Material völlig glatt ist. |

 **Result:**



---


### setRoughnessFactor{#setRoughnessFactor}

| Name | Beschreibung |
| --- | --- |
| setRoughnessFactor(value) | Liest oder setzt die Rauheit des Materials, ein Wert von 1 bedeutet, dass das Material völlig rau ist, und ein Wert von 0 bedeutet, dass das Material völlig glatt ist. |

 **Result:**



---


### getMetallicRoughness{#getMetallicRoughness}

| Name | Beschreibung |
| --- | --- |
| getMetallicRoughness() | Liest oder setzt die Textur für Metallisch (im R-Kanal) und Rauheit (im G-Kanal) |

 **Result:**



---


### setMetallicRoughness{#setMetallicRoughness}

| Name | Beschreibung |
| --- | --- |
| setMetallicRoughness(value) | Liest oder setzt die Textur für Metallisch (im R-Kanal) und Rauheit (im G-Kanal) |

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
| getEmissiveColor() | Liest oder setzt die Emissionsfarbe |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Name | Beschreibung |
| --- | --- |
| setEmissiveColor(value) | Liest oder setzt die Emissionsfarbe |

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


### fromMaterial{#fromMaterial}

| Name | Beschreibung |
| --- | --- |
| fromMaterial(material) | Erlaubt die Umwandlung eines anderen Materials in PbrMaterial |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Materie | Material | null |

 **Result:**
PbrMaterial


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



