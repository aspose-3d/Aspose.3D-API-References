---
title: "Klasse MorphTargetDeformer"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Deformers.MorphTargetDeformer Klasse. MorphTargetDeformer bietet per‑Vertex‑Animation. MorphTargetDeformer organisiert alle Ziele über MorphTargetChannel, wobei jeder Kanal mehrere Ziele organisieren kann. Ein häufiger Einsatz von Morph‑Target‑Deformer ist das Anwenden von Gesichtsausdrücken auf einen Charakter. Weitere Details finden Sie unter https//en.wikipedia.org/wiki/Morph_target_animation"
type: docs
weight: 230
url: /de/net/aspose.threed.deformers/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer bietet per-Vertex-Animation. MorphTargetDeformer organisiert alle Ziele über [`MorphTargetChannel`](../morphtargetchannel/), jeder Kanal kann mehrere Ziele organisieren. Ein häufiger Einsatz des MorphTargetDeformer ist das Anwenden von Gesichtsausdrücken auf einen Charakter. Weitere Details finden Sie unter https://en.wikipedia.org/wiki/Morph_target_animation

```csharp
public class MorphTargetDeformer : Deformer
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MorphTargetDeformer](morphtargetdeformer/#constructor)() | Initialisiert eine neue Instanz der Klasse `MorphTargetDeformer`. |
| [MorphTargetDeformer](morphtargetdeformer/#constructor_1)(string) | Initialisiert eine neue Instanz der Klasse `MorphTargetDeformer`. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Channels](../../aspose.threed.deformers/morphtargetdeformer/channels/) { get; } | Gibt alle Kanäle zurück, die in diesem Deformer enthalten sind |
| [Item](../../aspose.threed.deformers/morphtargetdeformer/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Owner](../../aspose.threed.deformers/deformer/owner/) { get; } | Gibt die Geometrie zurück, die diesen Deformer besitzt |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [Deformer](../deformer/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


