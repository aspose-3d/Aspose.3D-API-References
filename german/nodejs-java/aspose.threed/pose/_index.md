---
title: "Pose"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/pose/
---
## Pose class

Die Pose wird verwendet, um die Transformationsmatrix zu speichern, wenn die Geometrie geskinnt ist.  Die Pose ist ein Satz von BonePose, wobei jeder BonePose die konkreten Transformationsinformationen des Knotenpunkts speichert.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(name) | Initialisiert eine neue Instanz der Pose-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload() | Initialisiert eine neue Instanz der Pose-Klasse. |

 **Result:**



---


### getPoseType{#getPoseType}

| Name | Beschreibung |
| --- | --- |
| getPoseType() | Liest oder setzt den Typ der Pose. Der Wert der Eigenschaft ist die Ganzzahlkonstante PoseType. Der Typ der Pose. |

 **Result:**



---


### setPoseType{#setPoseType}

| Name | Beschreibung |
| --- | --- |
| setPoseType(value) | Liest oder setzt den Typ der Pose. Der Wert der Eigenschaft ist die Ganzzahlkonstante PoseType. Der Typ der Pose. |

 **Result:**



---


### getBonePoses{#getBonePoses}

| Name | Beschreibung |
| --- | --- |
| getBonePoses() | Liest alle BonePose. Die Knoten. |

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


### addBonePose{#addBonePose}

| Name | Beschreibung |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | Speichert die Pose-Transformationsmatrix für den angegebenen Knochenknoten. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Knoten | Knoten | Knochenknoten. |
| Matrix | Matrix4 | Transformationsmatrix. |
| localMatrix | boolean | Wenn festgelegt auf |

 **Result:**



---


### addBonePose{#addBonePose}

| Name | Beschreibung |
| --- | --- |
| addBonePose(node, matrix) | Speichert die Pose-Transformationsmatrix für den angegebenen Knochenknoten. Die globale Transformationsmatrix wird impliziert. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Knoten | Knoten | Knochenknoten. |
| Matrix | Matrix4 | Transformationsmatrix. |

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



