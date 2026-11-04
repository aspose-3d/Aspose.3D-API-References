---
title: "TransformBuilder.RotateEulerRadian"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método TransformBuilder. Encadenar una rotación por ángulos de Euler en radianes"
type: docs
weight: 120
url: /es/net/aspose.threed.utilities/transformbuilder/rotateeulerradian/
---
## RotateEulerRadian(double, double, double) {#rotateeulerradian_1}

Encadenar una rotación por ángulos de Euler en radianes

```csharp
public TransformBuilder RotateEulerRadian(double x, double y, double z)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Doble |  |
| y | Doble |  |
| z | Doble |  |

## Ejemplos

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(0, Math.PI, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Ver también

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateEulerRadian(Vector3) {#rotateeulerradian}

Encadenar una rotación por ángulos de Euler en radianes

```csharp
public TransformBuilder RotateEulerRadian(Vector3 r)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| r | Vector3 |  |

## Ejemplos

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(new Vector3(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Ver también

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


