---
title: MorphTargetChannel
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

Ein MorphTargetChannel wird von MorphTargetDeformer verwendet, um die Zielgeometrien zu organisieren. Einige Dateiformate wie FBX unterstützen mehrere Kanäle parallel. Das Gewicht liegt zwischen 0 und 1,0, und das Standardgewicht für das Ziel ist 0,0;


## Properties

| Name | Beschreibung |
| --- | --- |
| DEFAULT_WEIGHT | Standardgewicht für Morph‑Ziel. |

## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(name) | Initialisiert eine neue Instanz der Klasse MorphTargetChannel. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload() | Initialisiert eine neue Instanz der Klasse MorphTargetChannel. |

 **Result:**



---


### getWeights{#getWeights}

| Name | Beschreibung |
| --- | --- |
| getWeights() | Liest die vollständigen Gewichtswerte der Zielgeometrien. Die vollständigen Gewichte. |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| Name | Beschreibung |
| --- | --- |
| getChannelWeight() | Liest oder setzt das Deformer‑Gewicht dieses Kanals. Das Gewicht liegt zwischen 0,0 und 1,0 |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| Name | Beschreibung |
| --- | --- |
| setChannelWeight(value) | Liest oder setzt das Deformer‑Gewicht dieses Kanals. Das Gewicht liegt zwischen 0,0 und 1,0 |

 **Result:**



---


### getTargets{#getTargets}

| Name | Beschreibung |
| --- | --- |
| getTargets() | Liefert alle Ziele, die mit dem Kanal verknüpft sind. |

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


### get{#get}

| Name | Beschreibung |
| --- | --- |
| get(target) |  |

 **Result:**



---


### set{#set}

| Name | Beschreibung |
| --- | --- |
| set(target, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| Name | Beschreibung |
| --- | --- |
| getWeight(target) | Liefert das Gewicht für das angegebene Ziel; gehört das Ziel nicht zu diesem Kanal, wird der Standardwert 0 zurückgegeben. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Ziel | Shape | null |

 **Result:**
Number


---


### setWeight{#setWeight}

| Name | Beschreibung |
| --- | --- |
| setWeight(target, weight) | Setzt das Gewicht für das angegebene Ziel, Standardwert ist 1, der Bereich sollte zwischen 0 und 1 liegen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Ziel | Shape | null |
| wiegen | Number | null |

 **Result:**
Number


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



