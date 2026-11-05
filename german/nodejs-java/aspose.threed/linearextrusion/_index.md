---
title: "LinearExtrusion"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/linearextrusion/
---
## LinearExtrusion class

Lineare Extrusion nimmt eine 2D-Form als Eingabe und erweitert die Form in die dritte Dimension.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Konstruktor der Instanz LinearExtrusion. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(shape, height) | Konstruktor der Instanz LinearExtrusion. |

 **Result:**



---


### getShape{#getShape}

| Name | Beschreibung |
| --- | --- |
| getShape() | Die Basisform, die extrudiert werden soll. |

 **Result:**



---


### setShape{#setShape}

| Name | Beschreibung |
| --- | --- |
| setShape(value) | Die Basisform, die extrudiert werden soll. |

 **Result:**



---


### getDirection{#getDirection}

| Name | Beschreibung |
| --- | --- |
| getDirection() | Die Richtung der Extrusion, Standardwert ist (0, 0, 1) |

 **Result:**



---


### setDirection{#setDirection}

| Name | Beschreibung |
| --- | --- |
| setDirection(value) | Die Richtung der Extrusion, Standardwert ist (0, 0, 1) |

 **Result:**



---


### getHeight{#getHeight}

| Name | Beschreibung |
| --- | --- |
| getHeight() | Die Höhe der extrudierten Geometrie, Standardwert ist 1.0 |

 **Result:**



---


### setHeight{#setHeight}

| Name | Beschreibung |
| --- | --- |
| setHeight(value) | Die Höhe der extrudierten Geometrie, Standardwert ist 1.0 |

 **Result:**



---


### getSlices{#getSlices}

| Name | Beschreibung |
| --- | --- |
| getSlices() | Die Scheiben der verdrehten extrudierten Geometrie, Standardwert ist 1. |

 **Result:**



---


### setSlices{#setSlices}

| Name | Beschreibung |
| --- | --- |
| setSlices(value) | Die Scheiben der verdrehten extrudierten Geometrie, Standardwert ist 1. |

 **Result:**



---


### getCenter{#getCenter}

| Name | Beschreibung |
| --- | --- |
| getCenter() | Wenn dieser Wert false ist, ist der lineare Extrusions-Z-Bereich von 0 bis Höhe, andernfalls ist der Bereich von -Höhe/2 bis Höhe/2. |

 **Result:**



---


### setCenter{#setCenter}

| Name | Beschreibung |
| --- | --- |
| setCenter(value) | Wenn dieser Wert false ist, ist der lineare Extrusions-Z-Bereich von 0 bis Höhe, andernfalls ist der Bereich von -Höhe/2 bis Höhe/2. |

 **Result:**



---


### getTwistOffset{#getTwistOffset}

| Name | Beschreibung |
| --- | --- |
| getTwistOffset() | Der Versatz, der beim Verdrehen verwendet wird, Standardwert ist (0, 0, 0). |

 **Result:**



---


### setTwistOffset{#setTwistOffset}

| Name | Beschreibung |
| --- | --- |
| setTwistOffset(value) | Der Versatz, der beim Verdrehen verwendet wird, Standardwert ist (0, 0, 0). |

 **Result:**



---


### getTwist{#getTwist}

| Name | Beschreibung |
| --- | --- |
| getTwist() | Die Anzahl der Grad, durch die die Form extrudiert wird. |

 **Result:**



---


### setTwist{#setTwist}

| Name | Beschreibung |
| --- | --- |
| setTwist(value) | Die Anzahl der Grad, durch die die Form extrudiert wird. |

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


### toMesh{#toMesh}

| Name | Beschreibung |
| --- | --- |
| toMesh() | Konvertiere die Extrusion in ein Mesh. |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Ruft die Bounding-Box der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem ab. |

 **Result:**
Mesh


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



