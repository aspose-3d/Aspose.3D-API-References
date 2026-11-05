---
title: "Line"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/line/
---
## Line class

Eine Polylinie ist ein Pfad, der durch eine Menge von Punkten mit Geometry.ControlPoints definiert wird und durch Segments verbunden ist, was bedeutet, dass es auch eine Menge verbundener Liniensegmente sein kann. Die Linie ist normalerweise ein lineares Objekt, was bedeutet, dass sie nicht zur Darstellung einer Kurve verwendet werden kann; um eine Kurve darzustellen, wird NurbsCurve verwendet.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der Klasse Line. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(name) | Initialisiert eine neue Instanz der Klasse Line. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Name | Beschreibung |
| --- | --- |
| getControlPoints() | Liest alle Kontrollpunkte |

 **Result:**



---


### getVisible{#getVisible}

| Name | Beschreibung |
| --- | --- |
| getVisible() | Liest oder setzt, ob die Geometrie sichtbar ist |

 **Result:**



---


### setVisible{#setVisible}

| Name | Beschreibung |
| --- | --- |
| setVisible(value) | Liest oder setzt, ob die Geometrie sichtbar ist |

 **Result:**



---


### getSegments{#getSegments}

| Name | Beschreibung |
| --- | --- |
| getSegments() | Liest die Segmente der Linie |

 **Result:**



---


### getColor{#getColor}

| Name | Beschreibung |
| --- | --- |
| getColor() | Liest oder setzt die Farbe der Linie, Standardwert ist weiß(1, 1, 1) |

 **Result:**



---


### setColor{#setColor}

| Name | Beschreibung |
| --- | --- |
| setColor(value) | Liest oder setzt die Farbe der Linie, Standardwert ist weiß(1, 1, 1) |

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


### fromPoints{#fromPoints}

| Name | Beschreibung |
| --- | --- |
| fromPoints(points) | Erstellt eine Line‑Instanz aus einer Menge von Punkten. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| point | Vector3[] | null |

 **Result:**
Line


---


### makeDefaultIndices{#makeDefaultIndices}

| Name | Beschreibung |
| --- | --- |
| makeDefaultIndices() | Erzeugt die Sequenz 0,1,2,3....Geometry.ControlPoints.Length-1 zu Segments, damit die ControlPoints als einzelne Linie verwendet werden können. |

 **Result:**
Line


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



