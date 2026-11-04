---
title: "Класс Texture"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Shading.Texture. Этот класс определяет текстуру из внешнего файла"
type: docs
weight: 2600
url: /ru/net/aspose.threed.shading/texture/
---
## Texture class

Этот класс определяет текстуру из внешнего файла.

```csharp
public class Texture : TextureBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Texture](texture/#constructor)() | Инициализирует новый экземпляр класса `Texture`. |
| [Texture](texture/#constructor_1)(string) | Инициализирует новый экземпляр класса `Texture`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Alpha](../../aspose.threed.shading/texturebase/alpha/) { get; set; } | Получает или задает значение альфа по умолчанию для текстуры. Это актуально, когда [`AlphaSource`](../texturebase/alphasource/) установлен в PixelAlpha. Значение по умолчанию — 1.0, допустимый диапазон — от 0 до 1. |
| [AlphaSource](../../aspose.threed.shading/texturebase/alphasource/) { get; set; } | Получает или задает, определяет ли текстура альфа‑канал. Значение по умолчанию — None. |
| [Content](../../aspose.threed.shading/texture/content/) { get; set; } | Получает или задает двоичное содержимое текстуры. Встроенное содержимое текстуры является необязательным; при его отсутствии пользователь должен загрузить текстуру из внешнего файла. |
| [EnableMipMap](../../aspose.threed.shading/texture/enablemipmap/) { get; set; } | Получает или задает, включён ли mipmap для этой текстуры. |
| [FileName](../../aspose.threed.shading/texture/filename/) { get; set; } | Получает или задает связанный файл текстуры. |
| [MagFilter](../../aspose.threed.shading/texturebase/magfilter/) { get; set; } | Получает или задает фильтр для увеличения. |
| [MinFilter](../../aspose.threed.shading/texturebase/minfilter/) { get; set; } | Получает или задает фильтр для минификации. |
| [MipFilter](../../aspose.threed.shading/texturebase/mipfilter/) { get; set; } | Получает или задает фильтр для выборки уровней mip. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [UVRotation](../../aspose.threed.shading/texturebase/uvrotation/) { get; set; } | Получает или задает вращение текстуры |
| [UVScale](../../aspose.threed.shading/texturebase/uvscale/) { get; set; } | Получает или задает масштаб UV. |
| [UVTranslation](../../aspose.threed.shading/texturebase/uvtranslation/) { get; set; } | Получает или задает трансляцию UV. |
| [WrapModeU](../../aspose.threed.shading/texturebase/wrapmodeu/) { get; set; } | Получает или задает режимы обертки текстуры по оси U. |
| [WrapModeV](../../aspose.threed.shading/texturebase/wrapmodev/) { get; set; } | Получает или задает режимы обертки текстуры по оси V. |
| [WrapModeW](../../aspose.threed.shading/texturebase/wrapmodew/) { get; set; } | Получает или задает режимы обертки текстуры по оси W. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |
| [SetRotation](../../aspose.threed.shading/texturebase/setrotation/)(double, double) | Задает вращение UV. |
| [SetScale](../../aspose.threed.shading/texturebase/setscale/)(double, double) | Задает масштаб UV. |
| [SetTranslation](../../aspose.threed.shading/texturebase/settranslation/)(double, double) | Задает трансляцию UV. |

### См. также

* class [TextureBase](../texturebase/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


