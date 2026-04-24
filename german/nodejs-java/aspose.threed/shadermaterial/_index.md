---
title: ShaderMaterial
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/shadermaterial/
---
## ShaderMaterial class

Ein Shader-Material ermöglicht es, das Material durch eine externe Rendering-Engine oder Shadersprache zu beschreiben.  ShaderMaterial verwendet ShaderTechnique, um die konkreten Renderdetails zu beschreiben, und die am besten geeignete wird je nach Ziel-Rendering-Plattform verwendet.  Beispielsweise kann Ihre ShaderMaterial-Instanz zwei Techniken haben, eine definiert durch HLSL und eine andere durch GLSL.  Auf Nicht‑Windows‑Plattformen sollte GLSL anstelle von HLSL verwendet werden.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der Klasse ShaderMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(name) | Initialisiert eine neue Instanz der Klasse ShaderMaterial. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name |

 **Result:**



---


### getTechniques{#getTechniques}

| Name | Beschreibung |
| --- | --- |
| getTechniques() | Ermittelt alle verfügbaren Techniken, die in diesem Material definiert sind. |

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



