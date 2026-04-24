---
title: LinearExtrusion
second_title: Aspose.3D für Node.js via Java API-Referenz
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
| getCenter() | Wenn dieser Wert false ist, ist der Z‑Bereich der linearen Extrusion von 0 bis Höhe, andernfalls ist der Bereich von -Höhe/2 bis Höhe/2. |

 **Result:**



---


### setCenter{#setCenter}

| Name | Beschreibung |
| --- | --- |
| setCenter(value) | Wenn dieser Wert false ist, ist der Z‑Bereich der linearen Extrusion von 0 bis Höhe, andernfalls ist der Bereich von -Höhe/2 bis Höhe/2. |

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
| getTwist() | Die Anzahl der Grad, um die die Form extrudiert wird. |

 **Result:**



---


### setTwist{#setTwist}

| Name | Beschreibung |
| --- | --- |
| setTwist(value) | Die Anzahl der Grad, um die die Form extrudiert wird. |

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


### toMesh{#toMesh}

| Name | Beschreibung |
| --- | --- |
| toMesh() | Konvertiere die Extrusion zu einem Mesh. |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Liefert die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |

 **Result:**
Mesh


---


### getEntityRendererKey{#getEntityRendererKey}

| Name | Beschreibung |
| --- | --- |
| getEntityRendererKey() | Liefert den Schlüssel des Entitäts-Renderers, der im Renderer registriert ist |

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



