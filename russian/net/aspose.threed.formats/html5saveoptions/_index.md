---
title: "Класс Html5SaveOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.Html5SaveOptions. Параметры сохранения для HTML5"
type: docs
weight: 1290
url: /ru/net/aspose.threed.formats/html5saveoptions/
---
## Html5SaveOptions class

Параметры сохранения для HTML5

```csharp
public class Html5SaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Html5SaveOptions](html5saveoptions/)() | Конструктор `Html5SaveOptions` со всеми настройками по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CameraPosition](../../aspose.threed.formats/html5saveoptions/cameraposition/) { get; set; } | Получает или задает начальную позицию камеры, значение по умолчанию (10, 10, 10) |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Пробовать копировать текстуры, используемые в сцене, в выходной каталог. |
| [FarPlane](../../aspose.threed.formats/html5saveoptions/farplane/) { get; set; } | Получает или задает дальнюю плоскость камеры, значение по умолчанию 1000. |
| [FieldOfView](../../aspose.threed.formats/html5saveoptions/fieldofview/) { get; set; } | Получает или задает поле зрения, значение по умолчанию 45, измеряется в градусах. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [LookAt](../../aspose.threed.formats/html5saveoptions/lookat/) { get; set; } | Получает или задает позицию взгляда по умолчанию, значение по умолчанию (0, 0, 0) |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [NearPlane](../../aspose.threed.formats/html5saveoptions/nearplane/) { get; set; } | Получает или задает ближнюю плоскость камеры, значение по умолчанию 1 |
| [OrientationBox](../../aspose.threed.formats/html5saveoptions/orientationbox/) { get; set; } | Отображать коробку ориентации. Значение по умолчанию true. |
| [ShowGrid](../../aspose.threed.formats/html5saveoptions/showgrid/) { get; set; } | Отображать сетку в сцене. Значение по умолчанию true. |
| [ShowRulers](../../aspose.threed.formats/html5saveoptions/showrulers/) { get; set; } | Отображать линейки осей x/y/z в сцене для измерения модели. Значение по умолчанию false. |
| [ShowUI](../../aspose.threed.formats/html5saveoptions/showui/) { get; set; } | Отображать простой интерфейс в сцене. Значение по умолчанию true. |
| [UpVector](../../aspose.threed.formats/html5saveoptions/upvector/) { get; set; } | Получает или задает вектор вверх, значение может быть "x"/"y"/"z", значение по умолчанию "y" |

### См. также

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


