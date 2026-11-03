---
title: "Klasse Torus"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.Torus Klasse. Parametrisierter Torus"
type: docs
weight: 770
url: /de/net/aspose.threed.entities/torus/
---
## Torus class

Parametrisierter Torus.

```csharp
public class Torus : Primitive
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Torus](torus/#constructor)() | Initialisiert eine neue Instanz der `Torus` Klasse. |
| [Torus](torus/#constructor_1)(double, double) | Initialisiert eine neue Instanz der `Torus` Klasse. |
| [Torus](torus/#constructor_2)(double, double, double) | Initialisiert eine neue Instanz der `Torus` Klasse. |
| [Torus](torus/#constructor_3)(string, double, double, int, int, double) | Initialisiert eine neue Instanz der `Torus` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Arc](../../aspose.threed.entities/torus/arc/) { get; set; } | Liest oder setzt den Bogen. |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten werfen kann |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [RadialSegments](../../aspose.threed.entities/torus/radialsegments/) { get; set; } | Ruft die radialen Segmente ab oder legt sie fest. |
| [Radius](../../aspose.threed.entities/torus/radius/) { get; set; } | Liest oder setzt den Radius des Torus. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten empfangen kann. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Tube](../../aspose.threed.entities/torus/tube/) { get; set; } | Liest oder setzt den Radius des Rohrs. |
| [TubularSegments](../../aspose.threed.entities/torus/tubularsegments/) { get; set; } | Liest oder setzt die Rohrsegmente. |

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
| override [ToMesh](../../aspose.threed.entities/torus/tomesh/)() | Konvertiere das aktuelle Objekt zu einem Mesh |

### Siehe auch

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


