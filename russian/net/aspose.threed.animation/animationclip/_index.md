---
title: "Класс AnimationClip"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Animation.AnimationClip класс. Анимационный клип представляет собой набор анимаций. Сцена может содержать один или несколько анимационных клипов."
type: docs
weight: 30
url: /ru/net/aspose.threed.animation/animationclip/
---
## AnimationClip class

Клип анимации — это набор анимаций. Сцена может содержать один или несколько клипов анимации.

```csharp
public class AnimationClip : SceneObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AnimationClip](animationclip/#constructor)() | Инициализирует новый экземпляр класса `AnimationClip`. |
| [AnimationClip](animationclip/#constructor_1)(string) | Инициализирует новый экземпляр класса `AnimationClip`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Animations](../../aspose.threed.animation/animationclip/animations/) { get; } | Получает анимации, содержащиеся в клипе. |
| [Description](../../aspose.threed.animation/animationclip/description/) { get; set; } | Получает или задаёт описание этого анимационного клипа |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Start](../../aspose.threed.animation/animationclip/start/) { get; set; } | Получает или задаёт время в секундах начала клипа. |
| [Stop](../../aspose.threed.animation/animationclip/stop/) { get; set; } | Получает или задаёт время в секундах окончания клипа. |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateAnimationNode](../../aspose.threed.animation/animationclip/createanimationnode/)(string) | Краткая функция для создания и регистрации узла анимации в текущем клипе. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [SceneObject](../../aspose.threed/sceneobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


