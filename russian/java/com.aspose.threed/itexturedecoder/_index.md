---
title: ITextureDecoder
second_title: Справочник API Aspose.3D для Java
description: Внешний декодер текстур должен реализовать этот интерфейс для декодирования.
type: docs
weight: 256
url: /ru/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

Внешний декодер текстур должен реализовать этот интерфейс для декодирования.
## Методы

| Метод | Описание |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | Декодировать текстуру из потока, вернуть null, если декодирование не удалось. |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


Декодировать текстуру из потока, вернуть null, если декодирование не удалось.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Поток источника данных текстуры |
| reverseY | boolean | Отразить текстуру |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
