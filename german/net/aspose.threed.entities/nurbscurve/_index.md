---
title: "Klasse NurbsCurve"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.NurbsCurve Klasse. Eine NURBS-Kurve ist eine Kurve, die durch einen NURBSNonuniform rational basis spline dargestellt wird. Eine NURBS-Kurve wird durch ihre Ordnung, eine Menge gewichteter ControlPoints und KnotVectors definiert. Die w-Komponente im ControlPoint wird als Gewicht des ControlPoints verwendet, unabhängig davon, ob es sich um eine TwoDimensional- oder ThreeDimensional-Darstellung handelt."
type: docs
weight: 520
url: /de/net/aspose.threed.entities/nurbscurve/
---
## NurbsCurve class

[NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [`Order`](./order/), a set of weighted [`ControlPoints`](../geometry/controlpoints/) and a [`KnotVectors`](./knotvectors/) The w component in control point is used as control point's weight, whatever it is a TwoDimensional or ThreeDimensional

```csharp
public class NurbsCurve : Curve
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [NurbsCurve](nurbscurve/#constructor)() | Initialisiert eine neue Instanz der `NurbsCurve`-Klasse. |
| [NurbsCurve](nurbscurve/#constructor_1)(string) | Initialisiert eine neue Instanz der `NurbsCurve`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Liest oder setzt die Farbe der Linie, Standardwert ist weiß(1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/nurbscurve/controlpoints/) { get; } | Liest alle Kontrollpunkte |
| [CurveType](../../aspose.threed.entities/nurbscurve/curvetype/) { get; set; } | Liest oder setzt den Typ der Kurve. |
| [Degree](../../aspose.threed.entities/nurbscurve/degree/) { get; set; } | Liest oder setzt den Grad einer NURBS-Kurve, der Grad wird definiert als Ordnung - 1. |
| [Dimension](../../aspose.threed.entities/nurbscurve/dimension/) { get; set; } | Liest oder setzt die Dimension der Kurve. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [KnotVectors](../../aspose.threed.entities/nurbscurve/knotvectors/) { get; } | Liest den Knotenvector, es ist eine Sequenz von Parameterwerten, die bestimmt, wo und wie die ControlPoints die NURBS-Kurve beeinflussen. |
| [Multiplicity](../../aspose.threed.entities/nurbscurve/multiplicity/) { get; } | Liest die Multiplizität. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Order](../../aspose.threed.entities/nurbscurve/order/) { get; set; } | Liest oder setzt die Ordnung einer NURBS-Kurve, sie definiert die Anzahl benachbarter ControlPoints, die einen beliebigen Punkt auf der Kurve beeinflussen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Rational](../../aspose.threed.entities/nurbscurve/rational/) { get; set; } | Liest oder setzt, ob sie rational ist, dieser Wert gibt an, ob diese `NurbsCurve` ein rationaler Spline oder ein nicht-rationaler Spline ist. Ein nicht-rationaler B-Spline ist ein Spezialfall von rationalen B-Splines. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Evaluate](../../aspose.threed.entities/nurbscurve/evaluate/)(int) | Bewerte die NURBS-Kurve |
| [EvaluateAt](../../aspose.threed.entities/nurbscurve/evaluateat/)(double) | Bewerte den Punkt der Kurve an der angegebenen Position |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


