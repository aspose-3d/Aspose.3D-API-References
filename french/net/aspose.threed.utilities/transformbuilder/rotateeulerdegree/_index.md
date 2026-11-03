---
title: "TransformBuilder.RotateEulerDegree"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "TransformBuilder méthode. Enchaîner une rotation par angles d'Euler en degré"
type: docs
weight: 110
url: /fr/net/aspose.threed.utilities/transformbuilder/rotateeulerdegree/
---
## TransformBuilder.RotateEulerDegree method

Enchaîner une rotation par angles d'Euler en degrés

```csharp
public TransformBuilder RotateEulerDegree(double degX, double degY, double degZ)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| degX | Double |  |
| degY | Double |  |
| degZ | Double |  |

## Exemples

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerDegree(0, 90, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Voir aussi

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


