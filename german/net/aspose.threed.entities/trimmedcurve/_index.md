---
title: "Klasse TrimmedCurve"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.TrimmedCurve Klasse. Eine begrenzte Kurve, die die Basis­kurve an beiden Enden abschneidet."
type: docs
weight: 810
url: /de/net/aspose.threed.entities/trimmedcurve/
---
## TrimmedCurve class

Eine begrenzte Kurve, die die Basis­kurve an beiden Enden abschneidet.

```csharp
public class TrimmedCurve : Curve
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TrimmedCurve](trimmedcurve/)() | Konstruktor von `TrimmedCurve` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/trimmedcurve/basiscurve/) { get; set; } | Die Basis­kurve, die beschnitten werden soll. |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Liest oder setzt die Farbe der Linie, Standardwert ist weiß(1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [First](../../aspose.threed.entities/trimmedcurve/first/) { get; set; } | Der erste Endpunkt zum Abschneiden, kann ein kartesischer Punkt oder ein reeller Parameter sein. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [SameDirection](../../aspose.threed.entities/trimmedcurve/samedirection/) { get; set; } | Liest oder setzt, ob das beschnittene Ergebnis dieselbe Richtung wie die Basis­kurve verwendet. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Second](../../aspose.threed.entities/trimmedcurve/second/) { get; set; } | Der zweite Endpunkt zum Trimmen kann ein kartesischer Punkt oder ein reeller Parameter sein. |

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


