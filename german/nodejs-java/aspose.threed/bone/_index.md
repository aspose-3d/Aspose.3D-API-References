---
title: "Knochen"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/bone/
---
## Bone class

Ein Bone definiert die Teilmenge der Kontrollpunkte einer Geometrie und legt das Blend‑Weight für jeden Kontrollpunkt fest.  Das Bone‑Objekt kann nicht direkt verwendet werden; eine SkinDeformer‑Instanz wird zum Verformen der Geometrie eingesetzt, und SkinDeformer enthält eine Menge von Bones, wobei jeder Bone mit einem Knoten verknüpft ist.  HINWEIS: Ein Kontrollpunkt einer Geometrie kann an mehr als einem Bone gebunden sein.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(name) | Initialisiert eine neue Instanz der Klasse Bone. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload() | Initialisiert eine neue Instanz der Klasse Bone. |

 **Result:**



---


### getWeightCount{#getWeightCount}

| Name | Beschreibung |
| --- | --- |
| getWeightCount() | Gibt die Anzahl der Gewichte zurück, diese wird automatisch durch setWeight(int, double) erweitert. |

 **Result:**



---


### getTransform{#getTransform}

| Name | Beschreibung |
| --- | --- |
| getTransform() | Liest oder setzt die Transformationsmatrix des Knotens, der den Knochen enthält. |

 **Result:**



---


### setTransform{#setTransform}

| Name | Beschreibung |
| --- | --- |
| setTransform(value) | Liest oder setzt die Transformationsmatrix des Knotens, der den Knochen enthält. |

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
| getNode() | Liest oder setzt den Knoten. Der bone node ist der Knochen, an dem das Skin befestigt ist; der SkinDeformer verwendet den bone node, um die Verschiebung der Kontrollpunkte zu beeinflussen. Der bone node hat normalerweise ein Skeleton angehängt, aber das ist nicht erforderlich. Das angehängte Skeleton wird üblicherweise von DCC-Software verwendet, um dem Benutzer das Skelett anzuzeigen. |

 **Result:**



---


### setNode{#setNode}

| Name | Beschreibung |
| --- | --- |
| setNode(value) | Liest oder setzt den Knoten. Der bone node ist der Knochen, an dem das Skin befestigt ist; der SkinDeformer verwendet den bone node, um die Verschiebung der Kontrollpunkte zu beeinflussen. Der bone node hat normalerweise ein Skeleton angehängt, aber das ist nicht erforderlich. Das angehängte Skeleton wird üblicherweise von DCC-Software verwendet, um dem Benutzer das Skelett anzuzeigen. |

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
| getWeight(index) | Liest das Gewicht für den Kontrollpunkt, der durch den Index angegeben ist. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| index | Zahl | Index des Kontrollpunkts |

 **Result:**
Zahl


---


### setWeight{#setWeight}

| Name | Beschreibung |
| --- | --- |
| setWeight(index, weight) | Setzt das Gewicht für den Kontrollpunkt, der durch den Index angegeben ist. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| index | Zahl | Index des Kontrollpunkts |
| Gewicht | Zahl | Neues Gewicht |

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



