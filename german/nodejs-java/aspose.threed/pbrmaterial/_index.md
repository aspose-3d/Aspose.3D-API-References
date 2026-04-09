---
title: PbrMaterial
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/pbrmaterial/
---
## PbrMaterial class

Material für physikalisch basiertes Rendering basierend auf Albedo‑Farbe/Metallisch/Rauheit


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
| albedo | Vector3 | Der Standardwert für die Albedo-Farbe |

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
| getEmissiveColor() | Liest oder setzt die emittierende Farbe |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Name | Beschreibung |
| --- | --- |
| setEmissiveColor(value) | Liest oder setzt die emittierende Farbe |

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


### fromMaterial{#fromMaterial}

| Name | Beschreibung |
| --- | --- |
| fromMaterial(material) | Erlaubt die Konvertierung anderer Materialien zu PbrMaterial |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Material | Material | null |

 **Result:**
PbrMaterial


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



