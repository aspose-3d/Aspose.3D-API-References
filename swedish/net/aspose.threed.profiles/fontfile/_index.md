---
title: "Klass FontFile"
second_title: "Aspose.3D för .NET API‑referens"
description: "Aspose.ThreeD.Profiles.FontFile-klass. Typsnittfilen innehåller definitioner för glyfer, den används för att skapa textprofil"
type: docs
weight: 1720
url: /sv/net/aspose.threed.profiles/fontfile/
---
## FontFile class

Typsnittfilen innehåller definitioner för glyfer, den används för att skapa textprofil.

```csharp
public abstract class FontFile : A3DObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Hämtar eller anger namnet. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Hämtar samlingen av alla egenskaper. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromFile](../../aspose.threed.profiles/fontfile/fromfile/)(string) | Läs in FontFile från filnamn |
| static [Parse](../../aspose.threed.profiles/fontfile/parse/)(byte[]) | Analysera FontFile från byte |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Hittar egenskapen. Den kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad med dess namn) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Hämta värdet för den angivna egenskapen |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Tar bort en dynamisk egenskap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Ta bort den angivna egenskapen identifierad med namn |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Sätter värdet för den angivna egenskapen |

## Exempel

Följande kod visar hur man skapar ett 3D-nät från text med angiven typsnittsfil.

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

### Se även

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


