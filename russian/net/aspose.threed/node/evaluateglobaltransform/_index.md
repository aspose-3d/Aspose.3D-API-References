---
title: "Node.EvaluateGlobalTransform"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Node. Оценивает глобальное преобразование, включая геометрическое преобразование или нет."
type: docs
weight: 180
url: /ru/net/aspose.threed/node/evaluateglobaltransform/
---
## Node.EvaluateGlobalTransform method

Вычислить глобальное преобразование, включать геометрическое преобразование или нет.

```csharp
public Matrix4 EvaluateGlobalTransform(bool withGeometricTransform)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| withGeometricTransform | Boolean | Нужна ли геометрическая трансформация. |

### Возвращаемое значение

Глобальная матрица трансформации.

## Примеры

Следующий код показывает, как прочитать глобальную матрицу трансформации узла.

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//разместите коробку в (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
Matrix4 mat = boxNode.EvaluateGlobalTransform(true);
Console.WriteLine($"The box's global transform matrix is {mat}");
```

### См. также

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


