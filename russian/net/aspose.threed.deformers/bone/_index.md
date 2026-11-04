---
title: "Класс Bone"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Deformers.Bone class. Кость определяет подмножество контрольных точек геометрии и задаёт вес смешивания для каждой контрольной точки. Объект Bone нельзя использовать напрямую; экземпляр SkinDeformer используется для деформации геометрии, и SkinDeformer поставляется с набором костей, каждая кость связана с узлом. ПРИМЕЧАНИЕ: контрольная точка геометрии может быть привязана к более чем одной кости."
type: docs
weight: 190
url: /ru/net/aspose.threed.deformers/bone/
---
## Bone class

Кость определяет подмножество контрольных точек геометрии и задаёт вес смешивания для каждой контрольной точки. Объект `Bone` нельзя использовать напрямую, экземпляр [`SkinDeformer`](../skindeformer/) используется для деформации геометрии, и [`SkinDeformer`](../skindeformer/) поставляется с набором костей, каждая кость связана с узлом. ПРИМЕЧАНИЕ: контрольная точка геометрии может быть привязана к более чем одной кости.

```csharp
public class Bone : A3DObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Bone](bone/#constructor)() | Инициализирует новый экземпляр класса `Bone`. |
| [Bone](bone/#constructor_1)(string) | Инициализирует новый экземпляр класса `Bone`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BoneTransform](../../aspose.threed.deformers/bone/bonetransform/) { get; set; } | Получает или задает матрицу преобразования кости. |
| [Item](../../aspose.threed.deformers/bone/item/) { get; set; } |  |
| [LinkMode](../../aspose.threed.deformers/bone/linkmode/) { get; set; } | Режим соединения кости относится к способу, которым кость соединяется или связывается с родительской костью в иерархической структуре. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Node](../../aspose.threed.deformers/bone/node/) { get; set; } | Получает или задает узел. Узел кости — это кость, к которой прикреплена кожа; [`SkinDeformer`](../skindeformer/) будет использовать узел кости для влияния на смещение контрольных точек. Обычно узел кости имеет прикреплённый [`Skeleton`](../../aspose.threed.entities/skeleton/), но это не обязательно. Прикреплённый [`Skeleton`](../../aspose.threed.entities/skeleton/) обычно используется программным обеспечением DCC для отображения скелета пользователю. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Transform](../../aspose.threed.deformers/bone/transform/) { get; set; } | Получает или задает матрицу преобразования узла, содержащего кость. |
| [WeightCount](../../aspose.threed.deformers/bone/weightcount/) { get; } | Получает количество весов, которое автоматически расширяется с помощью [`SetWeight`](./setweight/) |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [GetWeight](../../aspose.threed.deformers/bone/getweight/)(int) | Получает вес для контрольной точки, указанной по индексу |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |
| [SetWeight](../../aspose.threed.deformers/bone/setweight/)(int, double) | Устанавливает вес для контрольной точки, указанной по индексу |

### См. также

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


