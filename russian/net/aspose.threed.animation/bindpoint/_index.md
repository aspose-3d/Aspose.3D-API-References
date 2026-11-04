---
title: "Класс BindPoint"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Animation.BindPoint класс. BindPoint обычно создаётся на свойстве объекта; некоторые типы свойств содержат несколько полей‑компонентов, например поле Vector3. BindPoint создаст канал для каждого поля‑компонента и соединит поле с одной или несколькими последовательностями ключевых кадров через каналы."
type: docs
weight: 50
url: /ru/net/aspose.threed.animation/bindpoint/
---
## BindPoint class

`BindPoint` обычно создаётся на свойстве объекта, некоторые типы свойств содержат несколько полей‑компонентов (например поле Vector3), `BindPoint` создаст канал для каждого поля‑компонента и соединит поле с одной или несколькими экземплярами последовательности ключевых кадров через каналы.

```csharp
public class BindPoint : A3DObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BindPoint](bindpoint/)(Scene, Property) | Инициализирует новый экземпляр класса `BindPoint`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ChannelsCount](../../aspose.threed.animation/bindpoint/channelscount/) { get; } | Получает общее количество каналов свойства, определённых в этом отображении анимационной кривой. |
| [Item](../../aspose.threed.animation/bindpoint/item/) { get; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Property](../../aspose.threed.animation/bindpoint/property/) { get; } | Получает свойство, связанное с CurveMapping |

## Методы

| Имя | Описание |
| --- | --- |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel)(string, object) | Добавляет указанный канал свойства. |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_1)(string, Type, object) | Добавляет указанный канал свойства. |
| [AddChannel&lt;T&gt;](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_2)(string, T) |  |
| [BindKeyframeSequence](../../aspose.threed.animation/bindpoint/bindkeyframesequence/)(string, KeyframeSequence) | Привязывает последовательность ключевых кадров к указанному каналу |
| [CreateKeyframeSequence](../../aspose.threed.animation/bindpoint/createkeyframesequence/)(string) | Создаёт новую кривую и соединяет её с первым каналом отображения кривой |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetChannel](../../aspose.threed.animation/bindpoint/getchannel/)(string) | Получает канал по заданному имени |
| [GetKeyframeSequence](../../aspose.threed.animation/bindpoint/getkeyframesequence/)(string) | Получает первую последовательность ключевых кадров в указанном канале |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [ResetChannels](../../aspose.threed.animation/bindpoint/resetchannels/)() | Очищает каналы свойства этого отображения анимационной кривой. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |
| override [ToString](../../aspose.threed.animation/bindpoint/tostring/)() | Преобразует объект в строку |

### См. также

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


