---
title: "MorphTargetChannel"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

Ein MorphTargetChannel wird von MorphTargetDeformer verwendet, um die Zielgeometrien zu organisieren. Einige Dateiformate wie FBX unterstützen mehrere Kanäle parallel. Das Gewicht liegt zwischen 0 und 1,0, und das Standardgewicht für das Ziel ist 0,0;


## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| DEFAULT_WEIGHT | Standardgewicht für Morph-Ziel. |

## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(name) | Initialisiert eine neue Instanz der Klasse MorphTargetChannel. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name. |

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
| getChannelWeight() | Liest oder setzt das Deformer-Gewicht dieses Kanals. Das Gewicht liegt zwischen 0,0 und 1,0. |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| Name | Beschreibung |
| --- | --- |
| setChannelWeight(value) | Liest oder setzt das Deformer-Gewicht dieses Kanals. Das Gewicht liegt zwischen 0,0 und 1,0. |

 **Result:**



---


### getTargets{#getTargets}

| Name | Beschreibung |
| --- | --- |
| getTargets() | Liest alle mit dem Kanal verbundenen Ziele. |

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
| getWeight(target) | Liest das Gewicht für das angegebene Ziel; wenn das Ziel nicht zu diesem Kanal gehört, wird der Standardwert 0 zurückgegeben. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| targe | Form | null |

 **Result:**
Zahl


---


### setWeight{#setWeight}

| Name | Beschreibung |
| --- | --- |
| setWeight(target, weight) | Setzt das Gewicht für das angegebene Ziel, der Standardwert ist 1, der Bereich sollte zwischen 0 und 1 liegen. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| targe | Form | null |
| wiegen | Zahl | null |

 **Result:**
Zahl


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



