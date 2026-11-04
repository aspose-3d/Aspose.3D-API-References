---
title: "Transform.TransformMatrix"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Transform. Возвращает или задает матрицу преобразования"
type: docs
weight: 130
url: /ru/net/aspose.threed/transform/transformmatrix/
---
## Transform.TransformMatrix property

Получает или задает матрицу трансформации.

```csharp
public Matrix4 TransformMatrix { get; set; }
```

## Примечания

Назначение на этом сбросит [`Translation`](../translation/), [`Scaling`](../scaling/) и [`Rotation`](../rotation/), а [`GeometricRotation`](../geometricrotation/), [`GeometricScaling`](../geometricscaling/) и [`GeometricTranslation`](../geometrictranslation/) не будут затронуты.

## Примеры

```csharp
Node node = new Node();
node.Transform.TransformMatrix = Matrix4.Identity;
```

### См. также

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


