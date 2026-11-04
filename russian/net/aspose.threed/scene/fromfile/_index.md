---
title: "Scene.FromFile"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Scene. Открывает сцену по указанному пути, используя заданный формат файла"
type: docs
weight: 20
url: /ru/net/aspose.threed/scene/fromfile/
---
## FromFile(string, FileFormat, CancellationToken) {#fromfile_1}

Открывает сцену по указанному пути, используя указанный формат файла.

```csharp
public static Scene FromFile(string fileName, FileFormat format, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |
| формат | FileFormat | Формат файла. |
| cancellationToken | CancellationToken | Токен отмены для задачи загрузки |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ImportException](../../importexception/) | Выбрасывается, если входные данные не являются допустимым 3D-форматом |

## Примеры

Следующий код показывает, как создать сцену из файла

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", FileFormat.FBX7400ASCII, cts.Token);
```

### См. также

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, LoadOptions, CancellationToken) {#fromfile_2}

Открывает сцену по указанному пути, используя указанный формат файла.

```csharp
public static Scene FromFile(string fileName, LoadOptions options, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |
| options | LoadOptions | Более подробная конфигурация для открытия потока. |
| cancellationToken | CancellationToken | Токен отмены для задачи загрузки |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ImportException](../../importexception/) | Выбрасывается, если входные данные не являются допустимым 3D-форматом |

## Примеры

Следующий код показывает, как создать сцену из файла

```csharp
var cts = new CancellationTokenSource();
var opt = new FbxLoadOptions();
opt.LookupPaths.Add("textures");
Scene scene = Scene.FromFile("input.fbx", opt, cts.Token);
```

### См. также

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string) {#fromfile}

Открывает сцену по указанному пути

```csharp
public static Scene FromFile(string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ImportException](../../importexception/) | Выбрасывается, если входные данные не являются допустимым 3D-форматом |

## Примеры

Следующий код показывает, как создать сцену из файла

```csharp
Scene scene = Scene.FromFile("input.fbx");
```

### См. также

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, CancellationToken) {#fromfile_3}

Открывает сцену по указанному пути

```csharp
public static Scene FromFile(string fileName, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |
| cancellationToken | CancellationToken | Токен отмены для задачи загрузки |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ImportException](../../importexception/) | Выбрасывается, если входные данные не являются допустимым 3D-форматом |

## Примеры

Следующий код показывает, как создать сцену из файла

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", cts.Token);
```

### См. также

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


