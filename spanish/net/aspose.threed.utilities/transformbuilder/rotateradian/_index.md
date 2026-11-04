---
title: "TransformBuilder.RotateRadian"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método TransformBuilder. Encadena una transformación de rotación en radianes"
type: docs
weight: 130
url: /es/net/aspose.threed.utilities/transformbuilder/rotateradian/
---
## RotateRadian(double, Vector3) {#rotateradian}

Encadenar una transformación de rotación en radianes

```csharp
public TransformBuilder RotateRadian(double angle, Vector3 axis)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | Doble | El ángulo a rotar en radianes |
| eje | Vector3 | El eje de rotación |

## Ejemplos

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(Math.PI, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Ver también

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateRadian(Vector3, RotationOrder) {#rotateradian_1}

Agregar rotación con el orden especificado

```csharp
public void RotateRadian(Vector3 rot, RotationOrder order)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rot | Vector3 | Rotación en radianes |
| orden | RotationOrder |  |

## Ejemplos

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(new Vector3(0.3, 0.4, 0.1), RotationOrder.YZX);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Ver también

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


