---
title: "KeyframeSequence"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

Die Sequenz von Schlüsselbildern, sie beschreibt die Transformation eines abgetasteten Wertes über die Zeit.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(name) | Initialisiert eine neue Instanz der Klasse KeyframeSequence. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name |

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
| getBindPoint() | Ermittelt den Bindungspunkt der Eigenschaft, dem diese Kurve gehört |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| Name | Beschreibung |
| --- | --- |
| getKeyFrames() | Ermittelt die Schlüsselbilder dieser Kurve. Die Schlüssel. |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| Name | Beschreibung |
| --- | --- |
| getPostBehavior() | Ermittelt das Nachverhalten, das angibt, welchen Wert die Abtastung nach dem letzten Schlüsselbild haben soll. |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| Name | Beschreibung |
| --- | --- |
| getPreBehavior() | Ermittelt das Vorverhalten, das angibt, welchen Wert die Abtastung vor dem ersten Schlüsselbild haben soll. |

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


### add{#add}

| Name | Beschreibung |
| --- | --- |
| add(time, value) | Erstelle ein neues Schlüsselbild mit dem angegebenen Wert |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| time | Zahl | Zeitposition (gemessen in Sekunden) |
| value | Zahl | Der Wert an dieser Zeitposition |

 **Result:**



---


### add{#add}

| Name | Beschreibung |
| --- | --- |
| add(time, value, interpolation) | Erstelle ein neues Schlüsselbild mit dem angegebenen Wert |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| time | Zahl | Zeitposition (gemessen in Sekunden) |
| value | Zahl | Der Wert an dieser Zeitposition |
| Interpolation | Interpolation | Interpolation |

 **Result:**



---


### reset{#reset}

| Name | Beschreibung |
| --- | --- |
| reset() | Entfernt alle Keyframes und setzt das Post-/Pre-Verhalten zurück. |

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


### iterator{#iterator}

| Name | Beschreibung |
| --- | --- |
| iterator() | Für die interne Verwendung reserviert. |

 **Result:**
Eigenschaft


---



