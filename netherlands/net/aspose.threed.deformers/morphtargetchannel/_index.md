---
title: MorphTargetChannel
second_title: Aspose.3D voor .NET API-referentie
description: Een MorphTargetChannel wordt gebruikt doorMorphTargetDeformer./morphtargetdeformer/ om de doelgeometrieën te organiseren. Sommige bestandsindelingen zoals FBX ondersteunen meerdere kanalen parallel.
type: docs
weight: 200
url: /nl/net/aspose.threed.deformers/morphtargetchannel/
---
## MorphTargetChannel class

Een MorphTargetChannel wordt gebruikt door[`MorphTargetDeformer`](../morphtargetdeformer/) om de doelgeometrieën te organiseren. Sommige bestandsindelingen zoals FBX ondersteunen meerdere kanalen parallel.

```csharp
public class MorphTargetChannel : A3DObject
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [MorphTargetChannel](morphtargetchannel/#constructor)() | Initialiseert een nieuw exemplaar van het`MorphTargetChannel` klasse. |
| [MorphTargetChannel](morphtargetchannel/#constructor_1)(string) | Initialiseert een nieuw exemplaar van het`MorphTargetChannel` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ChannelWeight](../../aspose.threed.deformers/morphtargetchannel/channelweight/) { get; set; } | Hiermee wordt het gewicht van de deformer van dit kanaal opgehaald of ingesteld. Het gewicht ligt tussen 0,0 en 1,0 |
| [Item](../../aspose.threed.deformers/morphtargetchannel/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Krijgt of stelt de naam in. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Haalt de verzameling van alle eigenschappen op. |
| [Targets](../../aspose.threed.deformers/morphtargetchannel/targets/) { get; } | Haalt alle doelen op die aan het kanaal zijn gekoppeld. |
| [Weights](../../aspose.threed.deformers/morphtargetchannel/weights/) { get; } | Krijgt de volledige gewichtswaarden van doelgeometrieën. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Vindt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of native eigenschap (geïdentificeerd door zijn naam) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Haal de waarde op van gespecificeerde eigenschap |
| [GetWeight](../../aspose.threed.deformers/morphtargetchannel/getweight/)(Shape) | Krijgt het gewicht voor het opgegeven doel, als het doel niet tot dit kanaal behoort, wordt de standaardwaarde 0 geretourneerd. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Verwijdert een dynamische eigenschap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Verwijder de gespecificeerde eigenschap geïdentificeerd door name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Stelt de waarde in van gespecificeerde eigenschap |
| [SetWeight](../../aspose.threed.deformers/morphtargetchannel/setweight/)(Shape, double) | Stelt het gewicht in voor het opgegeven doel, standaardwaarde is 1, bereik moet tussen 0~1 liggen |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [DefaultWeight](../../aspose.threed.deformers/morphtargetchannel/defaultweight/) | Standaardgewicht voor morph-doel. |

### Opmerkingen

Gewicht ligt tussen 0 en 1,0, en standaardgewicht voor doel is 0,0;

### Zie ook

* class [A3DObject](../../aspose.threed/a3dobject/)
* naamruimte [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
