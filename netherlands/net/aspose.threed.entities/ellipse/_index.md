---
title: Ellipse
second_title: Aspose.3D voor .NET API-referentie
description: EenEllipse./ellipse/definieert een reeks punten die de vorm van een ellips vormen.
type: docs
weight: 330
url: /nl/net/aspose.threed.entities/ellipse/
---
## Ellipse class

Een`Ellipse`definieert een reeks punten die de vorm van een ellips vormen.

```csharp
public class Ellipse : Curve
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Ellipse](ellipse/#constructor)() | Constructeur van`Ellipse` |
| [Ellipse](ellipse/#constructor_1)(double, double) | Constructeur van`Ellipse` |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Haalt of stelt de kleur van de lijn in, standaardwaarde is wit(1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Haalt op of stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Krijgt of stelt de naam in. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Haalt of stelt het eerste bovenliggende knooppunt in. Als het eerste bovenliggende knooppunt wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knooppunten. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Haalt alle bovenliggende knooppunten op, een entiteit kan worden gekoppeld aan meerdere bovenliggende knooppunten voor geometrie-instancing |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Haalt de verzameling van alle eigenschappen op. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Krijgt de scène waartoe dit object behoort |
| [SemiAxis1](../../aspose.threed.entities/ellipse/semiaxis1/) { get; set; } | Straal op X-as |
| [SemiAxis2](../../aspose.threed.entities/ellipse/semiaxis2/) { get; set; } | Straal op Y-as |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Vindt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of native eigenschap (geïdentificeerd door zijn naam) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Haalt het begrenzingskader op van de huidige entiteit in het coördinatensysteem van de objectruimte. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Haalt de sleutel op van de entiteitsrenderer die is geregistreerd in de renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Haal de waarde op van gespecificeerde eigenschap |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Verwijdert een dynamische eigenschap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Verwijder de gespecificeerde eigenschap geïdentificeerd door name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Stelt de waarde in van gespecificeerde eigenschap |

### Zie ook

* class [Curve](../curve/)
* naamruimte [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
