---
title: "TransformBuilder.Translate"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método TransformBuilder. Encadenar una transformación de traslación"
type: docs
weight: 150
url: /es/net/aspose.threed.utilities/transformbuilder/translate/
---
## Translate(double, double, double) {#translate_1}

Encadenar una transformación de traslación

```csharp
public TransformBuilder Translate(double tx, double ty, double tz)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tx | Doble |  |
| ty | Doble |  |
| tz | Doble |  |

## Ejemplos

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(0, 10, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Ver también

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Translate(Vector3) {#translate}

Encadenar una transformación de traslación

```csharp
public TransformBuilder Translate(Vector3 v)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v | Vector3 |  |

## Ejemplos

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(new Vector3(0, 10, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Ver también

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


