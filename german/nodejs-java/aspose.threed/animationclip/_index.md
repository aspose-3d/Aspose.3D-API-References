---
title: "AnimationClip"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

Der Animationsclip ist eine Sammlung von Animationen.  Die Szene kann einen oder mehrere Animationsclips enthalten.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der Klasse AnimationClip. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(name) | Initialisiert eine neue Instanz der Klasse AnimationClip. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name |

 **Result:**



---


### getAnimations{#getAnimations}

| Name | Beschreibung |
| --- | --- |
| getAnimations() | Liest die im Clip enthaltenen Animationen. Die Ebenen. |

 **Result:**



---


### getDescription{#getDescription}

| Name | Beschreibung |
| --- | --- |
| getDescription() | Liest oder setzt die Beschreibung dieses Animationsclips |

 **Result:**



---


### setDescription{#setDescription}

| Name | Beschreibung |
| --- | --- |
| setDescription(value) | Liest oder setzt die Beschreibung dieses Animationsclips |

 **Result:**



---


### getStart{#getStart}

| Name | Beschreibung |
| --- | --- |
| getStart() | Liest oder setzt die Zeit in Sekunden des Beginns des Clips. |

 **Result:**



---


### setStart{#setStart}

| Name | Beschreibung |
| --- | --- |
| setStart(value) | Liest oder setzt die Zeit in Sekunden des Beginns des Clips. |

 **Result:**



---


### getStop{#getStop}

| Name | Beschreibung |
| --- | --- |
| getStop() | Liest oder setzt die Zeit in Sekunden des Endes des Clips. |

 **Result:**



---


### setStop{#setStop}

| Name | Beschreibung |
| --- | --- |
| setStop(value) | Liest oder setzt die Zeit in Sekunden des Endes des Clips. |

 **Result:**



---


### getScene{#getScene}

| Name | Beschreibung |
| --- | --- |
| getScene() | Ruft die Szene ab, zu der dieses Objekt gehört |

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


### createAnimationNode{#createAnimationNode}

| Name | Beschreibung |
| --- | --- |
| createAnimationNode(nodeName) | Eine Kurzschreibweise‑Funktion, um den Animationsknoten im aktuellen Clip zu erstellen und zu registrieren. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| nodeName | String | Name des neuen Animationsknotens |

 **Result:**
AnimationNode


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



