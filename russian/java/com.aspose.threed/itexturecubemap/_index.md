---
title: ITextureCubemap
second_title: Справочник API Aspose.3D для Java
description: Текстура кубической карты
type: docs
weight: 255
url: /ru/java/com.aspose.threed/itexturecubemap/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITextureCubemap extends ITextureUnit
```

Текстура кубической карты
## Методы

| Метод | Описание |
| --- | --- |
| [load(CubeFace face, TextureData data)](#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Загрузить данные в указанную грань |
| [load(CubeFaceData<TextureData> data)](#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Загрузить содержимое текстуры из указанного [TextureData](../../com.aspose.threed/texturedata) |
| [loadFromFiles(CubeFaceData<String> fileNames)](#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--) | Загрузить содержимое текстуры из указанных файлов |
| [save(CubeFace side, TextureData bitmap)](#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Сохранить указанную сторону в память |
| [save(CubeFaceData<TextureData> bitmap)](#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Сохранить содержимое текстуры в память. |
| [save(CubeFaceData<String> path, String format)](#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-) | Сохранить содержимое текстур сторон куба во внешние файлы. |
| [toBitmap(CubeFace side)](#toBitmap-com.aspose.threed.CubeFace-) | Преобразовать единицу текстуры в экземпляр [TextureData](../../com.aspose.threed/texturedata) |
### load(CubeFace face, TextureData data) {#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void load(CubeFace face, TextureData data)
```


Загрузить данные в указанную грань

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |
| data | [TextureData](../../com.aspose.threed/texturedata) |  |

### load(CubeFaceData<TextureData> data) {#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void load(CubeFaceData<TextureData> data)
```


Загрузить содержимое текстуры из указанного [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> |  |

### loadFromFiles(CubeFaceData<String> fileNames) {#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--}
```
public abstract void loadFromFiles(CubeFaceData<String> fileNames)
```


Загрузить содержимое текстуры из указанных файлов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileNames | com.aspose.threed.CubeFaceData<java.lang.String> |  |

### save(CubeFace side, TextureData bitmap) {#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void save(CubeFace side, TextureData bitmap)
```


Сохранить указанную сторону в память

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(CubeFaceData<TextureData> bitmap) {#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void save(CubeFaceData<TextureData> bitmap)
```


Сохранить содержимое текстуры в память.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitmap | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> | Результирующий bitmap для сохранения. |

### save(CubeFaceData<String> path, String format) {#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-}
```
public abstract void save(CubeFaceData<String> path, String format)
```


Сохранить содержимое текстур сторон куба во внешние файлы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | com.aspose.threed.CubeFaceData<java.lang.String> | Имена файлов для сохранения. |
| формат | java.lang.String | Формат изображения |

### toBitmap(CubeFace side) {#toBitmap-com.aspose.threed.CubeFace-}
```
public abstract TextureData toBitmap(CubeFace side)
```


Преобразовать единицу текстуры в экземпляр [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
