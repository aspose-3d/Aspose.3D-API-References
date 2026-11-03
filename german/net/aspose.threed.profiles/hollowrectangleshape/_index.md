---
title: "Klasse HollowRectangleShape"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Profiles.HollowRectangleShape Klasse. IFC-kompatible hohle rechteckige Form mit sowohl inneren als auch äußeren abgerundeten Ecken"
type: docs
weight: 1750
url: /de/net/aspose.threed.profiles/hollowrectangleshape/
---
## HollowRectangleShape class

IFC kompatible hohle rechteckige Form mit sowohl inneren als auch äußeren abgerundeten Ecken.

```csharp
public class HollowRectangleShape : RectangleShape
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HollowRectangleShape](hollowrectangleshape/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [InnerFilletRadius](../../aspose.threed.profiles/hollowrectangleshape/innerfilletradius/) { get; set; } | Der innere Rundungsradius des inneren Rechtecks. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [RoundingRadius](../../aspose.threed.profiles/rectangleshape/roundingradius/) { get; set; } | Liest oder setzt den Radius der Kreisbögen aller vier Ecken, gemessen in Grad. Standardwert ist 0,0 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [WallThickness](../../aspose.threed.profiles/hollowrectangleshape/wallthickness/) { get; set; } | Die Dicke zwischen der Begrenzung des Rechtecks und dem inneren Loch |
| [XDim](../../aspose.threed.profiles/rectangleshape/xdim/) { get; set; } | Liest oder setzt den Umfang des Rechtecks in Richtung der x-Achse. Standardwert ist 2,0 |
| [YDim](../../aspose.threed.profiles/rectangleshape/ydim/) { get; set; } | Liest oder setzt den Umfang des Rechtecks in Richtung der y-Achse. Standardwert ist 2,0 |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| override [GetExtent](../../aspose.threed.profiles/rectangleshape/getextent/)() | Ermittelt den Umfang in x- und y-Richtung. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [RectangleShape](../rectangleshape/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


