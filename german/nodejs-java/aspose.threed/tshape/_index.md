---
title: "TShape"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/tshape/
---
## TShape class

IFC-kompatible T‑Form, definiert durch Parameter.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Konstruktor von TShape |

 **Result:**



---


### getDepth{#getDepth}

| Name | Beschreibung |
| --- | --- |
| getDepth() | Liest oder setzt die Länge des Stegs. |

 **Result:**



---


### setDepth{#setDepth}

| Name | Beschreibung |
| --- | --- |
| setDepth(value) | Liest oder setzt die Länge des Stegs. |

 **Result:**



---


### getFlangeWidth{#getFlangeWidth}

| Name | Beschreibung |
| --- | --- |
| getFlangeWidth() | Liest oder setzt die Länge des Flansches. |

 **Result:**



---


### setFlangeWidth{#setFlangeWidth}

| Name | Beschreibung |
| --- | --- |
| setFlangeWidth(value) | Liest oder setzt die Länge des Flansches. |

 **Result:**



---


### getWebThickness{#getWebThickness}

| Name | Beschreibung |
| --- | --- |
| getWebThickness() | Liest oder setzt die Wanddicke des Stegs. |

 **Result:**



---


### setWebThickness{#setWebThickness}

| Name | Beschreibung |
| --- | --- |
| setWebThickness(value) | Liest oder setzt die Wanddicke des Stegs. |

 **Result:**



---


### getFlangeThickness{#getFlangeThickness}

| Name | Beschreibung |
| --- | --- |
| getFlangeThickness() | Liest oder setzt die Wanddicke des Flansches. |

 **Result:**



---


### setFlangeThickness{#setFlangeThickness}

| Name | Beschreibung |
| --- | --- |
| setFlangeThickness(value) | Liest oder setzt die Wanddicke des Flansches. |

 **Result:**



---


### getFilletRadius{#getFilletRadius}

| Name | Beschreibung |
| --- | --- |
| getFilletRadius() | Liest oder setzt den Radius der Rundung zwischen Steg und Flansch. |

 **Result:**



---


### setFilletRadius{#setFilletRadius}

| Name | Beschreibung |
| --- | --- |
| setFilletRadius(value) | Liest oder setzt den Radius der Rundung zwischen Steg und Flansch. |

 **Result:**



---


### getFlangeEdgeRadius{#getFlangeEdgeRadius}

| Name | Beschreibung |
| --- | --- |
| getFlangeEdgeRadius() | Liest oder setzt den Radius der Flanschkante. |

 **Result:**



---


### setFlangeEdgeRadius{#setFlangeEdgeRadius}

| Name | Beschreibung |
| --- | --- |
| setFlangeEdgeRadius(value) | Liest oder setzt den Radius der Flanschkante. |

 **Result:**



---


### getWebEdgeRadius{#getWebEdgeRadius}

| Name | Beschreibung |
| --- | --- |
| getWebEdgeRadius() | Liest oder setzt den Radius der Webkante. |

 **Result:**



---


### setWebEdgeRadius{#setWebEdgeRadius}

| Name | Beschreibung |
| --- | --- |
| setWebEdgeRadius(value) | Liest oder setzt den Radius der Webkante. |

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


### getExtent{#getExtent}

| Name | Beschreibung |
| --- | --- |
| getExtent() | Gibt die Ausdehnung in x- und y-Richtung zurück. |

 **Result:**
Vector2


---


### getEntityRendererKey{#getEntityRendererKey}

| Name | Beschreibung |
| --- | --- |
| getEntityRendererKey() | Ruft den Schlüssel des im Renderer registrierten Entity-Renderers ab. |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Ruft die Bounding-Box der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem ab. |

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



