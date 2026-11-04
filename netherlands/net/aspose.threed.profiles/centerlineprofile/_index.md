---
title: "Klasse CenterLineProfile"
second_title: "Aspose.3D voor .NET API-referentie"
description: "Aspose.ThreeD.Profiles.CenterLineProfile klasse. IFC-compatibel middellijnprofiel"
type: docs
weight: 1690
url: /nl/net/aspose.threed.profiles/centerlineprofile/
---
## CenterLineProfile class

IFC-compatibel middellijnprofiel

```csharp
public class CenterLineProfile : Profile
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [CenterLineProfile](centerlineprofile/)(Curve, double) | Construeert een nieuw `CenterLineProfile` met de opgegeven curve als middellijn. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Curve](../../aspose.threed.profiles/centerlineprofile/curve/) { get; set; } | De kromme van de middellijn van het profiel |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Haalt op of stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Haalt op of stelt de naam in. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Haalt op of stelt de eerste bovenliggende node in; indien de eerste bovenliggende node wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende nodes. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Haalt alle bovenliggende nodes op; een entiteit kan aan meerdere bovenliggende nodes worden gekoppeld voor geometrie‑instantiatie. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Haalt de verzameling van alle eigenschappen op. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Haalt de scène op waartoe dit object behoort |
| [Thickness](../../aspose.threed.profiles/centerlineprofile/thickness/) { get; set; } | Dikte toegepast langs de middellijn |

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

### Zie ook

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


