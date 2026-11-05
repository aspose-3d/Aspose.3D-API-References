---
title: "Enum BoneLinkMode"
second_title: "Aspose.3D för .NET API‑referens"
description: "Aspose.ThreeD.Deformers.BoneLinkMode‑enum. Ett benlänkningsläge avser hur ett ben är anslutet eller länkat till sitt föräldrabben inom en hierarkisk struktur"
type: docs
weight: 200
url: /sv/net/aspose.threed.deformers/bonelinkmode/
---
## BoneLinkMode enumeration

Ett bens länkningsläge avser hur ett ben är anslutet eller länkat till sitt föräldrabben inom en hierarkisk struktur.

```csharp
public enum BoneLinkMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Normalize | `0` | I det här läget normaliseras transformationerna för barnbenen i förhållande till deras föräldrabens transformationer. |
| Additive | `1` | Additivt läge beräknar transformationerna för barnbenen genom att lägga till deras egna lokala transformationer till deras föräldrabens. |
| TotalOne | `2` | Total One säkerställer att kombinerade transformationer för föräldra- och barnbenen resulterar i en kombinerad transformation som skalas till en total längd på en enhet. |

### Se även

* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


