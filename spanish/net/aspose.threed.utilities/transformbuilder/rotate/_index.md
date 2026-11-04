---
title: "TransformBuilder.Rotate"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método TransformBuilder. Encadena una rotación mediante un cuaternión"
type: docs
weight: 90
url: /es/net/aspose.threed.utilities/transformbuilder/rotate/
---
## TransformBuilder.Rotate method

Encadenar una rotación mediante un cuaternión

```csharp
public TransformBuilder Rotate(Quaternion q)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| q | Cuaternión |  |

## Ejemplos

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Rotate(Quaternion.FromEulerAngle(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Ver también

* struct [Quaternion](../../quaternion/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


