---
title: "TransformBuilder.Scale"
second_title: "Aspose.3D für .NET API-Referenz"
description: "TransformBuilder-Methode. Ketten Sie eine Skalierungs-Transformationsmatrix mit einer um s skalierten Komponente"
type: docs
weight: 140
url: /de/net/aspose.threed.utilities/transformbuilder/scale/
---
## Scale(double) {#scale_1}

Verkette eine Skalierungs-Transformationsmatrix, wobei eine Komponente um s skaliert wird.

```csharp
public TransformBuilder Scale(double s)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | Double |  |

## Beispiele

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Siehe auch

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

Verkette eine Skalierungs-Transformationsmatrix.

```csharp
public TransformBuilder Scale(double x, double y, double z)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Double |  |
| y | Double |  |
| z | Double |  |

## Beispiele

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10, 10, 10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Siehe auch

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(Vector3) {#scale}

Verkette eine Skalierungs-Transformation.

```csharp
public TransformBuilder Scale(Vector3 s)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | Vector3 |  |

## Beispiele

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(new Vector3(10, 10, 10));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Siehe auch

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


