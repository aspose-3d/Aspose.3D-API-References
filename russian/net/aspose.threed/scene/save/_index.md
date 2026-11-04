---
title: "Scene.Save"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Scene. Сохраняет сцену в поток, используя указанный формат файла"
type: docs
weight: 160
url: /ru/net/aspose.threed/scene/save/
---
## Save(Stream, FileFormat) {#save}

Сохраняет сцену в поток, используя указанный формат файла.

```csharp
public void Save(Stream stream, FileFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Входной поток, пользователь отвечает за его закрытие. |
| формат | FileFormat | Формат. |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ExportException](../../exportexception/) | Выбрасывается при неудачной попытке экспортировать сцену в указанный 3D‑формат |

## Примеры

Следующий код показывает, как сохранить сцену

```csharp
Scene scene = Scene.FromFile("input.fbx");
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ);
}
```

### См. также

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, FileFormat, CancellationToken) {#save_1}

Сохраняет сцену в поток, используя указанный формат файла.

```csharp
public void Save(Stream stream, FileFormat format, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Входной поток, пользователь отвечает за его закрытие. |
| формат | FileFormat | Формат. |
| cancellationToken | CancellationToken | Токен отмены для задачи сохранения |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ExportException](../../exportexception/) | Выбрасывается при неудачной попытке экспортировать сцену в указанный 3D‑формат |

## Примеры

Следующий код показывает, как сохранить сцену

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ, cts.Token);
}
```

### См. также

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions) {#save_2}

Сохраняет сцену в поток, используя указанный формат файла.

```csharp
public void Save(Stream stream, SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Входной поток, пользователь отвечает за его закрытие. |
| options | SaveOptions | Более подробная конфигурация для сохранения потока. |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ExportException](../../exportexception/) | Выбрасывается при неудачной попытке экспортировать сцену в указанный 3D‑формат |

## Примеры

Следующий код показывает, как сохранить сцену

```csharp
Scene scene = Scene.FromFile("input.fbx");
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### См. также

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions, CancellationToken) {#save_3}

Сохраняет сцену в поток, используя указанный формат файла.

```csharp
public void Save(Stream stream, SaveOptions options, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Входной поток, пользователь отвечает за его закрытие. |
| options | SaveOptions | Более подробная конфигурация для сохранения потока. |
| cancellationToken | CancellationToken | Токен отмены для задачи сохранения |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ExportException](../../exportexception/) | Выбрасывается при неудачной попытке экспортировать сцену в указанный 3D‑формат |

## Примеры

Следующий код показывает, как сохранить сцену

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt, cts.Token);
}
```

### См. также

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string) {#save_4}

Сохраняет сцену по указанному пути, используя указанный формат файла.

```csharp
public void Save(string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ExportException](../../exportexception/) | Выбрасывается при неудачной попытке экспортировать сцену в указанный 3D‑формат |

## Примеры

Следующий код показывает, как сохранить сцену

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz");
```

### См. также

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat) {#save_5}

Сохраняет сцену по указанному пути, используя указанный формат файла.

```csharp
public void Save(string fileName, FileFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |
| формат | FileFormat | Формат. |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ExportException](../../exportexception/) | Выбрасывается при неудачной попытке экспортировать сцену в указанный 3D‑формат |

## Примеры

Следующий код показывает, как сохранить сцену

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ);
```

### См. также

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat, CancellationToken) {#save_6}

Сохраняет сцену по указанному пути, используя указанный формат файла.

```csharp
public void Save(string fileName, FileFormat format, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |
| формат | FileFormat | Формат. |
| cancellationToken | CancellationToken | Токен отмены для задачи сохранения |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ExportException](../../exportexception/) | Выбрасывается при неудачной попытке экспортировать сцену в указанный 3D‑формат |

## Примеры

Следующий код показывает, как сохранить сцену

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ, cts.Token);
```

### См. также

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions) {#save_7}

Сохраняет сцену по указанному пути, используя указанный формат файла.

```csharp
public void Save(string fileName, SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |
| options | SaveOptions | Более подробная конфигурация для сохранения потока. |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ExportException](../../exportexception/) | Выбрасывается при неудачной попытке экспортировать сцену в указанный 3D‑формат |

## Примеры

Следующий код показывает, как сохранить сцену

```csharp
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts);
```

### См. также

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions, CancellationToken) {#save_8}

Сохраняет сцену по указанному пути, используя указанный формат файла.

```csharp
public void Save(string fileName, SaveOptions options, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |
| options | SaveOptions | Более подробная конфигурация для сохранения потока. |
| cancellationToken | CancellationToken | Токен отмены для задачи сохранения |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается при ошибке чтения входных данных |
| [ExportException](../../exportexception/) | Выбрасывается при неудачной попытке экспортировать сцену в указанный 3D‑формат |

## Примеры

Следующий код показывает, как сохранить сцену

```csharp
var cts = new CancellationTokenSource();
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts, cts.Token);
```

### См. также

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


