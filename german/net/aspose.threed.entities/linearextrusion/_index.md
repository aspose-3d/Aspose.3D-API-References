---
title: "Klasse LinearExtrusion"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.LinearExtrusion Klasse. Lineare Extrusion nimmt eine 2D‑Form als Eingabe und erweitert die Form in der dritten Dimension."
type: docs
weight: 490
url: /de/net/aspose.threed.entities/linearextrusion/
---
## LinearExtrusion class

Lineare Extrusion nimmt eine 2D-Form als Eingabe und erweitert die Form in die dritte Dimension.

```csharp
public class LinearExtrusion : Entity, IMeshConvertible
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LinearExtrusion](linearextrusion/#constructor)() | Konstruktor der Instanz `LinearExtrusion`. |
| [LinearExtrusion](linearextrusion/#constructor_1)(Profile, double) | Konstruktor der Instanz `LinearExtrusion`. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Center](../../aspose.threed.entities/linearextrusion/center/) { get; set; } | Wenn dieser Wert false ist, ist der Z‑Bereich der linearen Extrusion von 0 bis height, andernfalls ist der Bereich von -height/2 bis height/2. |
| [Direction](../../aspose.threed.entities/linearextrusion/direction/) { get; set; } | Die Richtung der Extrusion, Standardwert ist (0, 0, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [Height](../../aspose.threed.entities/linearextrusion/height/) { get; set; } | Die Höhe der extrudierten Geometrie, Standardwert ist 1.0 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Shape](../../aspose.threed.entities/linearextrusion/shape/) { get; set; } | Die Basisform, die extrudiert werden soll. |
| [Slices](../../aspose.threed.entities/linearextrusion/slices/) { get; set; } | Die Scheiben der verdrehten extrudierten Geometrie, Standardwert ist 1. |
| [Twist](../../aspose.threed.entities/linearextrusion/twist/) { get; set; } | Die Anzahl der Grad, durch die die Form extrudiert wird. |
| [TwistOffset](../../aspose.threed.entities/linearextrusion/twistoffset/) { get; set; } | Der Versatz, der beim Verdrehen verwendet wird, Standardwert ist (0, 0, 0). |

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
| [ToMesh](../../aspose.threed.entities/linearextrusion/tomesh/)() | Konvertiere die Extrusion zu einem Mesh. |

## Beispiele

Der folgende Code zeigt, wie man LinearExtrusion verwendet, um eine Form zu einem Festkörpermodell zu extrudieren.

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//Erstelle eine neue 3D‑Szene
Scene scene = new Scene();

// Initialisiere das Basisprofil, das extrudiert werden soll
var profile = new RectangleShape()
{
	RoundingRadius = 0.3
};

// Erstelle linken Knoten
var left = scene.RootNode.CreateChildNode();
left.CreateChildNode(new Box(0.01, 3, 3));

// Erstelle rechten Knoten
var right = scene.RootNode.CreateChildNode();
right.CreateChildNode(new Box(0.01, 3, 3));
right.Transform.Translation = new Vector3(5, 0, 0);

//Führe lineare Extrusion am linken Knoten unter Verwendung der Eigenschaften center und slices durch
left.CreateChildNode(new LinearExtrusion(profile, 10) { Center = false, Slices = 3, Twist = 20.0 });

// Führe lineare Extrusion am linken Knoten unter Verwendung der Eigenschaften center und slices durch
right.CreateChildNode(new LinearExtrusion(profile, 10) { Center = true, Slices = 3, Twist = 90.0 });

scene
```

### Siehe auch

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


