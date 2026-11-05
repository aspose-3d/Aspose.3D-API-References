---
title: "Skelett"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/skeleton/
---
## Skeleton class

Das Skeleton wird hauptsächlich von CAD-Software verwendet, um dem Designer zu helfen, die Transformation der Skelettstruktur zu manipulieren; außerhalb von CAD-Software ist es in der Regel nutzlos.  Damit die Skeleton-Hierarchie in CAD-Software wie ein einzelnes Objekt wirkt, muss der oberste Skeleton-Knoten als Wurzel gekennzeichnet werden, indem der Typ auf SkeletonType.SKELETON gesetzt wird, und alle Kinder werden auf SkeletonType.BONE gesetzt.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der Klasse Skeleton. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(name) | Initialisiert eine neue Instanz der Klasse Skeleton. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name. |

 **Result:**



---


### getSize{#getSize}

| Name | Beschreibung |
| --- | --- |
| getSize() | Liest oder setzt die Größe des Gliedknotens, die in CAD-Software verwendet wird, um die Größe des Knochens darzustellen. |

 **Result:**



---


### setSize{#setSize}

| Name | Beschreibung |
| --- | --- |
| setSize(value) | Liest oder setzt die Größe des Gliedknotens, die in CAD-Software verwendet wird, um die Größe des Knochens darzustellen. |

 **Result:**



---


### getType{#getType}

| Name | Beschreibung |
| --- | --- |
| getType() | Liest oder setzt den Typ des Skeletts. Der Wert der Eigenschaft ist die Ganzzahlkonstante SkeletonType. Der Typ des Skeletts. |

 **Result:**



---


### setType{#setType}

| Name | Beschreibung |
| --- | --- |
| setType(value) | Liest oder setzt den Typ des Skeletts. Der Wert der Eigenschaft ist die Ganzzahlkonstante SkeletonType. Der Typ des Skeletts. |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Name | Beschreibung |
| --- | --- |
| getParentNodes() | Gibt alle übergeordneten Knoten zurück, ein Entity kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. Die Knoten. |

 **Result:**



---


### getExcluded{#getExcluded}

| Name | Beschreibung |
| --- | --- |
| getExcluded() | Liest oder setzt, ob dieses Entity beim Exportieren ausgeschlossen werden soll. |

 **Result:**



---


### setExcluded{#setExcluded}

| Name | Beschreibung |
| --- | --- |
| setExcluded(value) | Liest oder setzt, ob dieses Entity beim Exportieren ausgeschlossen werden soll. |

 **Result:**



---


### getParentNode{#getParentNode}

| Name | Beschreibung |
| --- | --- |
| getParentNode() | Liest oder setzt den ersten übergeordneten Knoten, wenn der erste übergeordnete Knoten gesetzt ist, wird dieses Entity von anderen übergeordneten Knoten getrennt. Der übergeordnete Knoten. |

 **Result:**



---


### setParentNode{#setParentNode}

| Name | Beschreibung |
| --- | --- |
| setParentNode(value) | Liest oder setzt den ersten übergeordneten Knoten, wenn der erste übergeordnete Knoten gesetzt ist, wird dieses Entity von anderen übergeordneten Knoten getrennt. Der übergeordnete Knoten. |

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


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Ruft die Bounding-Box der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem ab. |

 **Result:**



---


### getEntityRendererKey{#getEntityRendererKey}

| Name | Beschreibung |
| --- | --- |
| getEntityRendererKey() | Ruft den Schlüssel des im Renderer registrierten Entity-Renderers ab. |

 **Result:**
EntityRendererKey


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



