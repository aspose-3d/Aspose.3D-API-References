---
title: "Klasse HShape"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Profiles.HShape Klasse. Das HShape liefert die definierenden Parameter einer H- oder I-Form"
type: docs
weight: 1730
url: /de/net/aspose.threed.profiles/hshape/
---
## HShape class

Das `HShape` liefert die definierenden Parameter einer 'H'- oder 'I'-Form.

```csharp
public class HShape : ParameterizedProfile
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HShape](hshape/)() | Konstruktor von `HShape` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BottomFlangeEdgeRadius](../../aspose.threed.profiles/hshape/bottomflangeedgeradius/) { get; set; } | Liest oder setzt den Radius der oberen Kanten der unteren Flansch. |
| [BottomFlangeFilletRadius](../../aspose.threed.profiles/hshape/bottomflangefilletradius/) { get; set; } | Liest oder setzt den Radius der Rundung zwischen dem Steg und dem unteren Flansch. |
| [BottomFlangeThickness](../../aspose.threed.profiles/hshape/bottomflangethickness/) { get; set; } | Liest oder setzt die Flanschdicke der H-Form. |
| [BottomFlangeWidth](../../aspose.threed.profiles/hshape/bottomflangewidth/) { get; set; } | Liest oder setzt die Ausdehnung der Breite. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [OverallDepth](../../aspose.threed.profiles/hshape/overalldepth/) { get; set; } | Liest oder setzt die Ausdehnung der Tiefe. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [TopFlangeEdgeRadius](../../aspose.threed.profiles/hshape/topflangeedgeradius/) { get; set; } | Liest oder setzt den Radius der unteren Kanten des oberen Flansches. |
| [TopFlangeFilletRadius](../../aspose.threed.profiles/hshape/topflangefilletradius/) { get; set; } | Liest oder setzt den Radius der Rundung zwischen dem Steg und dem oberen Flansch. |
| [TopFlangeThickness](../../aspose.threed.profiles/hshape/topflangethickness/) { get; set; } | Liest oder setzt die Dicke des oberen Flansches. |
| [TopFlangeWidth](../../aspose.threed.profiles/hshape/topflangewidth/) { get; set; } | Liest oder setzt die Breite des oberen Flansches. |
| [WebThickness](../../aspose.threed.profiles/hshape/webthickness/) { get; set; } | Liest oder setzt die Dicke des Stegs der H-Form. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| override [GetExtent](../../aspose.threed.profiles/hshape/getextent/)() | Ermittelt den Umfang in x- und y-Richtung. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


