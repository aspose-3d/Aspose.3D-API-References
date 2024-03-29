---
title: MorphTargetChannel
second_title: Aspose.3D för .NET API-referens
description: En MorphTargetChannel används avMorphTargetDeformer./morphtargetdeformer för att organisera målgeometrierna. Vissa filformat som FBX stöder flera kanaler parallellt.
type: docs
weight: 200
url: /sv/net/aspose.threed.deformers/morphtargetchannel/
---
## MorphTargetChannel class

En MorphTargetChannel används av[`MorphTargetDeformer`](../morphtargetdeformer) för att organisera målgeometrierna. Vissa filformat som FBX stöder flera kanaler parallellt.

```csharp
public class MorphTargetChannel : A3DObject
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [MorphTargetChannel](morphtargetchannel#constructor)() | Initierar en ny instans av[`MorphTargetChannel`](../morphtargetchannel) class. |
| [MorphTargetChannel](morphtargetchannel#constructor_1)(string) | Initierar en ny instans av[`MorphTargetChannel`](../morphtargetchannel) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ChannelWeight](../../aspose.threed.deformers/morphtargetchannel/channelweight) { get; set; } | Hämtar eller ställer in deformeringsvikten för denna kanal. Vikten är mellan 0,0 och 1,0 |
| [Item](../../aspose.threed.deformers/morphtargetchannel/item) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Hämtar eller ställer in namnet. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Hämtar samlingen av alla egenskaper. |
| [Targets](../../aspose.threed.deformers/morphtargetchannel/targets) { get; } | Får alla mål associerade med kanalen. |
| [Weights](../../aspose.threed.deformers/morphtargetchannel/weights) { get; } | Får alla viktvärden för målgeometrier. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Hittar egenskapen. Det kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller inbyggd egenskap (identifierad med dess namn) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Få värdet av specificerad egenskap |
| [GetWeight](../../aspose.threed.deformers/morphtargetchannel/getweight)(Shape) | Får vikten för det angivna målet, om målet inte tillhör denna kanal returneras standardvärdet 0. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Tar bort en dynamisk egenskap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Ta bort den angivna egenskapen identifierad av name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Anger värdet för specificerad egenskap |
| [SetWeight](../../aspose.threed.deformers/morphtargetchannel/setweight)(Shape, double) | Ställer in vikten för det angivna målet, standardvärdet är 1, intervallet bör mellan 0~1 |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [DefaultWeight](../../aspose.threed.deformers/morphtargetchannel/defaultweight) | Standardvikt för morphmål. |

### Anmärkningar

Vikt är mellan 0 och 1,0, och standardvikt för mål är 0,0;

### Se även

* class [A3DObject](../../aspose.threed/a3dobject)
* namnutrymme [Aspose.ThreeD.Deformers](../../aspose.threed.deformers)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
