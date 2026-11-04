---
title: "Klasse BooleanOperator"
second_title: "Aspose.3D voor .NET API-referentie"
description: "Aspose.ThreeD.Entities.BooleanOperator class. Booleaanse operator stelt u in staat een Booleaanse bewerking toe te passen op twee IMeshConvertible-instanties"
type: docs
weight: 280
url: /nl/net/aspose.threed.entities/booleanoperator/
---
## BooleanOperator class

Booleaanse operator stelt u in staat een Booleaanse bewerking toe te passen op twee [`IMeshConvertible`](../imeshconvertible/) instanties.

```csharp
public class BooleanOperator : Entity, IMeshConvertible
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [BooleanOperator](booleanoperator/#constructor)() | Constructor van `BooleanOperator` |
| [BooleanOperator](booleanoperator/#constructor_1)(BooleanOperation, A3DObject, A3DObject) | Construeert een nieuw exemplaar van `BooleanOperator` met twee operanden |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Haalt op of stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [First](../../aspose.threed.entities/booleanoperator/first/) { get; set; } | De eerste operand van de Booleaanse operator |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Haalt op of stelt de naam in. |
| [Operator](../../aspose.threed.entities/booleanoperator/operator/) { get; set; } | De Booleaanse operator die wordt gebruikt in de bewerking om de resulterende mesh te maken. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Haalt op of stelt de eerste bovenliggende node in; indien de eerste bovenliggende node wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende nodes. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Haalt alle bovenliggende nodes op; een entiteit kan aan meerdere bovenliggende nodes worden gekoppeld voor geometrie‑instantiatie. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Haalt de verzameling van alle eigenschappen op. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Haalt de scène op waartoe dit object behoort |
| [Second](../../aspose.threed.entities/booleanoperator/second/) { get; set; } | De tweede operand van de Booleaanse operator |

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
| [ToMesh](../../aspose.threed.entities/booleanoperator/tomesh/)() | Voer de Booleaanse bewerking uit op twee operanden |

### Zie ook

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


