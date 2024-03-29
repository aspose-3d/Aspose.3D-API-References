---
title: SkinDeformer
second_title: Справочник по Aspose.3D для .NET API
description: Деформатор кожи содержит несколько костей для работы каждая кость смешивает часть геометрии с помощью веса контрольной точки.
type: docs
weight: 220
url: /ru/net/aspose.threed.deformers/skindeformer/
---
## SkinDeformer class

Деформатор кожи содержит несколько костей для работы, каждая кость смешивает часть геометрии с помощью веса контрольной точки.

```csharp
public class SkinDeformer : Deformer
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SkinDeformer](skindeformer#constructor)() | Инициализирует новый экземпляр[`SkinDeformer`](../skindeformer) класс. |
| [SkinDeformer](skindeformer#constructor_1)(string) | Инициализирует новый экземпляр[`SkinDeformer`](../skindeformer) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bones](../../aspose.threed.deformers/skindeformer/bones) { get; } | Получает все кости, которые содержит деформатор кожи |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Получает или задает имя. |
| [Owner](../../aspose.threed.deformers/deformer/owner) { get; } | Получает геометрию, которой принадлежит этот деформатор |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Получает коллекцию всех свойств. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Находит свойство. Это может быть динамическое свойство (созданное CreateDynamicProperty/SetProperty) или родное свойство (идентифицированное по имени) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Удалить указанное свойство с именем name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Устанавливает значение указанного свойства |

### Смотрите также

* class [Deformer](../deformer)
* пространство имен [Aspose.ThreeD.Deformers](../../aspose.threed.deformers)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
