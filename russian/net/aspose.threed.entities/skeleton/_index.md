---
title: "Класс Skeleton"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.Skeleton. Skeleton в основном используется CAD‑программами, чтобы помочь дизайнеру управлять преобразованием скелетной структуры; обычно он бесполезен вне CAD‑программ. Чтобы иерархия скелета вела себя как один объект в CAD‑программе, необходимо пометить верхний узел Skeleton как корневой, установив Type в значение Skeleton, а все дочерние узлы — в Bone."
type: docs
weight: 710
url: /ru/net/aspose.threed.entities/skeleton/
---
## Skeleton class

`Skeleton` в основном используется CAD‑программами, чтобы помочь дизайнеру управлять преобразованием скелетной структуры; обычно он бесполезен вне CAD‑программ. Чтобы иерархия скелета вела себя как один объект в CAD‑программе, необходимо пометить верхний узел `Skeleton` как корневой, установив [`Type`](./type/) в значение Skeleton, а все дочерние узлы — в Bone.

```csharp
public class Skeleton : Entity
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Skeleton](skeleton/#constructor)() | Инициализирует новый экземпляр класса `Skeleton`. |
| [Skeleton](skeleton/#constructor_1)(string) | Инициализирует новый экземпляр класса `Skeleton`. |
| [Skeleton](skeleton/#constructor_2)(string, SkeletonType) | Инициализирует новый экземпляр класса `Skeleton`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Size](../../aspose.threed.entities/skeleton/size/) { get; set; } | Получает или задает размер узла конечности, используемый в CAD‑программном обеспечении для представления размера кости. |
| [Type](../../aspose.threed.entities/skeleton/type/) { get; set; } | Получает или задает тип скелета. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


