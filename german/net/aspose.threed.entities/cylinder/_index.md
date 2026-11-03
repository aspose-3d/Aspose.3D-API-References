---
title: "Klasse Cylinder"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.Cylinder Klasse. Parametrisierter Zylinder. Er kann auch verwendet werden, um den Kegel darzustellen, wenn einer der Werte radiusTop/radiusBottom null ist."
type: docs
weight: 360
url: /de/net/aspose.threed.entities/cylinder/
---
## Cylinder class

Parametrisierter Zylinder. Er kann auch verwendet werden, um den Kegel darzustellen, wenn einer der Werte radiusTop/radiusBottom null ist.

```csharp
public class Cylinder : Primitive
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Cylinder](cylinder/#constructor)() | Initialisiert eine neue Instanz der `Cylinder`-Klasse. |
| [Cylinder](cylinder/#constructor_1)(double, double) | Initialisiert eine neue Instanz der `Cylinder`-Klasse. |
| [Cylinder](cylinder/#constructor_2)(double, double, double) | Initialisiert eine neue Instanz der `Cylinder`-Klasse. |
| [Cylinder](cylinder/#constructor_3)(double, double, double, int, int, bool) | Initialisiert eine neue Instanz der `Cylinder`-Klasse. |
| [Cylinder](cylinder/#constructor_4)(string, double, double, double, int, int, bool, double, double) | Initialisiert eine neue Instanz der `Cylinder`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten werfen kann |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [GenerateFanCylinder](../../aspose.threed.entities/cylinder/generatefancylinder/) { get; set; } | Ruft ab oder legt fest, ob ein fan-style Zylinder erzeugt werden soll, wenn ThetaLength kleiner als 2*PI ist, andernfalls wird das Modell nicht geschnitten. |
| [Height](../../aspose.threed.entities/cylinder/height/) { get; set; } | Ruft die Höhe des Zylinders ab oder legt sie fest. |
| [HeightSegments](../../aspose.threed.entities/cylinder/heightsegments/) { get; set; } | Liest oder setzt die Höhensegmente. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [OffsetBottom](../../aspose.threed.entities/cylinder/offsetbottom/) { get; set; } | Ruft den Transformationsoffset der Scheitelpunkte der Unterseite ab oder legt ihn fest. |
| [OffsetTop](../../aspose.threed.entities/cylinder/offsettop/) { get; set; } | Ruft den Transformationsoffset der Scheitelpunkte der Oberseite ab oder legt ihn fest. |
| [OpenEnded](../../aspose.threed.entities/cylinder/openended/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der angibt, ob dieser `Cylinder` offen ist. Der Standardwert ist false. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [RadialSegments](../../aspose.threed.entities/cylinder/radialsegments/) { get; set; } | Ruft die radialen Segmente ab oder legt sie fest. |
| [RadiusBottom](../../aspose.threed.entities/cylinder/radiusbottom/) { get; set; } | Ruft den Radius der Unterkappe des Zylinders ab oder legt ihn fest. |
| [RadiusTop](../../aspose.threed.entities/cylinder/radiustop/) { get; set; } | Ruft den Radius der Oberkappe des Zylinders ab oder legt ihn fest. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten empfangen kann. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [ShearBottom](../../aspose.threed.entities/cylinder/shearbottom/) { get; set; } | Ruft die Schertransformation der Unterseite ab oder legt sie fest, der Vektor speichert den (x-Achse, z-Achse) Scherwert in Radiant, Standardwert ist (0, 0). |
| [ShearTop](../../aspose.threed.entities/cylinder/sheartop/) { get; set; } | Ruft die Schertransformation der Oberseite ab oder legt sie fest, der Vektor speichert den (x-Achse, z-Achse) Scherwert in Radiant, Standardwert ist (0, 0). |
| [ThetaLength](../../aspose.threed.entities/cylinder/thetalength/) { get; set; } | Ruft die Länge von Theta ab oder legt sie fest. Der Standardwert ist 2π. |
| [ThetaStart](../../aspose.threed.entities/cylinder/thetastart/) { get; set; } | Ruft den Startwert von Theta ab oder legt ihn fest. Der Standardwert ist 0. |

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
| override [ToMesh](../../aspose.threed.entities/cylinder/tomesh/)() | Konvertiere das aktuelle Objekt zu einem Mesh |

### Siehe auch

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


