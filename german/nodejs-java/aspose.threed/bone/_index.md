---
title: Knochen
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/bone/
---
## Bone class

Ein Bone definiert die Teilmenge der Kontrollpunkte der Geometrie und legt das Blend‑Gewicht für jeden Kontrollpunkt fest.  Das Bone‑Objekt kann nicht direkt verwendet werden; eine SkinDeformer‑Instanz wird verwendet, um die Geometrie zu verformen, und SkinDeformer enthält einen Satz von Bones, wobei jeder Bone mit einem Knoten verknüpft ist.  HINWEIS: Ein Kontrollpunkt einer Geometrie kann an mehr als einem Bone gebunden sein.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(name) | Initialisiert eine neue Instanz der Bone-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload() | Initialisiert eine neue Instanz der Bone-Klasse. |

 **Result:**



---


### getWeightCount{#getWeightCount}

| Name | Beschreibung |
| --- | --- |
| getWeightCount() | Liest die Anzahl der Gewichte, diese wird automatisch durch setWeight(int, double) erweitert. |

 **Result:**



---


### getTransform{#getTransform}

| Name | Beschreibung |
| --- | --- |
| getTransform() | Liest oder setzt die Transformationsmatrix des Knotens, der das Bone enthält. |

 **Result:**



---


### setTransform{#setTransform}

| Name | Beschreibung |
| --- | --- |
| setTransform(value) | Liest oder setzt die Transformationsmatrix des Knotens, der das Bone enthält. |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| Name | Beschreibung |
| --- | --- |
| getBoneTransform() | Liest oder setzt die Transformationsmatrix des Knochens. |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| Name | Beschreibung |
| --- | --- |
| setBoneTransform(value) | Liest oder setzt die Transformationsmatrix des Knochens. |

 **Result:**



---


### getNode{#getNode}

| Name | Beschreibung |
| --- | --- |
| getNode() | Liest oder setzt den Knoten. Der Knochenknoten ist der Knochen, an dem die Haut befestigt ist; der SkinDeformer verwendet den Knochenknoten, um die Verschiebung der Kontrollpunkte zu beeinflussen. Der Knochenknoten hat normalerweise ein Skeleton angehängt, aber das ist nicht erforderlich. Das angehängte Skeleton wird üblicherweise von DCC‑Software verwendet, um dem Benutzer das Skelett anzuzeigen. |

 **Result:**



---


### setNode{#setNode}

| Name | Beschreibung |
| --- | --- |
| setNode(value) | Liest oder setzt den Knoten. Der Knochenknoten ist der Knochen, an dem die Haut befestigt ist; der SkinDeformer verwendet den Knochenknoten, um die Verschiebung der Kontrollpunkte zu beeinflussen. Der Knochenknoten hat normalerweise ein Skeleton angehängt, aber das ist nicht erforderlich. Das angehängte Skeleton wird üblicherweise von DCC‑Software verwendet, um dem Benutzer das Skelett anzuzeigen. |

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
| get(index) |  |

 **Result:**



---


### set{#set}

| Name | Beschreibung |
| --- | --- |
| set(index, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| Name | Beschreibung |
| --- | --- |
| getWeight(index) | Liest das Gewicht für den Kontrollpunkt, der durch den Index angegeben ist |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Index | Number | Index des Kontrollpunkts |

 **Result:**
Number


---


### setWeight{#setWeight}

| Name | Beschreibung |
| --- | --- |
| setWeight(index, weight) | Setzt das Gewicht für den Kontrollpunkt, der durch den Index angegeben ist |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Index | Number | Index des Kontrollpunkts |
| Gewicht | Number | Neues Gewicht |

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



