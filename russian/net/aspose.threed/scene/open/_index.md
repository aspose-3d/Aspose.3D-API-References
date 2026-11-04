---
title: "Scene.Open"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Scene. Открывает сцену из заданного потока, используя указанный формат файла"
type: docs
weight: 140
url: /ru/net/aspose.threed/scene/open/
---
## Open(Stream, FileFormat, CancellationToken) {#open_1}

Открывает сцену из указанного потока, используя указанный формат файла.

```csharp
public void Open(Stream stream, FileFormat format, CancellationToken cancellationToken = default)
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

Следующий код показывает, как открыть сцену из потока

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, FileFormat.GLTF2);
}
```

### См. также

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, LoadOptions, CancellationToken) {#open_2}

Открывает сцену из указанного потока, используя указанную конфигурацию ввода-вывода.

```csharp
public void Open(Stream stream, LoadOptions options, CancellationToken cancellationToken = default)
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

Следующий код показывает, как открыть сцену из потока с дополнительными параметрами загрузки

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    var opt = new FbxLoadOptions();
    opt.LookupPaths.Add("textures");
    scene.Open(stream, opt);
}
```

### См. также

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream) {#open}

Открывает сцену из указанного потока

```csharp
public void Open(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Входной поток, пользователь отвечает за его закрытие. |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ImportException](../../importexception/) | Выбрасывается, если входные данные не являются допустимым 3D-форматом |

## Примеры

Следующий код показывает, как открыть сцену из потока

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream);
}
```

### См. также

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, CancellationToken) {#open_3}

Открывает сцену из указанного потока

```csharp
public void Open(Stream stream, CancellationToken cancellationToken)
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

Следующий код показывает, как открыть сцену из потока с токеном отмены

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, cts.Token);
}
```

### См. также

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, FileFormat, CancellationToken) {#open_5}

Открывает сцену по указанному пути, используя указанный формат файла.

```csharp
public void Open(string fileName, FileFormat format, CancellationToken cancellationToken = default)
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

Следующий код показывает, как открыть сцену по имени файла с токеном отмены

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
scene.Open("input.fbx", FileFormat.FBX7400ASCII, cts.Token);

```

### См. также

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions) {#open_6}

Открывает сцену по указанному пути, используя указанный формат файла.

```csharp
public void Open(string fileName, LoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |
| options | LoadOptions | Более подробная конфигурация для открытия потока. |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ImportException](../../importexception/) | Выбрасывается, если входные данные не являются допустимым 3D-форматом |

## Примеры

Следующий код показывает, как открыть сцену по имени файла с дополнительными параметрами загрузки

```csharp
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts);
```

### См. также

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions, CancellationToken) {#open_7}

Открывает сцену по указанному пути, используя указанный формат файла.

```csharp
public void Open(string fileName, LoadOptions options, CancellationToken cancellationToken)
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

Следующий код показывает, как открыть сцену по имени файла с дополнительными параметрами загрузки и токеном отмены

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts, cts.Token);
```

### См. также

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string) {#open_4}

Открывает сцену по указанному пути

```csharp
public void Open(string fileName)
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

Следующий код показывает, как открыть сцену по имени файла

```csharp
Scene scene = new Scene();
scene.Open("input.fbx");
```

### См. также

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, CancellationToken) {#open_8}

Открывает сцену по указанному пути

```csharp
public void Open(string fileName, CancellationToken cancellationToken)
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

Следующий код показывает, как открыть сцену по имени файла и источник токена отмены

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
scene.Open("input.fbx", cts.Token);
```

### См. также

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


