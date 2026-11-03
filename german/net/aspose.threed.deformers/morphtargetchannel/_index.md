---
title: "Klasse MorphTargetChannel"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Deformers.MorphTargetChannel Klasse. Ein MorphTargetChannel wird von MorphTargetDeformer verwendet, um die Zielgeometrien zu organisieren. Einige Dateiformate wie FBX unterstützen mehrere Kanäle parallel."
type: docs
weight: 220
url: /de/net/aspose.threed.deformers/morphtargetchannel/
---
## MorphTargetChannel class

Ein MorphTargetChannel wird von [`MorphTargetDeformer`](../morphtargetdeformer/) verwendet, um die Zielgeometrien zu organisieren. Einige Dateiformate wie FBX unterstützen mehrere Kanäle parallel.

```csharp
public class MorphTargetChannel : A3DObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MorphTargetChannel](morphtargetchannel/#constructor)() | Initialisiert eine neue Instanz der `MorphTargetChannel` Klasse. |
| [MorphTargetChannel](morphtargetchannel/#constructor_1)(string) | Initialisiert eine neue Instanz der `MorphTargetChannel` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ChannelWeight](../../aspose.threed.deformers/morphtargetchannel/channelweight/) { get; set; } | Ermittelt oder setzt das Deformer‑Gewicht dieses Kanals. Das Gewicht liegt zwischen 0,0 und 1,0. |
| [Item](../../aspose.threed.deformers/morphtargetchannel/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Targets](../../aspose.threed.deformers/morphtargetchannel/targets/) { get; } | Ermittelt alle dem Kanal zugeordneten Ziele. |
| [Weights](../../aspose.threed.deformers/morphtargetchannel/weights/) { get; } | Ermittelt die vollständigen Gewichtswerte der Zielgeometrien. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [GetWeight](../../aspose.threed.deformers/morphtargetchannel/getweight/)(Shape) | Ermittelt das Gewicht für das angegebene Ziel; gehört das Ziel nicht zu diesem Kanal, wird der Standardwert 0 zurückgegeben. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |
| [SetWeight](../../aspose.threed.deformers/morphtargetchannel/setweight/)(Shape, double) | Setzt das Gewicht für das angegebene Ziel, der Standardwert ist 1, der Bereich sollte zwischen 0 und 1 liegen. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DefaultWeight](../../aspose.threed.deformers/morphtargetchannel/defaultweight/) | Standardgewicht für Morph‑Ziel. |

## Hinweise

Das Gewicht liegt zwischen 0 und 1,0, und das Standardgewicht für das Ziel ist 0,0;

### Siehe auch

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


