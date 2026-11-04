---
title: "Klasse Tekst"
second_title: "Aspose.3D voor .NET API-referentie"
description: "Aspose.ThreeD.Profiles.Text klasse. Tekstprofiel dit profiel beschrijft contouren met behulp van lettertype en tekst"
type: docs
weight: 1820
url: /nl/net/aspose.threed.profiles/text/
---
## Text class

Tekstprofiel, dit profiel beschrijft contouren met behulp van lettertype en tekst.

```csharp
public class Text : Profile
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Text](text/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Content](../../aspose.threed.profiles/text/content/) { get; set; } | Inhoud van de tekst |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Haalt op of stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [Font](../../aspose.threed.profiles/text/font/) { get; set; } | Het lettertype van de tekst. |
| [FontSize](../../aspose.threed.profiles/text/fontsize/) { get; set; } | Lettergrootte schaal. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Haalt op of stelt de naam in. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Haalt op of stelt de eerste bovenliggende node in; indien de eerste bovenliggende node wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende nodes. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Haalt alle bovenliggende nodes op; een entiteit kan aan meerdere bovenliggende nodes worden gekoppeld voor geometrie‑instantiatie. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Haalt de verzameling van alle eigenschappen op. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Haalt de scène op waartoe dit object behoort |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of een native‑eigenschap (geïdentificeerd aan de hand van de naam). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Haalt de begrenzingsdoos van de huidige entiteit op in het object‑ruimtes coördinatensysteem. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Haalt de sleutel van de entiteit‑renderer op die is geregistreerd in de renderer |
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

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


