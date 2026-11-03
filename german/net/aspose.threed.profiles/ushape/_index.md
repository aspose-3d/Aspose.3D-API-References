---
title: "Klasse UShape"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Profiles.UShape Klasse. IFC-kompatibles Ushape, das durch Parameter definiert ist."
type: docs
weight: 1840
url: /de/net/aspose.threed.profiles/ushape/
---
## UShape class

IFC kompatible U-förmige Form, definiert durch Parameter.

```csharp
public class UShape : ParameterizedProfile
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [UShape](ushape/)() | Konstruktor von `UShape` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Depth](../../aspose.threed.profiles/ushape/depth/) { get; set; } | Liest oder setzt die Länge des Stegs. |
| [EdgeRadius](../../aspose.threed.profiles/ushape/edgeradius/) { get; set; } | Liest oder setzt den Radius der Kante im Flanschrand. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [FilletRadius](../../aspose.threed.profiles/ushape/filletradius/) { get; set; } | Liest oder setzt den Radius der Rundung zwischen Flansch und Steg. |
| [FlangeThickness](../../aspose.threed.profiles/ushape/flangethickness/) { get; set; } | Liest oder setzt die Dicke des Flansches. |
| [FlangeWidth](../../aspose.threed.profiles/ushape/flangewidth/) { get; set; } | Liest oder setzt die Länge des Flansches. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [WebThickness](../../aspose.threed.profiles/ushape/webthickness/) { get; set; } | Liest oder setzt die Dicke des Stegs. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| override [GetExtent](../../aspose.threed.profiles/ushape/getextent/)() | Ermittelt den Umfang in x- und y-Richtung. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


