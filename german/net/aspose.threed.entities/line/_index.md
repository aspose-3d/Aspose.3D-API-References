---
title: "Klasse Line"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.Line Klasse. Eine Polylinie ist ein Pfad, der durch eine Menge von Punkten mit ControlPoints definiert wird und durch Segments verbunden ist, was bedeutet, dass sie auch eine Menge verbundener Liniensegmente sein kann. Die Linie ist normalerweise ein lineares Objekt, was bedeutet, dass sie nicht verwendet werden kann, um eine Kurve darzustellen; um eine Kurve darzustellen, wird NurbsCurve verwendet."
type: docs
weight: 480
url: /de/net/aspose.threed.entities/line/
---
## Line class

Eine Polylinie ist ein Pfad, der durch eine Menge von Punkten mit [`ControlPoints`](../geometry/controlpoints/) definiert wird und durch [`Segments`](./segments/) verbunden ist, was bedeutet, dass sie auch eine Menge verbundener Liniensegmente sein kann. Die Linie ist normalerweise ein lineares Objekt, was bedeutet, dass sie nicht verwendet werden kann, um eine Kurve darzustellen; um eine Kurve darzustellen, wird [`NurbsCurve`](../nurbscurve/) verwendet.

```csharp
public class Line : Curve
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Line](line/#constructor)() | Initialisiert eine neue Instanz der `Line` Klasse. |
| [Line](line/#constructor_1)(string) | Initialisiert eine neue Instanz der `Line` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Liest oder setzt die Farbe der Linie, Standardwert ist weiß(1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/line/controlpoints/) { get; } | Liest alle Kontrollpunkte |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Segments](../../aspose.threed.entities/line/segments/) { get; } | Gibt die Segmente der Linie zurück. |
| [Visible](../../aspose.threed.entities/line/visible/) { get; set; } | Liest oder setzt, ob die Geometrie sichtbar ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromPoints](../../aspose.threed.entities/line/frompoints/)(params Vector3[]) | Erstellt eine `Line` Instanz aus einer Menge von Punkten. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [MakeDefaultIndices](../../aspose.threed.entities/line/makedefaultindices/)() | Erzeuge die Sequenz 0,1,2,3....[`ControlPoints`](../geometry/controlpoints/).Length-1 zu [`Segments`](./segments/), damit die ControlPoints als einzelne Linie verwendet werden können. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


