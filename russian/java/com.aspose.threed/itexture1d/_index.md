---
title: ITexture1D
second_title: Справочник API Aspose.3D для Java
description: 1D текстура
type: docs
weight: 252
url: /ru/java/com.aspose.threed/itexture1d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture1D extends ITextureUnit
```

1D текстура
## Методы

| Метод | Описание |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | Загрузить содержимое текстуры из указанного Bitmap |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | Сохранить содержимое текстуры во внешний файл. |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | Сохранить содержимое текстуры во внешний файл. |
| [toBitmap()](#toBitmap--) | Преобразовать единицу текстуры в экземпляр [TextureData](../../com.aspose.threed/texturedata) |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


Загрузить содержимое текстуры из указанного Bitmap

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


Сохранить содержимое текстуры во внешний файл.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Результирующий bitmap для сохранения. |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


Сохранить содержимое текстуры во внешний файл.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | java.lang.String | Имя файла для сохранения. |
| формат | java.lang.String | Формат изображения |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


Преобразовать единицу текстуры в экземпляр [TextureData](../../com.aspose.threed/texturedata)

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
