---
title: "Klasse Pose"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Pose Klasse. Die Pose wird verwendet, um Transformationsmatrizen zu speichern, wenn die Geometrie geskinnt ist. Die Pose ist ein Satz von BonePose, wobei jeder BonePose die konkreten Transformationsinformationen des Knochenspeichers sichert."
type: docs
weight: 1650
url: /de/net/aspose.threed/pose/
---
## Pose class

Die Pose wird verwendet, um Transformationsmatrizen zu speichern, wenn die Geometrie geskinnt ist. Die Pose ist ein Satz von [`BonePose`](../bonepose/), wobei jeder [`BonePose`](../bonepose/) die konkreten Transformationsinformationen des Knoten des Knochens speichert.

```csharp
public class Pose : A3DObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Pose](pose/#constructor)() | Initialisiert eine neue Instanz der `Pose`-Klasse. |
| [Pose](pose/#constructor_1)(string) | Initialisiert eine neue Instanz der `Pose`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BonePoses](../../aspose.threed/pose/boneposes/) { get; } | Liefert alle [`BonePose`](../bonepose/). |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [PoseType](../../aspose.threed/pose/posetype/) { get; set; } | Liefert oder setzt den Typ der Pose. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose)(Node, Matrix4) | Speichert die Transformationsmatrix der Pose für den angegebenen Knoten des Knochens. Die globale Transformationsmatrix wird impliziert. |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose_1)(Node, Matrix4, bool) | Speichert die Transformationsmatrix der Pose für den angegebenen Knoten des Knochens. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


