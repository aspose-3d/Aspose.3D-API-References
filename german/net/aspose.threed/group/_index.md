---
title: "Klasse Group"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Group Klasse. Eine Group stellt die logischen Beziehungen von Node dar."
type: docs
weight: 1570
url: /de/net/aspose.threed/group/
---
## Group class

Eine `Group` stellt die logischen Beziehungen von [`Node`](../node/) dar.

```csharp
public class Group : A3DObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Group](group/)(string) | Erstelle eine neue Instanz von `Group`. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Groups](../../aspose.threed/group/groups/) { get; } | Untergruppen |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Nodes](../../aspose.threed/group/nodes/) { get; } | Die Knoten in dieser Gruppe. |
| [Parent](../../aspose.threed/group/parent/) { get; } | Übergeordnete Gruppe der aktuellen Gruppe. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |
| override [ToString](../../aspose.threed/group/tostring/)() | Gibt die Zeichenkettenrepräsentation von `Group` zurück. |

### Siehe auch

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


