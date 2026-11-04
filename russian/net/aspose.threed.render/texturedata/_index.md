---
title: "Класс TextureData"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Render.TextureData. Этот класс содержит необработанные данные и определение формата текстуры."
type: docs
weight: 2460
url: /ru/net/aspose.threed.render/texturedata/
---
## TextureData class

Этот класс содержит необработанные данные и определение формата текстуры.

```csharp
public class TextureData : A3DObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextureData](texturedata/#constructor)() | Конструктор `TextureData` |
| [TextureData](texturedata/#constructor_1)(int, int, PixelFormat) | Создаёт новый `TextureData` и выделяет данные пикселей. |
| [TextureData](texturedata/#constructor_2)(int, int, int, int, PixelFormat, byte[]) | Конструктор `TextureData` |

## Свойства

| Имя | Описание |
| --- | --- |
| [BytesPerPixel](../../aspose.threed.render/texturedata/bytesperpixel/) { get; } | Количество байтов в пикселе |
| [Data](../../aspose.threed.render/texturedata/data/) { get; } | Необработанные байты данных пикселя |
| [Height](../../aspose.threed.render/texturedata/height/) { get; } | Количество вертикальных пикселей |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [PixelFormat](../../aspose.threed.render/texturedata/pixelformat/) { get; } | Формат пикселя |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Stride](../../aspose.threed.render/texturedata/stride/) { get; } | Количество байтов в строке сканирования. |
| [Width](../../aspose.threed.render/texturedata/width/) { get; } | Количество горизонтальных пикселей |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromFile](../../aspose.threed.render/texturedata/fromfile/)(string) | Загрузить текстуру из файла |
| static [FromStream](../../aspose.threed.render/texturedata/fromstream/)(Stream) | Загрузить текстуру из потока |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels)(PixelMapMode) | Отобразить все пиксели для чтения/записи |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_1)(PixelMapMode, PixelFormat) | Отобразить все пиксели для чтения/записи в заданном формате пикселя |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_2)(Rect, PixelMapMode, PixelFormat) | Отобразить пиксели, определённые прямоугольником, для чтения/записи в заданном формате пикселя |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [Save](../../aspose.threed.render/texturedata/save/#save_1)(string) | Сохранить данные текстуры в файл изображения |
| [Save](../../aspose.threed.render/texturedata/save/#save)(Stream, string) | Сохранить данные текстуры в указанный формат изображения |
| [Save](../../aspose.threed.render/texturedata/save/#save_2)(string, string) | Сохранить данные текстуры в файл изображения |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |
| [TransformPixelFormat](../../aspose.threed.render/texturedata/transformpixelformat/)(PixelFormat) | Преобразовать расположение пикселя в новый формат пикселя. |

### См. также

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


