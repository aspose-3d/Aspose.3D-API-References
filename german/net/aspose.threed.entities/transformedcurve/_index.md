---
title: "Klasse TransformedCurve"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.TransformedCurve class. Ein TransformedCurve gibt einer Kurve eine Platzierung mittels einer Transformationsmatrix. Dies ermöglicht eine Transformation innerhalb einer TrimmedCurve oder CompositeCurve."
type: docs
weight: 780
url: /de/net/aspose.threed.entities/transformedcurve/
---
## TransformedCurve class

Ein `TransformedCurve` gibt einer Kurve eine Platzierung mittels einer Transformationsmatrix. Dies ermöglicht eine Transformation innerhalb einer [`TrimmedCurve`](../trimmedcurve/) oder [`CompositeCurve`](../compositecurve/).

```csharp
public class TransformedCurve : Curve
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TransformedCurve](transformedcurve/#constructor)() | Der Konstruktor von `TransformedCurve` |
| [TransformedCurve](transformedcurve/#constructor_1)(Curve, Matrix4) | Der Konstruktor von `TransformedCurve` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/transformedcurve/basiscurve/) { get; set; } | Die Basis-Kurve. |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Liest oder setzt die Farbe der Linie, Standardwert ist weiß(1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [TransformMatrix](../../aspose.threed.entities/transformedcurve/transformmatrix/) { get; set; } | Die Transformationsmatrix. |

## Methoden

| Name | Beschreibung |
| --- | --- |
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


