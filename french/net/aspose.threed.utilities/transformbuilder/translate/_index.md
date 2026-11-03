---
title: "TransformBuilder.Translate"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode TransformBuilder. Enchaîner une transformation de translation"
type: docs
weight: 150
url: /fr/net/aspose.threed.utilities/transformbuilder/translate/
---
## Translate(double, double, double) {#translate_1}

Enchaîner une transformation de translation

```csharp
public TransformBuilder Translate(double tx, double ty, double tz)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| tx | Double |  |
| ty | Double |  |
| tz | Double |  |

## Exemples

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(0, 10, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Voir aussi

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Translate(Vector3) {#translate}

Enchaîner une transformation de translation

```csharp
public TransformBuilder Translate(Vector3 v)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| v | Vector3 |  |

## Exemples

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(new Vector3(0, 10, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Voir aussi

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


