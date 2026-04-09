---
title: KeyframeSequence
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

Die Sequenz von Schlüsselbildern beschreibt die Transformation eines abgetasteten Wertes über die Zeit.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(name) | Initialisiert eine neue Instanz der Klasse KeyframeSequence. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload() | Initialisiert eine neue Instanz der Klasse KeyframeSequence. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Name | Beschreibung |
| --- | --- |
| getBindPoint() | Gibt den Property-Bind-Punkt zurück, der diese Kurve besitzt |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| Name | Beschreibung |
| --- | --- |
| getKeyFrames() | Gibt die Schlüsselbilder dieser Kurve zurück. Die Schlüssel. |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| Name | Beschreibung |
| --- | --- |
| getPostBehavior() | Gibt das Post‑Verhalten zurück, das angibt, welchen abgetasteten Wert es nach dem letzten Keyframe haben soll. |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| Name | Beschreibung |
| --- | --- |
| getPreBehavior() | Gibt das Pre‑Verhalten zurück, das angibt, welchen abgetasteten Wert es vor dem ersten Keyframe haben soll. |

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


### add{#add}

| Name | Beschreibung |
| --- | --- |
| add(time, value) | Erstelle einen neuen Keyframe mit angegebenem Wert |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Zeit | Number | Zeitposition (gemessen in Sekunden) |
| Wert | Number | Der Wert an dieser Zeitposition |

 **Result:**



---


### add{#add}

| Name | Beschreibung |
| --- | --- |
| add(time, value, interpolation) | Erstelle einen neuen Keyframe mit angegebenem Wert |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Zeit | Number | Zeitposition (gemessen in Sekunden) |
| Wert | Number | Der Wert an dieser Zeitposition |
| Interpolation | Interpolation | Interpolation |

 **Result:**



---


### reset{#reset}

| Name | Beschreibung |
| --- | --- |
| reset() | Entfernt alle Keyframes und setzt das Post-/Pre‑Verhalten zurück. |

 **Result:**



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



