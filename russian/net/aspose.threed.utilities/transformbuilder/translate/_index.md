---
title: "TransformBuilder.Translate"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод TransformBuilder. Добавить трансляцию в цепочку преобразований"
type: docs
weight: 150
url: /ru/net/aspose.threed.utilities/transformbuilder/translate/
---
## Translate(double, double, double) {#translate_1}

Сцепить преобразование переноса

```csharp
public TransformBuilder Translate(double tx, double ty, double tz)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| tx | Double |  |
| ty | Double |  |
| tz | Double |  |

## Примеры

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(0, 10, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### См. также

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Translate(Vector3) {#translate}

Сцепить преобразование переноса

```csharp
public TransformBuilder Translate(Vector3 v)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| v | Vector3 |  |

## Примеры

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(new Vector3(0, 10, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### См. также

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


