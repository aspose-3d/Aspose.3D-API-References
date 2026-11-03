---
title: "Klasse LShape"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Profiles.LShape Klasse. IFC-kompatibles Lshape-Profil, das durch Parameter definiert ist."
type: docs
weight: 1760
url: /de/net/aspose.threed.profiles/lshape/
---
## LShape class

IFC kompatibles L-förmiges Profil, das durch Parameter definiert ist.

```csharp
public class LShape : ParameterizedProfile
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LShape](lshape/)() | Konstruktor von `LShape` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Depth](../../aspose.threed.profiles/lshape/depth/) { get; set; } | Liest oder setzt die Tiefe des Profils. |
| [EdgeRadius](../../aspose.threed.profiles/lshape/edgeradius/) { get; set; } | Liest oder setzt den Radius der Kante. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [FilletRadius](../../aspose.threed.profiles/lshape/filletradius/) { get; set; } | Liest oder setzt den Radius der Rundung. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Thickness](../../aspose.threed.profiles/lshape/thickness/) { get; set; } | Liest oder setzt die Dicke der konstanten Wand. |
| [Width](../../aspose.threed.profiles/lshape/width/) { get; set; } | Liest oder setzt die Breite des Profils. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| override [GetExtent](../../aspose.threed.profiles/lshape/getextent/)() | Ermittelt den Umfang in x- und y-Richtung. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


