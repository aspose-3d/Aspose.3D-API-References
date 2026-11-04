---
title: "Klasse FontFile"
second_title: "Aspose.3D voor .NET API-referentie"
description: "Aspose.ThreeD.Profiles.FontFile klasse. Lettertypebestand bevat definities voor glyphs, dit wordt gebruikt om een tekstprofiel te maken"
type: docs
weight: 1720
url: /nl/net/aspose.threed.profiles/fontfile/
---
## FontFile class

Lettertypebestand bevat definities voor glyphs, dit wordt gebruikt om een tekstprofiel te maken.

```csharp
public abstract class FontFile : A3DObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Haalt op of stelt de naam in. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Haalt de verzameling van alle eigenschappen op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromFile](../../aspose.threed.profiles/fontfile/fromfile/)(string) | Laad FontFile van bestandsnaam |
| static [Parse](../../aspose.threed.profiles/fontfile/parse/)(byte[]) | Parse FontFile van bytes |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of een native‑eigenschap (geïdentificeerd aan de hand van de naam). |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Haalt de waarde van de opgegeven eigenschap op |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Verwijdert een dynamische eigenschap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Verwijder de opgegeven eigenschap die wordt geïdentificeerd op naam |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Stelt de waarde van de opgegeven eigenschap in |

## Voorbeelden

De volgende code toont hoe je een 3D-mesh maakt van tekst met behulp van een opgegeven lettertypebestand.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### Zie ook

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


