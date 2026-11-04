---
title: "Scene.FromStream"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Scene. Открывает сцену из заданного потока, используя указанный формат файла"
type: docs
weight: 30
url: /ru/net/aspose.threed/scene/fromstream/
---
## FromStream(Stream, FileFormat, CancellationToken) {#fromstream}

Открывает сцену из указанного потока, используя указанный формат файла.

```csharp
public static Scene FromStream(Stream stream, FileFormat format, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Входной поток, пользователь отвечает за его закрытие. |
| формат | FileFormat | Формат файла. |
| cancellationToken | CancellationToken | Токен отмены для задачи загрузки |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ImportException](../../importexception/) | Выбрасывается, если входные данные не являются допустимым 3D-форматом |

## Примеры

Следующий код показывает, как создать сцену из потока

```csharp
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream);
}
```

### См. также

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, LoadOptions, CancellationToken) {#fromstream_1}

Открывает сцену из указанного потока, используя указанную конфигурацию ввода-вывода.

```csharp
public static Scene FromStream(Stream stream, LoadOptions options, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Входной поток, пользователь отвечает за его закрытие. |
| options | LoadOptions | Более подробная конфигурация для открытия потока. |
| cancellationToken | CancellationToken | Токен отмены для задачи загрузки |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ImportException](../../importexception/) | Выбрасывается, если входные данные не являются допустимым 3D-форматом |

## Примеры

Следующий код показывает, как создать сцену из потока с параметрами загрузки

```csharp
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, opts);
}
```

### См. также

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, CancellationToken) {#fromstream_2}

Открывает сцену из указанного потока

```csharp
public static Scene FromStream(Stream stream, CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Входной поток, пользователь отвечает за его закрытие. |
| cancellationToken | CancellationToken | Токен отмены для задачи загрузки |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ImportException](../../importexception/) | Выбрасывается, если входные данные не являются допустимым 3D-форматом |

## Примеры

Следующий код показывает, как создать сцену из потока с источником токена отмены

```csharp
var cts = new CancellationTokenSource();
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, cts.Token);
}
```

### См. также

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


