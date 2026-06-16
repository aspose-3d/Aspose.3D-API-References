---
title: "TransformBuilder.Translate"
second_title: "Aspose.3D for .NET API 参考"
description: "TransformBuilder 方法。链式平移变换"
type: docs
weight: 150
url: /zh/net/aspose.threed.utilities/transformbuilder/translate/
---
## Translate(double, double, double) {#translate_1}

链接平移变换

```csharp
public TransformBuilder Translate(double tx, double ty, double tz)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tx | Double |  |
| ty | Double |  |
| tz | Double |  |

## 示例

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(0, 10, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### 另请参见

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Translate(Vector3) {#translate}

链接平移变换

```csharp
public TransformBuilder Translate(Vector3 v)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v | Vector3 |  |

## 示例

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(new Vector3(0, 10, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### 另请参见

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


