---
title: "TransformBuilder.Scale"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método TransformBuilder. Encadena una matriz de transformación de escala con un componente escalado por s"
type: docs
weight: 140
url: /es/net/aspose.threed.utilities/transformbuilder/scale/
---
## Scale(double) {#scale_1}

Encadenar una matriz de transformación de escalado con un componente escalado por s

```csharp
public TransformBuilder Scale(double s)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | Doble |  |

## Ejemplos

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Ver también

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

Encadenar una matriz de transformación de escalado

```csharp
public TransformBuilder Scale(double x, double y, double z)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Doble |  |
| y | Doble |  |
| z | Doble |  |

## Ejemplos

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10, 10, 10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Ver también

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(Vector3) {#scale}

Encadenar una transformación de escala

```csharp
public TransformBuilder Scale(Vector3 s)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | Vector3 |  |

## Ejemplos

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(new Vector3(10, 10, 10));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Ver también

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


