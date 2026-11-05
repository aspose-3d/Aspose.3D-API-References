---
title: "Material"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/material/
---
## Material class

Material definiert die für das visuelle Erscheinungsbild von Geometrie notwendigen Parameter. Aspose.3D bietet Shading-Modelle für LambertMaterial, PhongMaterial und ShaderMaterial  @hideconstructor


## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| MAP_SPECULAR | Wird in setTexture(java.lang.String, com.aspose.threed.TextureBase) verwendet, um eine spekulare Texturzuordnung zuzuweisen. |
| MAP_DIFFUSE | Wird in setTexture(java.lang.String, com.aspose.threed.TextureBase) verwendet, um eine diffuse Texturzuordnung zuzuweisen. |
| MAP_EMISSIVE | Wird in setTexture(java.lang.String, com.aspose.threed.TextureBase) verwendet, um eine emittierende Texturzuordnung zuzuweisen. |
| MAP_AMBIENT | Wird in setTexture(java.lang.String, com.aspose.threed.TextureBase) verwendet, um eine Umgebungs‑Texturzuordnung zuzuweisen. |
| MAP_NORMAL | Wird in setTexture(java.lang.String, com.aspose.threed.TextureBase) verwendet, um eine Normal‑Texturzuordnung zuzuweisen. |

## Methoden

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



