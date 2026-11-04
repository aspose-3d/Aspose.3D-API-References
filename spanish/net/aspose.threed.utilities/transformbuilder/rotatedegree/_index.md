---
title: "TransformBuilder.RotateDegree"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método TransformBuilder. Encadena una transformación de rotación en grados"
type: docs
weight: 100
url: /es/net/aspose.threed.utilities/transformbuilder/rotatedegree/
---
## RotateDegree(double, Vector3) {#rotatedegree}

Encadenar una transformación de rotación en grados

```csharp
public TransformBuilder RotateDegree(double angle, Vector3 axis)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | Doble | El ángulo a rotar en grados |
| eje | Vector3 | El eje de rotación |

## Ejemplos

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateDegree(90, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Ver también

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateDegree(Vector3, RotationOrder) {#rotatedegree_1}

Agregar rotación con el orden especificado

```csharp
public void RotateDegree(Vector3 rot, RotationOrder order)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rot | Vector3 | Rotación en grados |
| orden | RotationOrder |  |

### Ver también

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


