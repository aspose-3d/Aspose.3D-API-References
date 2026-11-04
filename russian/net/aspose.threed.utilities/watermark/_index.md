---
title: "Класс Watermark"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Utilities.Watermark. Утилита для кодирования/декодирования слепой водяной метки в/из сетки"
type: docs
weight: 2950
url: /ru/net/aspose.threed.utilities/watermark/
---
## Watermark class

Утилита для кодирования/декодирования скрытой водяной метки в/из сетки.

```csharp
public class Watermark
```

## Методы

| Имя | Описание |
| --- | --- |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark)(Mesh) | Декодировать водяную метку из сетки |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark_1)(Mesh, string) | Декодировать водяную метку из сетки |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark)(Mesh, string) | Кодировать текст в слепую водяную метку mesh'. |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_1)(Mesh, string, string) | Кодировать текст в слепую водяную метку mesh'. |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_2)(Mesh, string, string, bool) | Кодировать текст в слепую водяную метку mesh'. |

## Примечания

Обе функции [`EncodeWatermark`](./encodewatermark/) и [`DecodeWatermark`](./decodewatermark/) выполняют проверку лицензии. Использование в режиме пробной версии вызовет исключение, вы можете использовать [`SuppressTrialException`](../../aspose.threed/trialexception/suppresstrialexception/) для подавления исключения, но это не снимет ограничение здесь. Для использования этих функций без каких-либо ограничений требуется действительная лицензия.

## Примеры

Следующий код показывает, как закодировать слепую водяную метку в сетку и декодировать её.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", null);
var watermark = Watermark.DecodeWatermark(encodedMesh, null);
```

### См. также

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


