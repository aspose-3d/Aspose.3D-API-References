---
title: "TransformBuilder.Rotate"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "TransformBuilder méthode. Enchaîner une rotation par un quaternion"
type: docs
weight: 90
url: /fr/net/aspose.threed.utilities/transformbuilder/rotate/
---
## TransformBuilder.Rotate method

Chaînez une rotation par un quaternion

```csharp
public TransformBuilder Rotate(Quaternion q)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| q | Quaternion |  |

## Exemples

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Rotate(Quaternion.FromEulerAngle(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Voir aussi

* struct [Quaternion](../../quaternion/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


