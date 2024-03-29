---
title: SceneObject
second_title: Справочник по Aspose.3D для .NET API
description: Корневой класс объектов которые будут храниться внутри сцены.
type: docs
weight: 2260
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
| [SceneObject](sceneobject#constructor)() | Инициализировать объект сцены. |
| [SceneObject](sceneobject#constructor_1)(string) | Инициализировать объект сцены с именем по умолчанию |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Получает или задает имя. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Получает сцену, которой принадлежит этот объект |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Находит свойство. Это может быть динамическое свойство (созданное CreateDynamicProperty/SetProperty) или родное свойство (идентифицированное по имени) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Удалить указанное свойство с именем name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Устанавливает значение указанного свойства |

### Смотрите также

* class [A3DObject](../a3dobject)
* пространство имен [Aspose.ThreeD](../../aspose.threed)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
