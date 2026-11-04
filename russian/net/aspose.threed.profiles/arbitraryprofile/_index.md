---
title: "Класс ArbitraryProfile"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Profiles.ArbitraryProfile класс. Этот класс позволяет создавать 2D профиль напрямую из произвольной кривой"
type: docs
weight: 1670
url: /ru/net/aspose.threed.profiles/arbitraryprofile/
---
## ArbitraryProfile class

Этот класс позволяет напрямую создавать 2D‑профиль из произвольной кривой.

```csharp
public class ArbitraryProfile : Profile
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ArbitraryProfile](arbitraryprofile/#constructor)() | Конструктор `ArbitraryProfile` |
| [ArbitraryProfile](arbitraryprofile/#constructor_1)(Curve) | Конструктор `ArbitraryProfile` с начальной кривой. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Curve](../../aspose.threed.profiles/arbitraryprofile/curve/) { get; set; } | Кривая, используемая для построения профиля |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [Holes](../../aspose.threed.profiles/arbitraryprofile/holes/) { get; } | Отверстия профиля, также представленные в виде кривой |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


