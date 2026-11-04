---
title: "Klasse HalfSpace"
second_title: "Aspose.3D voor .NET API-referentie"
description: "Aspose.ThreeD.Entities.HalfSpace klasse. HalfSpace vertegenwoordigt een oneindige ruimte die wordt gesplitst door een vlak; dit kan worden gebruikt met BooleanOperator"
type: docs
weight: 420
url: /nl/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` vertegenwoordigt een oneindige ruimte die wordt gesplitst door een vlak, dit kan worden gebruikt met [`BooleanOperator`](../booleanoperator/)

```csharp
public class HalfSpace : Entity
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | Construeert een nieuw exemplaar van `HalfSpace` |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | Construeert een nieuw exemplaar van `HalfSpace` met een gegeven normaalvector en een positie op het snijvlak; |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Haalt op of stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Haalt op of stelt de naam in. |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | De normaal van het splitsingsvlak; het vlak wordt gedefinieerd als N * P + D = 0 waarbij N de normaal is en P elk punt op het vlak. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Haalt op of stelt de eerste bovenliggende node in; indien de eerste bovenliggende node wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende nodes. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Haalt alle bovenliggende nodes op; een entiteit kan aan meerdere bovenliggende nodes worden gekoppeld voor geometrie‑instantiatie. |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | Elk punt op het splitsingsvlak; het vlak wordt gedefinieerd als N * P + D = 0 waarbij N de normaal is en P elk punt op het vlak. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Haalt de verzameling van alle eigenschappen op. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Haalt de scène op waartoe dit object behoort |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of een native‑eigenschap (geïdentificeerd aan de hand van de naam). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Haalt de begrenzingsdoos van de huidige entiteit op in het object‑ruimtes coördinatensysteem. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Haalt de sleutel van de entiteit‑renderer op die is geregistreerd in de renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Haalt de waarde van de opgegeven eigenschap op |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Verwijdert een dynamische eigenschap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Verwijder de opgegeven eigenschap die wordt geïdentificeerd op naam |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Stelt de waarde van de opgegeven eigenschap in |

### Zie ook

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


