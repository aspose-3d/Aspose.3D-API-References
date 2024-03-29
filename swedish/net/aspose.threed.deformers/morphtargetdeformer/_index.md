---
title: MorphTargetDeformer
second_title: Aspose.3D för .NET API-referens
description: MorphTargetDeformer tillhandahåller animering per vertex. MorphTargetDeformer organiserar alla mål viaMorphTargetChannel./morphtargetchannel  kan varje kanal organisera flera mål. En vanlig användning av morph target deformer är att applicera ansiktsuttryck på en karaktär. Mer information finns på https//en.wikipedia.org/wiki/Morph_target_animation
type: docs
weight: 210
url: /sv/net/aspose.threed.deformers/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer tillhandahåller animering per vertex. MorphTargetDeformer organiserar alla mål via[`MorphTargetChannel`](../morphtargetchannel) , kan varje kanal organisera flera mål. En vanlig användning av morph target deformer är att applicera ansiktsuttryck på en karaktär. Mer information finns på https://en.wikipedia.org/wiki/Morph_target_animation

```csharp
public class MorphTargetDeformer : Deformer
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [MorphTargetDeformer](morphtargetdeformer#constructor)() | Initierar en ny instans av[`MorphTargetDeformer`](../morphtargetdeformer) class. |
| [MorphTargetDeformer](morphtargetdeformer#constructor_1)(string) | Initierar en ny instans av[`MorphTargetDeformer`](../morphtargetdeformer) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Channels](../../aspose.threed.deformers/morphtargetdeformer/channels) { get; } | Får alla kanaler som finns i denna deformer |
| [Item](../../aspose.threed.deformers/morphtargetdeformer/item) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Hämtar eller ställer in namnet. |
| [Owner](../../aspose.threed.deformers/deformer/owner) { get; } | Får geometrin som äger denna deformer |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Hämtar samlingen av alla egenskaper. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Hittar egenskapen. Det kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller inbyggd egenskap (identifierad med dess namn) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Få värdet av specificerad egenskap |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Tar bort en dynamisk egenskap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Ta bort den angivna egenskapen identifierad av name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Anger värdet för specificerad egenskap |

### Se även

* class [Deformer](../deformer)
* namnutrymme [Aspose.ThreeD.Deformers](../../aspose.threed.deformers)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
