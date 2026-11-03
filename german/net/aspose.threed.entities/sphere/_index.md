---
title: "Klasse Sphere"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.Sphere Klasse. Parametrisierte Kugel"
type: docs
weight: 730
url: /de/net/aspose.threed.entities/sphere/
---
## Sphere class

Parametrisierte Kugel.

```csharp
public class Sphere : Primitive
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Sphere](sphere/#constructor)() | Initialisiert eine neue Instanz von `Sphere` mit dem Standardradius 1. |
| [Sphere](sphere/#constructor_1)(double) | Initialisiert eine neue Instanz der `Sphere`-Klasse mit angegebenem Radius. |
| [Sphere](sphere/#constructor_2)(double, int, int) | Initialisiert eine neue Instanz der `Sphere`-Klasse mit angegebenem Radius, Breitensegmenten und Höhensegmenten. |
| [Sphere](sphere/#constructor_3)(string, double, int, int, double, double, double, double) | Initialisiert eine neue Instanz der `Sphere`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten werfen kann |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [HeightSegments](../../aspose.threed.entities/sphere/heightsegments/) { get; set; } | Liest oder setzt die Höhensegmente. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [PhiLength](../../aspose.threed.entities/sphere/philength/) { get; set; } | Liest oder setzt die Länge von phi. |
| [PhiStart](../../aspose.threed.entities/sphere/phistart/) { get; set; } | Liest oder setzt den phi-Start. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Radius](../../aspose.threed.entities/sphere/radius/) { get; set; } | Liest oder setzt den Radius der Kugel. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten empfangen kann. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [ThetaLength](../../aspose.threed.entities/sphere/thetalength/) { get; set; } | Liest oder setzt die Länge von theta. |
| [ThetaStart](../../aspose.threed.entities/sphere/thetastart/) { get; set; } | Liest oder setzt den Theta-Start. |
| [WidthSegments](../../aspose.threed.entities/sphere/widthsegments/) { get; set; } | Liest oder setzt die Breitensegmente. |

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
| override [ToMesh](../../aspose.threed.entities/sphere/tomesh/)() | Konvertiere das aktuelle Objekt zu einem Mesh |

### Siehe auch

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


