---
title: Pose
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/pose/
---
## Pose class

Die Pose wird verwendet, um die Transformationsmatrix zu speichern, wenn die Geometrie geskinnt ist.  Die Pose ist ein Satz von BonePose, wobei jeder BonePose die konkreten Transformationsinformationen des Knochen-Nodes speichert.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(name) | Initialisiert eine neue Instanz der Klasse Pose. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload() | Initialisiert eine neue Instanz der Klasse Pose. |

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


### addBonePose{#addBonePose}

| Name | Beschreibung |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | Speichert die Pose-Transformationsmatrix für den angegebenen Knochenknoten. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| node | Node | Knochenknoten. |
| Matrix | Matrix4 | Transformationsmatrix. |
| localMatrix | boolean | Wenn gesetzt auf |

 **Result:**



---


### addBonePose{#addBonePose}

| Name | Beschreibung |
| --- | --- |
| addBonePose(node, matrix) | Speichert die Pose-Transformationsmatrix für den angegebenen Knochenknoten. Die globale Transformationsmatrix wird impliziert. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| node | Node | Knochenknoten. |
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



