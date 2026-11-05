---
title: "Klass Text"
second_title: "Aspose.3D för .NET API‑referens"
description: "Aspose.ThreeD.Profiles.Text-klass. Textprofil den här profilen beskriver konturer med hjälp av typsnitt och text"
type: docs
weight: 1820
url: /sv/net/aspose.threed.profiles/text/
---
## Text class

Textprofil, den här profilen beskriver konturer med hjälp av typsnitt och text.

```csharp
public class Text : Profile
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Text](text/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Content](../../aspose.threed.profiles/text/content/) { get; set; } | Innehållet i texten |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Hämtar eller anger om detta objekt ska exkluderas vid export. |
| [Font](../../aspose.threed.profiles/text/font/) { get; set; } | Typsnittet för texten. |
| [FontSize](../../aspose.threed.profiles/text/fontsize/) { get; set; } | Typsnittsstorleksskala. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Hämtar eller anger namnet. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Hämtar eller anger den första föräldranoden, om den första föräldranoden anges kommer detta objekt att frikopplas från andra föräldranoder. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Hämtar alla föräldranoder, ett objekt kan fästas vid flera föräldranoder för geometrisk instansering |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Hämtar samlingen av alla egenskaper. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Hämtar scenen som detta objekt tillhör |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Hittar egenskapen. Den kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad med dess namn) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Hämtar den omgivande lådan för den aktuella enheten i dess objektrumskoordinatsystem. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Hämtar nyckeln för enhetens renderare som är registrerad i renderaren |
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

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


