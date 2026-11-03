---
title: "TransformBuilder.Translate"
second_title: "Aspose.3D für .NET API-Referenz"
description: "TransformBuilder-Methode. Verkette eine Translations-Transformation"
type: docs
weight: 150
url: /de/net/aspose.threed.utilities/transformbuilder/translate/
---
## Translate(double, double, double) {#translate_1}

Verkette eine Translations-Transformation.

```csharp
public TransformBuilder Translate(double tx, double ty, double tz)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tx | Double |  |
| ty | Double |  |
| tz | Double |  |

## Beispiele

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(0, 10, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Siehe auch

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Translate(Vector3) {#translate}

Verkette eine Translations-Transformation.

```csharp
public TransformBuilder Translate(Vector3 v)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| v | Vector3 |  |

## Beispiele

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(new Vector3(0, 10, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Siehe auch

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


