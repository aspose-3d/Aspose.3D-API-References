---
title: "Klasse Box"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.Box Klasse. Box"
type: docs
weight: 290
url: /de/net/aspose.threed.entities/box/
---
## Box class

Box.

```csharp
public class Box : Primitive
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Box](box/#constructor)() | Initialisiert eine neue Instanz der `Box` Klasse. |
| [Box](box/#constructor_1)(double, double, double) | Initialisiert eine neue Instanz der `Box` Klasse. |
| [Box](box/#constructor_2)(string, double, double, double, int, int, int) | Initialisiert eine neue Instanz der `Box` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten werfen kann |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [Height](../../aspose.threed.entities/box/height/) { get; set; } | Liest oder legt die Höhe der Box entlang der y-Achse fest. |
| [HeightSegments](../../aspose.threed.entities/box/heightsegments/) { get; set; } | liest oder legt die Höhensegmente fest. |
| [Length](../../aspose.threed.entities/box/length/) { get; set; } | Liest oder legt die Länge der Box entlang der z-Achse fest. |
| [LengthSegments](../../aspose.threed.entities/box/lengthsegments/) { get; set; } | Liest oder setzt die Längensegmente. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten empfangen kann. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Width](../../aspose.threed.entities/box/width/) { get; set; } | Liest oder legt die Breite der Box entlang der x-Achse fest. |
| [WidthSegments](../../aspose.threed.entities/box/widthsegments/) { get; set; } | Liest oder legt die Breitensegmente fest |

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
| override [ToMesh](../../aspose.threed.entities/box/tomesh/)() | Konvertiere das aktuelle Objekt zu einem Mesh |

### Siehe auch

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


