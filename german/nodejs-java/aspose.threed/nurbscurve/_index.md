---
title: "NurbsCurve"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

NURBS-Kurve ist eine Kurve, die durch NURBS (Non-uniform rational basis spline) dargestellt wird,  Eine NURBS-Kurve wird durch ihre Ordnung, eine Menge gewichteter Geometry.ControlPoints und KnotVectors definiert.  Die w-Komponente im Kontrollpunkt wird als Gewicht des Kontrollpunkts verwendet, unabhängig davon, ob es sich um CurveDimension.TWO_DIMENSIONAL oder CurveDimension.THREE_DIMENSIONAL handelt.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der Klasse NurbsCurve. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(name) | Initialisiert eine neue Instanz der Klasse NurbsCurve. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Name | Beschreibung |
| --- | --- |
| getControlPoints() | Liest alle Kontrollpunkte |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| Name | Beschreibung |
| --- | --- |
| getMultiplicity() | Ermittelt die Multiplizität. Die Multiplizität. |

 **Result:**



---


### getOrder{#getOrder}

| Name | Beschreibung |
| --- | --- |
| getOrder() | Ermittelt oder setzt die Ordnung einer NURBS-Kurve, sie definiert die Anzahl benachbarter Kontrollpunkte, die einen beliebigen Punkt auf der Kurve beeinflussen. Die Ordnung. |

 **Result:**



---


### setOrder{#setOrder}

| Name | Beschreibung |
| --- | --- |
| setOrder(value) | Ermittelt oder setzt die Ordnung einer NURBS-Kurve, sie definiert die Anzahl benachbarter Kontrollpunkte, die einen beliebigen Punkt auf der Kurve beeinflussen. Die Ordnung. |

 **Result:**



---


### getDimension{#getDimension}

| Name | Beschreibung |
| --- | --- |
| getDimension() | Ermittelt oder setzt die Dimension der Kurve. Der Wert der Eigenschaft ist die Ganzzahlkonstante CurveDimension. Für eine CurveDimension.TWO_DIMENSIONAL-Kurve wird die z-Komponente im Kontrollpunkt nicht verwendet. |

 **Result:**



---


### setDimension{#setDimension}

| Name | Beschreibung |
| --- | --- |
| setDimension(value) | Ermittelt oder setzt die Dimension der Kurve. Der Wert der Eigenschaft ist die Ganzzahlkonstante CurveDimension. Für eine CurveDimension.TWO_DIMENSIONAL-Kurve wird die z-Komponente im Kontrollpunkt nicht verwendet. |

 **Result:**



---


### getCurveType{#getCurveType}

| Name | Beschreibung |
| --- | --- |
| getCurveType() | Ermittelt oder setzt den Typ der Kurve. Der Wert der Eigenschaft ist die Ganzzahlkonstante NurbsType. Der Typ der Kurve. |

 **Result:**



---


### setCurveType{#setCurveType}

| Name | Beschreibung |
| --- | --- |
| setCurveType(value) | Ermittelt oder setzt den Typ der Kurve. Der Wert der Eigenschaft ist die Ganzzahlkonstante NurbsType. Der Typ der Kurve. |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| Name | Beschreibung |
| --- | --- |
| getKnotVectors() | Ermittelt den Knotenvector, er ist eine Sequenz von Parameterwerten, die bestimmt, wo und wie die Kontrollpunkte die NURBS-Kurve beeinflussen. |

 **Result:**



---


### getRational{#getRational}

| Name | Beschreibung |
| --- | --- |
| getRational() | Liest oder setzt, ob es rational ist, dieser Wert gibt an, ob diese NurbsCurve ein rationaler Spline oder ein nicht-rationaler Spline ist. Nicht-rationaler B-spline ist ein Spezialfall von rationalen B-splines. true, wenn es ein rationaler Spline ist; andernfalls, false, wenn es ein nicht-rationaler Spline ist. |

 **Result:**



---


### setRational{#setRational}

| Name | Beschreibung |
| --- | --- |
| setRational(value) | Liest oder setzt, ob es rational ist, dieser Wert gibt an, ob diese NurbsCurve ein rationaler Spline oder ein nicht-rationaler Spline ist. Nicht-rationaler B-spline ist ein Spezialfall von rationalen B-splines. true, wenn es ein rationaler Spline ist; andernfalls, false, wenn es ein nicht-rationaler Spline ist. |

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


### evaluate{#evaluate}

| Name | Beschreibung |
| --- | --- |
| evaluate(steps) | Evaluiert die NURBS-Kurve |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Schritte | Zahl | Die Evaluierungsfrequenz zwischen zwei benachbarten Knoten, Standardwert ist 20 |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| Name | Beschreibung |
| --- | --- |
| evaluateAt(u) | Evaluiert den Punkt der Kurve an der angegebenen Position |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| u | Zahl | Die Position in der Kurve, zwischen 0 und 1 |

 **Result:**
Vector4


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



