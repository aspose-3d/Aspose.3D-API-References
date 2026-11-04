---
title: "Класс Discreet3dsSaveOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.Discreet3dsSaveOptions. Параметры сохранения для файлов 3DS"
type: docs
weight: 1130
url: /ru/net/aspose.threed.formats/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Параметры сохранения для файла 3DS.

```csharp
public class Discreet3dsSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Discreet3dsSaveOptions](discreet3dssaveoptions/)() | Конструктор `Discreet3dsSaveOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [DuplicatedNameCounterBase](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterbase/) { get; set; } | Счётчик, используемый для генерации новых имён при дублировании, значение по умолчанию — 2. |
| [DuplicatedNameCounterFormat](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterformat/) { get; set; } | Формат счётчика дублирования, значение по умолчанию — пустая строка. |
| [DuplicatedNameSeparator](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednameseparator/) { get; set; } | Разделитель между именем объекта и счётчиком дублирования, значение по умолчанию — "_". Когда сцена содержит объекты с одинаковым именем, экспортер Aspose.3D 3DS генерирует другое имя для объекта. Например, есть два узла с именем "Box": первый узел будет иметь имя "Box", а второй получит новое имя "Box_2" при использовании конфигурации по умолчанию. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [ExportCamera](../../aspose.threed.formats/discreet3dssaveoptions/exportcamera/) { get; set; } | Получает или задает, экспортировать ли все камеры в сцене. |
| [ExportLight](../../aspose.threed.formats/discreet3dssaveoptions/exportlight/) { get; set; } | Получает или задает, экспортировать ли все источники света в сцене. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Пробовать копировать текстуры, используемые в сцене, в выходной каталог. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dssaveoptions/flipcoordinatesystem/) { get; set; } | Получает или задает инверсию системы координат контрольных точек/нормалей при импорте/экспорте. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dssaveoptions/gammacorrectedcolor/) { get; set; } | Файл 3ds может содержать оригинальный цвет и цвет с гамма‑коррекцией для одного и того же атрибута; установка этого параметра в true заставит использовать цвет с гамма‑коррекцией, если это возможно, иначе Aspose.3D попытается использовать оригинальный цвет. |
| [HighPreciseColor](../../aspose.threed.formats/discreet3dssaveoptions/highprecisecolor/) { get; set; } | Если параметр установлен в true, сгенерированный файл 3ds будет использовать высокоточный цвет, то есть каждый канал красного/зелёного/синего будет представлен 32‑битным float. В противном случае файл будет использовать 24‑битный цвет, каждый канал — 8‑битный байт. Значение по умолчанию — false, поскольку не все приложения поддерживают высокоточный цвет. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [MasterScale](../../aspose.threed.formats/discreet3dssaveoptions/masterscale/) { get; set; } | Получает или задает основной масштаб, используемый при экспорте. |

### См. также

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


