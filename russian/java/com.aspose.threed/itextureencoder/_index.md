---
title: ITextureEncoder
second_title: Справочник API Aspose.3D для Java
description: Внешний кодировщик текстур должен реализовать этот интерфейс для кодирования.
type: docs
weight: 257
url: /ru/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

Внешний кодировщик текстур должен реализовать этот интерфейс для кодирования.
## Методы

| Метод | Описание |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | Кодировать данные текстуры в поток |
| [getFileExtension()](#getFileExtension--) | Имя расширения файла (без точки) этого кодировщика |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


Кодировать данные текстуры в поток

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | Данные текстуры, которые необходимо закодировать |
| stream | [Stream](../../com.aspose.threed/stream) | Выходной поток |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


Имя расширения файла (без точки) этого кодировщика

**Returns:**
java.lang.String - Имя расширения файла (без точки) этого кодировщика
