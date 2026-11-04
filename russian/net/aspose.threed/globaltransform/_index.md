---
title: "Класс GlobalTransform"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.GlobalTransform. Глобальное преобразование аналогично Transform, но оно неизменяемо, поскольку представляет окончательно вычисленное преобразование. При вычислении глобального преобразования используется правосторонняя система координат"
type: docs
weight: 1560
url: /ru/net/aspose.threed/globaltransform/
---
## GlobalTransform class

Глобальное преобразование аналогично [`Transform`](../transform/), но оно неизменяемо, поскольку представляет окончательно вычисленное преобразование. При вычислении глобального преобразования используется правосторонняя система координат

```csharp
public class GlobalTransform
```

## Свойства

| Имя | Описание |
| --- | --- |
| [EulerAngles](../../aspose.threed/globaltransform/eulerangles/) { get; } | Получает вращение, представленное в углах Эйлера, измеряемое в градусах |
| [Rotation](../../aspose.threed/globaltransform/rotation/) { get; } | Получает вращение, представленное кватернионом. |
| [Scale](../../aspose.threed/globaltransform/scale/) { get; } | Получает масштаб |
| [TransformMatrix](../../aspose.threed/globaltransform/transformmatrix/) { get; } | Получает матрицу преобразования. |
| [Translation](../../aspose.threed/globaltransform/translation/) { get; } | Получает трансляцию |

## Примеры

Следующий код показывает, как прочитать глобальное преобразование узла

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//разместите коробку в (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### См. также

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


