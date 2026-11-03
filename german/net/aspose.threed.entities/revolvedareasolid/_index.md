---
title: "Klasse RevolvedAreaSolid"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.RevolvedAreaSolid Klasse. Diese Klasse stellt ein Festkörpermodell dar, indem ein Querschnitt, der durch ein Profil bereitgestellt wird, um eine Achse rotiert wird."
type: docs
weight: 680
url: /de/net/aspose.threed.entities/revolvedareasolid/
---
## RevolvedAreaSolid class

Diese Klasse stellt ein Festkörpermodell dar, indem ein Querschnitt, der durch ein Profil bereitgestellt wird, um eine Achse rotiert wird.

```csharp
public class RevolvedAreaSolid : Entity, IMeshConvertible
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RevolvedAreaSolid](revolvedareasolid/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AngleEnd](../../aspose.threed.entities/revolvedareasolid/angleend/) { get; set; } | Liest oder setzt den Endwinkel des Rotationsvorgangs, gemessen in Radiant, Standardwert ist pi. |
| [AngleStart](../../aspose.threed.entities/revolvedareasolid/anglestart/) { get; set; } | Liest oder setzt den Startwinkel des Rotationsvorgangs, gemessen in Radiant, Standardwert ist 0. |
| [Axis](../../aspose.threed.entities/revolvedareasolid/axis/) { get; set; } | Liest oder setzt die Achsenrichtung, Standardwert ist (0, 1, 0). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Origin](../../aspose.threed.entities/revolvedareasolid/origin/) { get; set; } | Liest oder setzt den Ursprungspunkt der Rotation, Standardwert ist (0, 0, 0). |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Shape](../../aspose.threed.entities/revolvedareasolid/shape/) { get; set; } | Liest oder setzt das Basisprofil, das für die Rotation verwendet wird. |

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
| [ToMesh](../../aspose.threed.entities/revolvedareasolid/tomesh/)() | Konvertiere das `RevolvedAreaSolid` in ein Mesh. |

## Beispiele

Der folgende Code zeigt, wie man RevolvedAreaSolid verwendet, um eine Form in ein Festkörpermodell zu rotieren.

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//Erstelle eine neue 3D‑Szene
Scene scene = new Scene();

// Initialisiere das Basisprofil, das rotiert werden soll
var profile = new RectangleShape()
{
    RoundingRadius = 0.3
};
//erstelle eine RevolvedAreaSolid‑Instanz
var revolved = new RevolvedAreaSolid()
{
  Shape = profile,
  Origin = new Vector3(1, 0, 0),
  AngleStart = 0,
  AngleEnd = Math.PI
};
scene.RootNode.CreateChildNode(revolved);

scene.Save("revolved.obj");
```

```csharp
//Erstelle eine neue 3D‑Szene
Scene scene = new Scene();

// Initialisiere das Basisprofil, das extrudiert werden soll
var profile = new RectangleShape();
profile.setRoundingRadius(0.3);

var revolved = new RevolvedAreaSolid();
revolved.setShape(profile);
revolved.setOrigin(new Vector3(1, 0, 0));
revolved.setAngleStart(0);
revolved.setAngleEnd(Math.PI);
scene.getRootNode().createChildNode(revolved);

scene.save("revolved.obj");
```

### Siehe auch

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


