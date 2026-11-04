---
title: "Класс SceneObject"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.SceneObject class. Корневой класс объектов, которые будут храниться внутри сцены"
type: docs
weight: 2510
url: /ru/net/aspose.threed/sceneobject/
---
## SceneObject class

Корневой класс объектов, которые будут храниться внутри сцены.

```csharp
public abstract class SceneObject : A3DObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SceneObject](sceneobject/#constructor)() | Инициализировать объект SceneObject. |
| [SceneObject](sceneobject/#constructor_1)(string) | Инициализировать объект SceneObject с именем по умолчанию |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


