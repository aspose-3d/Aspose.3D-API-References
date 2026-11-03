---
title: "Klasse Pyramid"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.Pyramid class. Parametrisierte Pyramide"
type: docs
weight: 650
url: /de/net/aspose.threed.entities/pyramid/
---
## Pyramid class

Parametrisierte Pyramide.

```csharp
public class Pyramid : Primitive
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Pyramid](pyramid/#constructor)() | Erstelle eine neue Pyramideninstanz mit Standard‑Grundfläche (10, 10) und Standardhöhe (5) |
| [Pyramid](pyramid/#constructor_1)(double, double, double) | Erstelle eine neue Pyramideninstanz mit angegebener Grundfläche |
| [Pyramid](pyramid/#constructor_2)(double, double, double, double, double) | Erstelle eine neue Pyramideninstanz mit angegebener Grundfläche, Oberflächenfläche und Höhe. |
| [Pyramid](pyramid/#constructor_3)(string, double, double, double, double, double) | Erstelle eine neue Pyramideninstanz mit angegebener Grundfläche, Oberflächenfläche und Höhe. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BottomArea](../../aspose.threed.entities/pyramid/bottomarea/) { get; set; } | Fläche der unteren Kappe |
| [BottomOffset](../../aspose.threed.entities/pyramid/bottomoffset/) { get; set; } | Versatz für untere Scheitelpunkte |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten werfen kann |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [Height](../../aspose.threed.entities/pyramid/height/) { get; set; } | Höhe der Pyramide |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten empfangen kann. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [TopArea](../../aspose.threed.entities/pyramid/toparea/) { get; set; } | Fläche der oberen Kappe |

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
| override [ToMesh](../../aspose.threed.entities/pyramid/tomesh/)() | Konvertiere das aktuelle Objekt zu einem Mesh |

### Siehe auch

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


