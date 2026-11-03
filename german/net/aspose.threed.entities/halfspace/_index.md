---
title: "Klasse HalfSpace"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.HalfSpace-Klasse. HalfSpace stellt einen unendlichen Raum dar, der durch eine Ebene geteilt wird; dies kann mit BooleanOperator verwendet werden."
type: docs
weight: 420
url: /de/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` stellt einen unendlichen Raum dar, der durch eine Ebene geteilt wird, dies kann mit [`BooleanOperator`](../booleanoperator/) verwendet werden.

```csharp
public class HalfSpace : Entity
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | Konstruiert eine neue Instanz von `HalfSpace` |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | Konstruiert eine neue Instanz von `HalfSpace` mit dem angegebenen Normalenvektor und einer Position auf der Schneideebene; |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | Die Normale der Teilungsebene, die Ebene ist definiert als N * P + D = 0, wobei N die Normale und P ein beliebiger Punkt auf der Ebene ist. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | Ein beliebiger Punkt auf der Teilungsebene, die Ebene ist definiert als N * P + D = 0, wobei N die Normale und P ein beliebiger Punkt auf der Ebene ist. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
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

### Siehe auch

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


