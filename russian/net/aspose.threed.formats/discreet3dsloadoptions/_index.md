---
title: "Класс Discreet3dsLoadOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.Discreet3dsLoadOptions. Параметры загрузки для файла 3DS"
type: docs
weight: 1120
url: /ru/net/aspose.threed.formats/discreet3dsloadoptions/
---
## Discreet3dsLoadOptions class

Параметры загрузки для файла 3DS.

```csharp
public class Discreet3dsLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Discreet3dsLoadOptions](discreet3dsloadoptions/)() | Конструктор `Discreet3dsLoadOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [ApplyAnimationTransform](../../aspose.threed.formats/discreet3dsloadoptions/applyanimationtransform/) { get; set; } | Получает или задает, использовать ли трансформацию, определённую в первом кадре анимационной дорожки. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dsloadoptions/flipcoordinatesystem/) { get; set; } | Получает или задает инверсию системы координат контрольных точек/нормалей при импорте/экспорте. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dsloadoptions/gammacorrectedcolor/) { get; set; } | Файл 3ds может содержать оригинальный цвет и цвет с гамма‑коррекцией для одного и того же атрибута; установка этого параметра в true заставит использовать цвет с гамма‑коррекцией, если это возможно, иначе Aspose.3D попытается использовать оригинальный цвет. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


