---
title: MaterialConverter
second_title: Справочник API Aspose.3D для Java
description: Пользовательский конвертер для преобразования оригинального материала геометрии в материал GLTFs PBR.
type: docs
weight: 260
url: /ru/java/com.aspose.threed/materialconverter/
---
```
public interface MaterialConverter
```

Пользовательский конвертер для преобразования оригинального материала геометрии в PBR‑материал GLTF.
## Методы

| Метод | Описание |
| --- | --- |
| [call(Material mat)](#call-com.aspose.threed.Material-) | Пользовательский конвертер для преобразования оригинального материала геометрии в PBR‑материал GLTF. |
### call(Material mat) {#call-com.aspose.threed.Material-}
```
public abstract Material call(Material mat)
```


Пользовательский конвертер для преобразования оригинального материала геометрии в PBR‑материал GLTF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mat | [Material](../../com.aspose.threed/material) | Экземпляр старого материала |

**Returns:**
[Material](../../com.aspose.threed/material) - New material instance
