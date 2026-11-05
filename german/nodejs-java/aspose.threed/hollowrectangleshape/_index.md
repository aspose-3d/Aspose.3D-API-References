---
title: "HollowRectangleShape"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/hollowrectangleshape/
---
## HollowRectangleShape class

IFC-kompatible hohle rechteckige Form mit abgerundeten inneren/äußeren Ecken.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getWallThickness{#getWallThickness}

| Name | Beschreibung |
| --- | --- |
| getWallThickness() | Die Dicke zwischen der Begrenzung des Rechtecks und dem inneren Loch |

 **Result:**



---


### setWallThickness{#setWallThickness}

| Name | Beschreibung |
| --- | --- |
| setWallThickness(value) | Die Dicke zwischen der Begrenzung des Rechtecks und dem inneren Loch |

 **Result:**



---


### getInnerFilletRadius{#getInnerFilletRadius}

| Name | Beschreibung |
| --- | --- |
| getInnerFilletRadius() | Der innere Rundungsradius des inneren Rechtecks. |

 **Result:**



---


### setInnerFilletRadius{#setInnerFilletRadius}

| Name | Beschreibung |
| --- | --- |
| setInnerFilletRadius(value) | Der innere Rundungsradius des inneren Rechtecks. |

 **Result:**



---


### getRoundingRadius{#getRoundingRadius}

| Name | Beschreibung |
| --- | --- |
| getRoundingRadius() | Liest oder setzt den Radius der kreisförmigen Bögen aller vier Ecken, gemessen in Grad. Standardwert ist 0,0 |

 **Result:**



---


### setRoundingRadius{#setRoundingRadius}

| Name | Beschreibung |
| --- | --- |
| setRoundingRadius(value) | Liest oder setzt den Radius der kreisförmigen Bögen aller vier Ecken, gemessen in Grad. Standardwert ist 0,0 |

 **Result:**



---


### getXDim{#getXDim}

| Name | Beschreibung |
| --- | --- |
| getXDim() | Liest oder setzt die Ausdehnung des Rechtecks in Richtung der x-Achse. Standardwert ist 2,0 |

 **Result:**



---


### setXDim{#setXDim}

| Name | Beschreibung |
| --- | --- |
| setXDim(value) | Liest oder setzt die Ausdehnung des Rechtecks in Richtung der x-Achse. Standardwert ist 2,0 |

 **Result:**



---


### getYDim{#getYDim}

| Name | Beschreibung |
| --- | --- |
| getYDim() | Liest oder setzt die Ausdehnung des Rechtecks in Richtung der y-Achse. Standardwert ist 2,0 |

 **Result:**



---


### setYDim{#setYDim}

| Name | Beschreibung |
| --- | --- |
| setYDim(value) | Liest oder setzt die Ausdehnung des Rechtecks in Richtung der y-Achse. Standardwert ist 2,0 |

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



