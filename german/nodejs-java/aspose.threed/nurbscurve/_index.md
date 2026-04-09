---
title: NurbsCurve
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

Eine NURBS-Kurve ist eine Kurve, die durch NURBS (Non-uniform rational basis spline) dargestellt wird,  Eine NURBS-Kurve wird durch ihre Ordnung, ein Satz gewichteter Geometry.ControlPoints und ein KnotVectors definiert  Die w-Komponente im Kontrollpunkt wird als Gewicht des Kontrollpunkts verwendet, unabhängig davon, ob es sich um CurveDimension.TWO_DIMENSIONAL oder CurveDimension.THREE_DIMENSIONAL handelt.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der NurbsCurve-Klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(name) | Initialisiert eine neue Instanz der NurbsCurve-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Name | Beschreibung |
| --- | --- |
| getControlPoints() | Ermittelt alle Kontrollpunkte |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| Name | Beschreibung |
| --- | --- |
| getMultiplicity() | Gibt die Multiplizität zurück. Die Multiplizität. |

 **Result:**



---


### getOrder{#getOrder}

| Name | Beschreibung |
| --- | --- |
| getOrder() | Liest oder setzt die Ordnung einer NURBS-Kurve, sie definiert die Anzahl der benachbarten Kontrollpunkte, die einen beliebigen Punkt auf der Kurve beeinflussen. Die Ordnung. |

 **Result:**



---


### setOrder{#setOrder}

| Name | Beschreibung |
| --- | --- |
| setOrder(value) | Liest oder setzt die Ordnung einer NURBS-Kurve, sie definiert die Anzahl der benachbarten Kontrollpunkte, die einen beliebigen Punkt auf der Kurve beeinflussen. Die Ordnung. |

 **Result:**



---


### getDimension{#getDimension}

| Name | Beschreibung |
| --- | --- |
| getDimension() | Liest oder setzt die Dimension der Kurve. Der Wert der Eigenschaft ist die Ganzzahlkonstante CurveDimension. Für eine CurveDimension.TWO_DIMENSIONAL-Kurve wird die z-Komponente im Kontrollpunkt nicht verwendet. |

 **Result:**



---


### setDimension{#setDimension}

| Name | Beschreibung |
| --- | --- |
| setDimension(value) | Liest oder setzt die Dimension der Kurve. Der Wert der Eigenschaft ist die Ganzzahlkonstante CurveDimension. Für eine CurveDimension.TWO_DIMENSIONAL-Kurve wird die z-Komponente im Kontrollpunkt nicht verwendet. |

 **Result:**



---


### getCurveType{#getCurveType}

| Name | Beschreibung |
| --- | --- |
| getCurveType() | Liest oder setzt den Typ der Kurve. Der Wert der Eigenschaft ist die Ganzzahlkonstante NurbsType. Der Typ der Kurve. |

 **Result:**



---


### setCurveType{#setCurveType}

| Name | Beschreibung |
| --- | --- |
| setCurveType(value) | Liest oder setzt den Typ der Kurve. Der Wert der Eigenschaft ist die Ganzzahlkonstante NurbsType. Der Typ der Kurve. |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| Name | Beschreibung |
| --- | --- |
| getKnotVectors() | Ruft den Knotenvektor ab, er ist eine Sequenz von Parameterwerten, die bestimmen, wo und wie die Kontrollpunkte die NURBS-Kurve beeinflussen. |

 **Result:**



---


### getRational{#getRational}

| Name | Beschreibung |
| --- | --- |
| getRational() | Liest oder setzt, ob sie rational ist; dieser Wert gibt an, ob diese NurbsCurve ein rationaler Spline oder ein nicht-rationaler Spline ist. Ein nicht-rationaler B-Spline ist ein Spezialfall von rationalen B-Splines. true, wenn es ein rationaler Spline ist; andernfalls ist false ein nicht-rationaler Spline. |

 **Result:**



---


### setRational{#setRational}

| Name | Beschreibung |
| --- | --- |
| setRational(value) | Liest oder setzt, ob sie rational ist; dieser Wert gibt an, ob diese NurbsCurve ein rationaler Spline oder ein nicht-rationaler Spline ist. Ein nicht-rationaler B-Spline ist ein Spezialfall von rationalen B-Splines. true, wenn es ein rationaler Spline ist; andernfalls ist false ein nicht-rationaler Spline. |

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


### evaluate{#evaluate}

| Name | Beschreibung |
| --- | --- |
| evaluate(steps) | Evaluiert die NURBS-Kurve |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Schritte | Number | Die Auswertungsfrequenz zwischen zwei benachbarten Knoten, Standardwert ist 20 |

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
| u | Number | Die Position in der Kurve, zwischen 0 und 1 |

 **Result:**
Vector4


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



