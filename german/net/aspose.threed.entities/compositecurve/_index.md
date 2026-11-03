---
title: "Klasse CompositeCurve"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.CompositeCurve Klasse. Ein CompositeCurve besteht aus mehreren Kurvensegmenten"
type: docs
weight: 320
url: /de/net/aspose.threed.entities/compositecurve/
---
## CompositeCurve class

Ein `CompositeCurve` besteht aus mehreren Kurvensegmenten.

```csharp
public class CompositeCurve : Curve
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CompositeCurve](compositecurve/)() | Konstruktor von `CompositeCurve` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Liest oder setzt die Farbe der Linie, Standardwert ist weiß(1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Segments](../../aspose.threed.entities/compositecurve/segments/) { get; } | Die Segmente der Kurve. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddSegment](../../aspose.threed.entities/compositecurve/addsegment/)(Curve, bool) | Füge ein neues Segment zur aktuellen Kurve hinzu. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [Segment](../../aspose.threed.entities/compositecurve.segment) |  |

### Siehe auch

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


