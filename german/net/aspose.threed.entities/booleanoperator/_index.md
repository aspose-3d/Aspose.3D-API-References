---
title: "Klasse BooleanOperator"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.BooleanOperator Klasse. Der Boolesche Operator ermöglicht das Anwenden einer Booleschen Operation auf zwei IMeshConvertible‑Instanzen."
type: docs
weight: 280
url: /de/net/aspose.threed.entities/booleanoperator/
---
## BooleanOperator class

Der Boolesche Operator ermöglicht das Anwenden einer Booleschen Operation auf zwei [`IMeshConvertible`](../imeshconvertible/) Instanzen.

```csharp
public class BooleanOperator : Entity, IMeshConvertible
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BooleanOperator](booleanoperator/#constructor)() | Konstruktor von `BooleanOperator` |
| [BooleanOperator](booleanoperator/#constructor_1)(BooleanOperation, A3DObject, A3DObject) | Erstellt eine neue Instanz von `BooleanOperator` mit zwei Operanden |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [First](../../aspose.threed.entities/booleanoperator/first/) { get; set; } | Der erste Operand des Booleschen Operators |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Operator](../../aspose.threed.entities/booleanoperator/operator/) { get; set; } | Der im Vorgang verwendete Boolesche Operator, um das Ergebnis‑Mesh zu erzeugen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Second](../../aspose.threed.entities/booleanoperator/second/) { get; set; } | Der zweite Operand des Booleschen Operators |

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
| [ToMesh](../../aspose.threed.entities/booleanoperator/tomesh/)() | Führt die Boolesche Operation mit zwei Operanden aus |

### Siehe auch

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


