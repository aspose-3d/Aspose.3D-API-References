---
title: "ITextureDecoder.Decode"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод ITextureDecoder. Декодирует текстуру из потока, возвращает null, если декодирование не удалось"
type: docs
weight: 10
url: /ru/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

Декодировать текстуру из потока, вернуть null, если декодирование не удалось.

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток источника данных текстуры |
| reverseY | Boolean | Отразить текстуру |

### Возвращаемое значение

Декодированные данные текстуры или null, если не поддерживается.

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается, когда не удалось прочитать данные из потока |

### См. также

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


