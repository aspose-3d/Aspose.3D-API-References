---
title: "Класс FileFormat"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.FileFormat. Определение формата файла"
type: docs
weight: 1060
url: /ru/net/aspose.threed/fileformat/
---
## FileFormat class

Определение формата файла

```csharp
public class FileFormat
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
| static [Formats](../../aspose.threed/fileformat/formats/) { get; } | Доступ ко всем поддерживаемым форматам |

## Методы

| Имя | Описание |
| --- | --- |
| static [Detect](../../aspose.threed/fileformat/detect/#detect_1)(string) | Определить формат файла по имени файла, файл должен быть читаемым, чтобы Aspose.3D мог определить формат файла по заголовку. |
| static [Detect](../../aspose.threed/fileformat/detect/#detect)(Stream, string) | Определить формат файла из потока данных, имя файла необязательно для определения типов, у которых нет магического заголовка. |
| static [GetFormatByExtension](../../aspose.threed/fileformat/getformatbyextension/)(string) | Получает предпочтительный формат файла из имени расширения. Имя расширения должно начинаться с точки ('.'). |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | Создаёт параметры загрузки по умолчанию для этого формата файла |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | Создаёт параметры сохранения по умолчанию для этого формата файла |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Преобразует форматы в строку |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [AMF](../../aspose.threed/fileformat/amf/) | Формат файла аддитивного производства |
| static readonly [ASE](../../aspose.threed/fileformat/ase/) | Формат ASCII Scene Exporter программы 3D Studio Max. |
| static readonly [Aspose3DWeb](../../aspose.threed/fileformat/aspose3dweb/) | Веб-формат Aspose.3D. |
| static readonly [Blender](../../aspose.threed/fileformat/blender/) | 3D‑формат файла Blender |
| static readonly [Collada](../../aspose.threed/fileformat/collada/) | Формат файла Collada |
| static readonly [Discreet3DS](../../aspose.threed/fileformat/discreet3ds/) | Формат файла 3D Studio |
| static readonly [DXF](../../aspose.threed/fileformat/dxf/) | AutoCAD DXF |
| static readonly [FBX6100ASCII](../../aspose.threed/fileformat/fbx6100ascii/) | Формат файла ASCII FBX, с версией 6.1.0 |
| static readonly [FBX6100Binary](../../aspose.threed/fileformat/fbx6100binary/) | Формат файла Binary FBX, с версией 6.1.0 |
| static readonly [FBX7200ASCII](../../aspose.threed/fileformat/fbx7200ascii/) | Формат файла ASCII FBX, с версией 7.2.0 |
| static readonly [FBX7200Binary](../../aspose.threed/fileformat/fbx7200binary/) | Формат файла Binary FBX, с версией 7.2.0 |
| static readonly [FBX7300ASCII](../../aspose.threed/fileformat/fbx7300ascii/) | Формат файла ASCII FBX, с версией 7.3.0 |
| static readonly [FBX7300Binary](../../aspose.threed/fileformat/fbx7300binary/) | Формат файла Binary FBX, с версией 7.3.0 |
| static readonly [FBX7400ASCII](../../aspose.threed/fileformat/fbx7400ascii/) | Формат файла ASCII FBX, с версией 7.4.0 |
| static readonly [FBX7400Binary](../../aspose.threed/fileformat/fbx7400binary/) | Формат файла Binary FBX, с версией 7.4.0 |
| static readonly [FBX7500ASCII](../../aspose.threed/fileformat/fbx7500ascii/) | Формат файла ASCII FBX, с версией 7.5.0 |
| static readonly [FBX7500Binary](../../aspose.threed/fileformat/fbx7500binary/) | Формат файла Binary FBX, с версией 7.5.0 |
| static readonly [FBX7600ASCII](../../aspose.threed/fileformat/fbx7600ascii/) | Формат файла ASCII FBX, с версией 7.6.0 |
| static readonly [FBX7600Binary](../../aspose.threed/fileformat/fbx7600binary/) | Формат файла Binary FBX, с версией 7.6.0 |
| static readonly [FBX7700ASCII](../../aspose.threed/fileformat/fbx7700ascii/) | Формат файла ASCII FBX, с версией 7.7.0 |
| static readonly [FBX7700Binary](../../aspose.threed/fileformat/fbx7700binary/) | Формат файла Binary FBX, с версией 7.7.0 |
| static readonly [GLTF](../../aspose.threed/fileformat/gltf/) | glTF группы Khronos |
| static readonly [GLTF2](../../aspose.threed/fileformat/gltf2/) | glTF версии 2.0 группы Khronos |
| static readonly [GLTF2_Binary](../../aspose.threed/fileformat/gltf2_binary/) | glTF версии 2.0 группы Khronos |
| static readonly [GLTF_Binary](../../aspose.threed/fileformat/gltf_binary/) | glTF в бинарном формате группы Khronos |
| static readonly [HTML5](../../aspose.threed/fileformat/html5/) | Файл HTML5 |
| static readonly [IFC](../../aspose.threed/fileformat/ifc/) | Модель данных Industry Foundation Classes ISO 16739-1. |
| static readonly [MayaASCII](../../aspose.threed/fileformat/mayaascii/) | Autodesk Maya в ASCII-формате |
| static readonly [MayaBinary](../../aspose.threed/fileformat/mayabinary/) | Autodesk Maya в бинарном формате |
| static readonly [Pcd](../../aspose.threed/fileformat/pcd/) | Файл PCL Point Cloud Data в режиме ASCII |
| static readonly [PcdBinary](../../aspose.threed/fileformat/pcdbinary/) | Файл PCL Point Cloud Data в бинарном режиме |
| static readonly [SiemensJT8](../../aspose.threed/fileformat/siemensjt8/) | Файл Siemens JT версии 8 |
| static readonly [SiemensJT9](../../aspose.threed/fileformat/siemensjt9/) | Файл Siemens JT версии 9 |
| static readonly [STLASCII](../../aspose.threed/fileformat/stlascii/) | Формат файла ASCII STL |
| static readonly [STLBinary](../../aspose.threed/fileformat/stlbinary/) | Формат файла Binary STL |
| static readonly [Universal3D](../../aspose.threed/fileformat/universal3d/) | Формат файла Universal3D |
| static readonly [USD](../../aspose.threed/fileformat/usd/) | Универсальное описание сцены |
| static readonly [USDA](../../aspose.threed/fileformat/usda/) | Универсальное описание сцены в формате ASCII. |
| static readonly [USDZ](../../aspose.threed/fileformat/usdz/) | Сжатое Universal Scene Description |
| static readonly [VRML](../../aspose.threed/fileformat/vrml/) | Виртуальный язык моделирования реальности |
| static readonly [WavefrontOBJ](../../aspose.threed/fileformat/wavefrontobj/) | Формат файла Obj от Wavefront |
| static readonly [XBinary](../../aspose.threed/fileformat/xbinary/) | Файл DirectX X в бинарном формате |
| static readonly [XText](../../aspose.threed/fileformat/xtext/) | Файл DirectX X в бинарном формате |
| static readonly [Xyz](../../aspose.threed/fileformat/xyz/) | Файл облака точек Xyz |
| static readonly [Zip](../../aspose.threed/fileformat/zip/) | ZIP-архив, содержащий другие 3D форматы файлов. |
| static readonly [Draco](../../aspose.threed/fileformat/draco/) | Сетка Google Draco |
| static readonly [Microsoft3MF](../../aspose.threed/fileformat/microsoft3mf/) | Формат 3D производства Microsoft |
| static readonly [PDF](../../aspose.threed/fileformat/pdf/) | Портативный формат документов Adobe |
| static readonly [PLY](../../aspose.threed/fileformat/ply/) | Формат файлов Polygon или Stanford Triangle |
| static readonly [RvmBinary](../../aspose.threed/fileformat/rvmbinary/) | Модель системы управления проектированием заводов AVEGA в бинарном формате |
| static readonly [RvmText](../../aspose.threed/fileformat/rvmtext/) | Модель системы управления проектированием заводов AVEGA в текстовом формате |

### См. также

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


