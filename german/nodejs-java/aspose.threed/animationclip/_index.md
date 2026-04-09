---
title: AnimationClip
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

Der Animationsclip ist eine Sammlung von Animationen.  Die Szene kann einen oder mehrere Animationsclips haben.


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
| Name | String | Name |

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
| getScene() | Liefert die Szene, zu der dieses Objekt gehört |

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


### createAnimationNode{#createAnimationNode}

| Name | Beschreibung |
| --- | --- |
| createAnimationNode(nodeName) | Eine Kurzschreibweise-Funktion zum Erstellen und Registrieren des Animationsknotens im aktuellen Clip. |

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



