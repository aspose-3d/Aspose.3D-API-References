---
title: "Klasse Plane"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.Plane Klasse. Parametrisierte Ebene"
type: docs
weight: 590
url: /de/net/aspose.threed.entities/plane/
---
## Plane class

Parametrisierte Ebene.

```csharp
public class Plane : Primitive
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Plane](plane/#constructor)() | Initialisiert eine neue Instanz des `Plane` mit Standardgröße 1x1. |
| [Plane](plane/#constructor_1)(double, double) | Initialisiert eine neue Instanz des `Plane`. |
| [Plane](plane/#constructor_2)(string, double, double, int, int) | Initialisiert eine neue Instanz des `Plane`. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten werfen kann |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [Length](../../aspose.threed.entities/plane/length/) { get; set; } | Liest oder setzt die Länge der Ebene. |
| [LengthSegments](../../aspose.threed.entities/plane/lengthsegments/) { get; set; } | Liest oder setzt die Längensegmente. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten empfangen kann. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Up](../../aspose.threed.entities/plane/up/) { get; set; } | Liest oder setzt den Aufwärtsvektor der Ebene, Standardwert ist (0, 1, 0), dies beeinflusst die Erzeugung der Ebene |
| [Width](../../aspose.threed.entities/plane/width/) { get; set; } | Liest oder setzt die Breite der Ebene. |
| [WidthSegments](../../aspose.threed.entities/plane/widthsegments/) { get; set; } | Liest oder setzt die Breitensegmente. |

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
| override [ToMesh](../../aspose.threed.entities/plane/tomesh/)() | Konvertiere das aktuelle Objekt zu einem Mesh |

### Siehe auch

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


