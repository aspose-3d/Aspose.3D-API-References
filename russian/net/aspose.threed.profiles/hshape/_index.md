---
title: "Класс HShape"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Profiles.HShape. HShape предоставляет определяющие параметры формы H или I"
type: docs
weight: 1730
url: /ru/net/aspose.threed.profiles/hshape/
---
## HShape class

`HShape` предоставляет определяющие параметры формы 'H' или 'I'.

```csharp
public class HShape : ParameterizedProfile
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HShape](hshape/)() | Конструктор `HShape` |

## Свойства

| Имя | Описание |
| --- | --- |
| [BottomFlangeEdgeRadius](../../aspose.threed.profiles/hshape/bottomflangeedgeradius/) { get; set; } | Получает или задает радиус верхних кромок нижнего фланца. |
| [BottomFlangeFilletRadius](../../aspose.threed.profiles/hshape/bottomflangefilletradius/) { get; set; } | Получает или задает радиус скругления между стенкой и нижней кромкой. |
| [BottomFlangeThickness](../../aspose.threed.profiles/hshape/bottomflangethickness/) { get; set; } | Получает или задает толщину фланца H-образной формы. |
| [BottomFlangeWidth](../../aspose.threed.profiles/hshape/bottomflangewidth/) { get; set; } | Получает или задает размер ширины. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [OverallDepth](../../aspose.threed.profiles/hshape/overalldepth/) { get; set; } | Получает или задает размер глубины. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [TopFlangeEdgeRadius](../../aspose.threed.profiles/hshape/topflangeedgeradius/) { get; set; } | Получает или задает радиус нижних кромок верхнего фланца. |
| [TopFlangeFilletRadius](../../aspose.threed.profiles/hshape/topflangefilletradius/) { get; set; } | Получает или задает радиус скругления между стенкой и верхним фланцем. |
| [TopFlangeThickness](../../aspose.threed.profiles/hshape/topflangethickness/) { get; set; } | Получает или задает толщину верхнего фланца. |
| [TopFlangeWidth](../../aspose.threed.profiles/hshape/topflangewidth/) { get; set; } | Получает или задает ширину верхнего фланца. |
| [WebThickness](../../aspose.threed.profiles/hshape/webthickness/) { get; set; } | Получает или задает толщину стенки H-образной формы. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| override [GetExtent](../../aspose.threed.profiles/hshape/getextent/)() | Получает размеры в измерениях x и y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


