---
title: "Класс AnimationNode"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Animation.AnimationNode. Aspose.3Ds поддерживает иерархию анимации, каждая анимация может состоять из нескольких анимаций и определения ключевых кадров анимации. AnimationNode определяет трансформацию значения свойства во времени, например, узел анимации может использоваться для управления трансформацией узла или другими числовыми свойствами объектов A3DObject."
type: docs
weight: 40
url: /ru/net/aspose.threed.animation/animationnode/
---
## AnimationNode class

Aspose.3D поддерживает иерархию анимации, каждая анимация может состоять из нескольких анимаций и определения ключевых кадров анимации. `AnimationNode` определяет трансформацию значения свойства во времени, например, узел анимации может использоваться для управления трансформацией узла или другими числовыми свойствами объекта [`A3DObject`](../../aspose.threed/a3dobject/).

```csharp
public class AnimationNode : A3DObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AnimationNode](animationnode/#constructor)() | Инициализирует новый экземпляр класса `AnimationNode`. |
| [AnimationNode](animationnode/#constructor_1)(string) | Инициализирует новый экземпляр класса `AnimationNode`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BindPoints](../../aspose.threed.animation/animationnode/bindpoints/) { get; } | Получает текущие точки привязки свойства |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [SubAnimations](../../aspose.threed.animation/animationnode/subanimations/) { get; } | Получает подузлы анимации внутри текущих анимаций |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateBindPoint](../../aspose.threed.animation/animationnode/createbindpoint/)(A3DObject, string) | Создаёт BindPoint на основе типа данных свойства. |
| [FindBindPoint](../../aspose.threed.animation/animationnode/findbindpoint/)(A3DObject, string) | Находит точку привязки по цели и имени. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBindPoint](../../aspose.threed.animation/animationnode/getbindpoint/)(A3DObject, string, bool) | Получает точку привязки анимации для указанного свойства. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence)(A3DObject, string, bool) | Получает последовательность ключевых кадров для указанного свойства. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence_1)(A3DObject, string, string, bool) | Получает последовательность ключевых кадров для указанного свойства и канала. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


