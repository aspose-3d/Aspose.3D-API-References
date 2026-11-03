---
title: "TransformBuilder.Scale"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "TransformBuilder méthode. Enchaîner une matrice de transformation d'échelle avec un composant mis à l'échelle par s"
type: docs
weight: 140
url: /fr/net/aspose.threed.utilities/transformbuilder/scale/
---
## Scale(double) {#scale_1}

Enchaîner une matrice de transformation d'échelle avec un composant mis à l'échelle par s

```csharp
public TransformBuilder Scale(double s)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| s | Double |  |

## Exemples

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Voir aussi

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

Enchaîner une matrice de transformation d'échelle

```csharp
public TransformBuilder Scale(double x, double y, double z)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| x | Double |  |
| y | Double |  |
| z | Double |  |

## Exemples

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10, 10, 10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Voir aussi

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(Vector3) {#scale}

Enchaîner une transformation d'échelle

```csharp
public TransformBuilder Scale(Vector3 s)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| s | Vector3 |  |

## Exemples

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(new Vector3(10, 10, 10));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Voir aussi

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


