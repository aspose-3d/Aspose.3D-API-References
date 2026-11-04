---
title: "Watermark.DecodeWatermark"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Watermark. Декодировать водяной знак из сетки"
type: docs
weight: 10
url: /ru/net/aspose.threed.utilities/watermark/decodewatermark/
---
## DecodeWatermark(Mesh) {#decodewatermark}

Декодировать водяную метку из сетки

```csharp
public static string DecodeWatermark(Mesh input)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | Сетка | Сетка для извлечения водяного знака |

### Возвращаемое значение

Слепой водяной знак или null, если водяной знак не декодирован.

### Исключения

| исключение | условие |
| --- | --- |
| UnauthorizedAccessException | Сетка защищена паролем, и предоставленный пароль неверен. |

## Примечания

Оба [`EncodeWatermark`](../encodewatermark/) и `DecodeWatermark` выполняют проверку лицензии. При использовании в пробной версии будет выброшено исключение, вы можете использовать [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) для подавления исключения, но это не снимет ограничение здесь. Для использования этих функций без ограничений требуется действительная лицензия.

## Примеры

Следующий код показывает, как декодировать слепой водяной знак из сетки, сохранённой в 3D‑файле.

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh);
```

### См. также

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## DecodeWatermark(Mesh, string) {#decodewatermark_1}

Декодировать водяную метку из сетки

```csharp
public static string DecodeWatermark(Mesh input, string password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | Сетка | Сетка для извлечения водяного знака |
| пароль | String | Пароль для расшифровки водяного знака |

### Возвращаемое значение

Слепой водяной знак или null, если водяной знак не декодирован.

### Исключения

| исключение | условие |
| --- | --- |
| UnauthorizedAccessException | Сетка защищена паролем, и предоставленный пароль неверен. |

## Примеры

Следующий код показывает, как декодировать слепой водяной знак из сетки, сохранённой в 3D‑файле.

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh, "password");
```

### См. также

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


