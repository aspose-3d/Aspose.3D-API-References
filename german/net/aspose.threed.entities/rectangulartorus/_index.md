---
title: "Klasse RectangularTorus"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.RectangularTorus Klasse. Parametrisierter rechteckiger Torus"
type: docs
weight: 660
url: /de/net/aspose.threed.entities/rectangulartorus/
---
## RectangularTorus class

Parametrisierter rechteckiger Torus.

```csharp
public class RectangularTorus : Primitive
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RectangularTorus](rectangulartorus/#constructor)() | Konstruktor von `RectangularTorus` |
| [RectangularTorus](rectangulartorus/#constructor_1)(string) | Konstruktor von `RectangularTorus` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AngleStart](../../aspose.threed.entities/rectangulartorus/anglestart/) { get; set; } | Der Startwinkel des Bogens, gemessen in Radiant. Standardwert ist 0 |
| [Arc](../../aspose.threed.entities/rectangulartorus/arc/) { get; set; } | Der Gesamtwinkel des Bogens, gemessen in Radiant. Standardwert ist PI |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten werfen kann |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [Height](../../aspose.threed.entities/rectangulartorus/height/) { get; set; } | Die Höhe des rechteckigen Torus. Der Standardwert ist 20 |
| [InnerRadius](../../aspose.threed.entities/rectangulartorus/innerradius/) { get; set; } | Der innere Radius des rechteckigen Torus Standardwert ist 17 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [OuterRadius](../../aspose.threed.entities/rectangulartorus/outerradius/) { get; set; } | Der äußere Radius des rechteckigen Torus Standardwert ist 20 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [RadialSegments](../../aspose.threed.entities/rectangulartorus/radialsegments/) { get; set; } | Die radialen Segmente, Standardwert ist 10 |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten empfangen kann. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |
| override [ToMesh](../../aspose.threed.entities/rectangulartorus/tomesh/)() | Konvertiere dieses Primitive zu [`Mesh`](../mesh/) |

### Siehe auch

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


