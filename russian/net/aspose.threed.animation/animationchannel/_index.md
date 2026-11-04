---
title: "Класс AnimationChannel"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Animation.AnimationChannel класс. Канал сопоставляет поле компонента свойства с набором последовательностей ключевых кадров"
type: docs
weight: 20
url: /ru/net/aspose.threed.animation/animationchannel/
---
## AnimationChannel class

Канал сопоставляет поле компонента свойства с набором последовательностей ключевых кадров

```csharp
public class AnimationChannel : KeyframeSequence
```

## Свойства

| Имя | Описание |
| --- | --- |
| [BindPoint](../../aspose.threed.animation/keyframesequence/bindpoint/) { get; } | Получает точку привязки свойства, которой принадлежит эта кривая |
| [ComponentType](../../aspose.threed.animation/animationchannel/componenttype/) { get; } | Получает тип поля компонента |
| [DefaultValue](../../aspose.threed.animation/animationchannel/defaultvalue/) { get; set; } | Получает или задает значение по умолчанию канала. Если у канала нет подключенных последовательностей ключевых кадров, значение по умолчанию будет использоваться при оценке анимации. Реальный пример: анимация изменяет только координату x узла, координаты y и z не меняются, тогда значение по умолчанию будет использовано при полной оценке трансляции. |
| [KeyFrames](../../aspose.threed.animation/keyframesequence/keyframes/) { get; } | Получает ключевые кадры этой кривой. |
| [KeyframeSequence](../../aspose.threed.animation/animationchannel/keyframesequence/) { get; set; } | Получает связанную последовательность ключевых кадров внутри этого канала |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [PostBehavior](../../aspose.threed.animation/keyframesequence/postbehavior/) { get; } | Получает пост‑поведение, указывающее, каким должно быть выборочное значение после последнего ключевого кадра. |
| [PreBehavior](../../aspose.threed.animation/keyframesequence/prebehavior/) { get; } | Получает пре‑поведение, указывающее, каким должно быть выборочное значение до первого ключа. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.threed.animation/keyframesequence/add/)(double, float) | Создать новый ключевой кадр с указанным значением |
| [Add](../../aspose.threed.animation/keyframesequence/add/)(double, float, Interpolation) | Создать новый ключевой кадр с указанным значением |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetEnumerator](../../aspose.threed.animation/keyframesequence/getenumerator/)() | Получает перечислитель для обхода всех ключевых кадров. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [Reset](../../aspose.threed.animation/keyframesequence/reset/)() | Удаляет все ключевые кадры и сбрасывает пост/пре‑поведения. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [KeyframeSequence](../keyframesequence/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


