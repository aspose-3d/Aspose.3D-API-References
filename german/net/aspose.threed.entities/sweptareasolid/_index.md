---
title: "Klasse SweptAreaSolid"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.SweptAreaSolid Klasse. Ein SweptAreaSolid erzeugt eine Geometrie, indem ein Profil entlang einer Direktrixe bewegt wird."
type: docs
weight: 750
url: /de/net/aspose.threed.entities/sweptareasolid/
---
## SweptAreaSolid class

Ein `SweptAreaSolid` erzeugt eine Geometrie, indem ein Profil entlang einer Direktrixe bewegt wird.

```csharp
public class SweptAreaSolid : Entity, IMeshConvertible
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SweptAreaSolid](sweptareasolid/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Directrix](../../aspose.threed.entities/sweptareasolid/directrix/) { get; set; } | Die Direktrixe, entlang der die SweptArea bewegt wird. |
| [EndPoint](../../aspose.threed.entities/sweptareasolid/endpoint/) { get; set; } | Der Endpunkt der Direktrixe. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Shape](../../aspose.threed.entities/sweptareasolid/shape/) { get; set; } | Das Basisprofil zur Konstruktion der Geometrie. |
| [StartPoint](../../aspose.threed.entities/sweptareasolid/startpoint/) { get; set; } | Der Startpunkt der Direktrixe. |

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
| [ToMesh](../../aspose.threed.entities/sweptareasolid/tomesh/)() | Konvertiere das aktuelle Objekt zu einem Mesh |

## Beispiele

Der folgende Code zeigt, wie man ein solides Objekt modelliert, indem man eine C‑Form auf einem Kreis sweepet.

```csharp
var directrix = new Circle(20);
var shape = new CShape();

var swept = new SweptAreaSolid()
{
  Shape = shape,
  Directrix = directrix,
  StartPoint = EndPoint.FromDegree(0),
  EndPoint = EndPoint.FromDegree(130)
};

var scene = new Scene();
scene.RootNode.CreateChildNode(swept);
scene.Save("swept.obj");
```

### Siehe auch

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


