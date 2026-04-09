---
title: TShape
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/tshape/
---
## TShape class

IFC‑kompatible T‑Form, definiert durch Parameter.


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
| getWebThickness() | Liest oder setzt die Wandstärke des Stegs. |

 **Result:**



---


### setWebThickness{#setWebThickness}

| Name | Beschreibung |
| --- | --- |
| setWebThickness(value) | Liest oder setzt die Wandstärke des Stegs. |

 **Result:**



---


### getFlangeThickness{#getFlangeThickness}

| Name | Beschreibung |
| --- | --- |
| getFlangeThickness() | Liest oder setzt die Wandstärke des Flansches. |

 **Result:**



---


### setFlangeThickness{#setFlangeThickness}

| Name | Beschreibung |
| --- | --- |
| setFlangeThickness(value) | Liest oder setzt die Wandstärke des Flansches. |

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
| getWebEdgeRadius() | Liest oder setzt den Radius der Stegkante. |

 **Result:**



---


### setWebEdgeRadius{#setWebEdgeRadius}

| Name | Beschreibung |
| --- | --- |
| setWebEdgeRadius(value) | Liest oder setzt den Radius der Stegkante. |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Name | Beschreibung |
| --- | --- |
| getParentNodes() | Gibt alle übergeordneten Knoten zurück, ein Entity kann für Geometrie-Instanziierung an mehrere übergeordnete Knoten angehängt werden. Die Knoten. |

 **Result:**



---


### getExcluded{#getExcluded}

| Name | Beschreibung |
| --- | --- |
| getExcluded() | Gibt an oder legt fest, ob dieses Entity beim Exportieren ausgeschlossen wird. |

 **Result:**



---


### setExcluded{#setExcluded}

| Name | Beschreibung |
| --- | --- |
| setExcluded(value) | Gibt an oder legt fest, ob dieses Entity beim Exportieren ausgeschlossen wird. |

 **Result:**



---


### getParentNode{#getParentNode}

| Name | Beschreibung |
| --- | --- |
| getParentNode() | Gibt den ersten übergeordneten Knoten zurück oder legt ihn fest; wenn der erste übergeordnete Knoten gesetzt wird, wird dieses Entity von anderen übergeordneten Knoten getrennt. Der übergeordnete Knoten. |

 **Result:**



---


### setParentNode{#setParentNode}

| Name | Beschreibung |
| --- | --- |
| setParentNode(value) | Gibt den ersten übergeordneten Knoten zurück oder legt ihn fest; wenn der erste übergeordnete Knoten gesetzt wird, wird dieses Entity von anderen übergeordneten Knoten getrennt. Der übergeordnete Knoten. |

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


### getExtent{#getExtent}

| Name | Beschreibung |
| --- | --- |
| getExtent() | Ermittelt die Ausdehnung in x- und y-Richtung. |

 **Result:**
Vector2


---


### getEntityRendererKey{#getEntityRendererKey}

| Name | Beschreibung |
| --- | --- |
| getEntityRendererKey() | Liefert den Schlüssel des Entitäts-Renderers, der im Renderer registriert ist |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Liefert die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |

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



