---
title: CShape
second_title: Aspose.3D voor .NET API-referentie
description: IFCcompatibel Cvormig profiel gedefinieerd door parameters. De middenpositie van het profiel bevindt zich in het midden van het begrenzingskader.
type: docs
weight: 1520
url: /nl/net/aspose.threed.profiles/cshape/
---
## CShape class

IFC-compatibel C-vormig profiel gedefinieerd door parameters. De middenpositie van het profiel bevindt zich in het midden van het begrenzingskader.

```csharp
public class CShape : ParameterizedProfile
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [CShape](cshape/)() | Constructeur van`CShape` |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Depth](../../aspose.threed.profiles/cshape/depth/) { get; set; } | Haalt of stelt de diepte van het profiel in. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Haalt op of stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [Girth](../../aspose.threed.profiles/cshape/girth/) { get; set; } | Bepaalt of stelt de lengte van de omtrek in. |
| [InternalFilletRadius](../../aspose.threed.profiles/cshape/internalfilletradius/) { get; set; } | Haalt de interne afrondingsradius op of stelt deze in. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Krijgt of stelt de naam in. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Haalt of stelt het eerste bovenliggende knooppunt in. Als het eerste bovenliggende knooppunt wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knooppunten. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Haalt alle bovenliggende knooppunten op, een entiteit kan worden gekoppeld aan meerdere bovenliggende knooppunten voor geometrie-instancing |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Haalt de verzameling van alle eigenschappen op. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Krijgt de scène waartoe dit object behoort |
| [WallThickness](../../aspose.threed.profiles/cshape/wallthickness/) { get; set; } | Haalt of stelt de dikte van de muur in. |
| [Width](../../aspose.threed.profiles/cshape/width/) { get; set; } | Haalt of stelt de breedte van het profiel in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Vindt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of native eigenschap (geïdentificeerd door zijn naam) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Haalt het begrenzingskader op van de huidige entiteit in het coördinatensysteem van de objectruimte. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Haalt de sleutel op van de entiteitsrenderer die is geregistreerd in de renderer |
| override [GetExtent](../../aspose.threed.profiles/cshape/getextent/)() | Haalt het bereik op in x- en y-dimensie. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Haal de waarde op van gespecificeerde eigenschap |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Verwijdert een dynamische eigenschap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Verwijder de gespecificeerde eigenschap geïdentificeerd door name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Stelt de waarde in van gespecificeerde eigenschap |

### Zie ook

* class [ParameterizedProfile](../parameterizedprofile/)
* naamruimte [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
