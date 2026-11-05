---
title: "MorphTargetDeformer"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer bietet per-Vertex-Animation. MorphTargetDeformer organisiert alle Ziele über MorphTargetChannel, jeder Kanal kann mehrere Ziele organisieren. Ein häufiger Einsatz von MorphTargetDeformer ist das Anwenden von Gesichtsausdrücken auf einen Charakter. Weitere Details finden Sie unter https://en.wikipedia.org/wiki/Morph_target_animation


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(name) | Initialisiert eine neue Instanz der Klasse MorphTargetDeformer. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload() | Initialisiert eine neue Instanz der Klasse MorphTargetDeformer. |

 **Result:**



---


### getChannels{#getChannels}

| Name | Beschreibung |
| --- | --- |
| getChannels() | Liest alle Kanäle, die in diesem Deformer enthalten sind |

 **Result:**



---


### getOwner{#getOwner}

| Name | Beschreibung |
| --- | --- |
| getOwner() | Ermittelt die Geometrie, die diesen Deformer besitzt |

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



