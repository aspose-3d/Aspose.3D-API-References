---
title: "Klasse TShape"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Profiles.TShape Klasse. IFC-kompatible Tshape definiert durch Parameter"
type: docs
weight: 1810
url: /de/net/aspose.threed.profiles/tshape/
---
## TShape class

IFC kompatible T-förmige Form, definiert durch Parameter.

```csharp
public class TShape : ParameterizedProfile
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TShape](tshape/)() | Konstruktor von `TShape` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Depth](../../aspose.threed.profiles/tshape/depth/) { get; set; } | Liest oder setzt die Länge des Stegs. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [FilletRadius](../../aspose.threed.profiles/tshape/filletradius/) { get; set; } | Liest oder setzt den Radius der Rundung zwischen Steg und Flansch. |
| [FlangeEdgeRadius](../../aspose.threed.profiles/tshape/flangeedgeradius/) { get; set; } | Liest oder setzt den Radius der Flanschkante. |
| [FlangeThickness](../../aspose.threed.profiles/tshape/flangethickness/) { get; set; } | Liest oder setzt die Wandstärke des Flansches. |
| [FlangeWidth](../../aspose.threed.profiles/tshape/flangewidth/) { get; set; } | Liest oder setzt die Länge des Flansches. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [WebEdgeRadius](../../aspose.threed.profiles/tshape/webedgeradius/) { get; set; } | Liest oder setzt den Radius der Stegkante. |
| [WebThickness](../../aspose.threed.profiles/tshape/webthickness/) { get; set; } | Liest oder setzt die Wandstärke des Stegs. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| override [GetExtent](../../aspose.threed.profiles/tshape/getextent/)() | Ermittelt den Umfang in x- und y-Richtung. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


