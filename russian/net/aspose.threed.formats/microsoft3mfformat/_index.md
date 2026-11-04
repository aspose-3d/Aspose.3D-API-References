---
title: "Класс Microsoft3MFFormat"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.Microsoft3MFFormat. Экземпляр формата файла для Microsoft 3MF с утилитами, связанными с 3MF"
type: docs
weight: 1340
url: /ru/net/aspose.threed.formats/microsoft3mfformat/
---
## Microsoft3MFFormat class

Экземпляр формата файла для Microsoft 3MF с утилитами, связанными с 3MF.

```csharp
public class Microsoft3MFFormat : FileFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | Получает, поддерживает ли Aspose.3D экспорт сцены в текущий формат файла. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | Получает, поддерживает ли Aspose.3D импорт сцены из текущего формата файла. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | Получает тип содержимого формата файла |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | Получает имя расширения этого типа. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | Получает имена расширений этого типа. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | Получает тип формата файла |
| [Version](../../aspose.threed/fileformat/version/) { get; } | Получает версию формата файла |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | Создаёт параметры загрузки по умолчанию для этого формата файла |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | Создаёт параметры сохранения по умолчанию для этого формата файла |
| [GetObjectType](../../aspose.threed.formats/microsoft3mfformat/getobjecttype/)(Node) | Получает тип модели для указанного узла. |
| [GetTransformForBuild](../../aspose.threed.formats/microsoft3mfformat/gettransformforbuild/)(Node) | Получить матрицу преобразования для узла, используемого в сборке. |
| [IsBuildable](../../aspose.threed.formats/microsoft3mfformat/isbuildable/)(Node) | Проверить, помечен ли этот узел как сборочный. |
| [SetBuildable](../../aspose.threed.formats/microsoft3mfformat/setbuildable/)(Node, bool, Matrix4?) |  |
| [SetObjectType](../../aspose.threed.formats/microsoft3mfformat/setobjecttype/)(Node, string) | Устанавливает тип модели для указанного узла. Возможные значения: model, surface, solidsupport, support, other |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Преобразует форматы в строку |

### См. также

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


