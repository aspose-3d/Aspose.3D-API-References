---
title: "Watermark.EncodeWatermark"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Watermark. Закодировать текст в слепой водяной знак сетки"
type: docs
weight: 20
url: /ru/net/aspose.threed.utilities/watermark/encodewatermark/
---
## EncodeWatermark(Mesh, string) {#encodewatermark}

Кодировать текст в слепую водяную метку mesh'.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | Сетка | Сетка для кодирования слепого водяного знака |
| текст | String | Текст для кодирования в сетку |

### Возвращаемое значение

Новый экземпляр сетки с закодированным слепым водяным знаком

## Примечания

Оба `EncodeWatermark` и [`DecodeWatermark`](../decodewatermark/) выполняют проверку лицензии. При использовании пробной версии будет выброшено исключение, вы можете использовать [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) чтобы подавить исключение, но это не снимет ограничение здесь. Для использования этих функций без ограничений требуется действительная лицензия.

## Примеры

Следующий код показывает, как закодировать скрытый водяной знак в сетку и сохранить в файл ply.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello");
new Scene(encodedMesh).Save("test.ply");
```

### См. также

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string) {#encodewatermark_1}

Кодировать текст в слепую водяную метку mesh'.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | Сетка | Сетка для кодирования слепого водяного знака |
| текст | String | Текст для кодирования в сетку |
| пароль | String | Пароль для защиты водяного знака, он необязателен. |

### Возвращаемое значение

Новый экземпляр сетки с закодированным слепым водяным знаком

## Примечания

Оба `EncodeWatermark` и [`DecodeWatermark`](../decodewatermark/) выполняют проверку лицензии. При использовании пробной версии будет выброшено исключение, вы можете использовать [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) чтобы подавить исключение, но это не снимет ограничение здесь. Для использования этих функций без ограничений требуется действительная лицензия.

## Примеры

Следующий код показывает, как закодировать скрытый водяной знак в сетку и сохранить в файл ply.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### См. также

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string, bool) {#encodewatermark_2}

Кодировать текст в слепую водяную метку mesh'.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password, bool permanent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | Сетка | Сетка для кодирования слепого водяного знака |
| текст | String | Текст для кодирования в сетку |
| пароль | String | Пароль для защиты водяного знака, он необязателен. |
| постоянный | Boolean | Постоянный водяной знак не будет перезаписан или удалён. |

### Возвращаемое значение

Новый экземпляр сетки с закодированным слепым водяным знаком

## Примечания

Оба `EncodeWatermark` и [`DecodeWatermark`](../decodewatermark/) выполняют проверку лицензии. При использовании пробной версии будет выброшено исключение, вы можете использовать [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) чтобы подавить исключение, но это не снимет ограничение здесь. Для использования этих функций без ограничений требуется действительная лицензия.

## Примеры

Следующий код показывает, как закодировать скрытый водяной знак в сетку и сохранить в файл ply.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### См. также

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


