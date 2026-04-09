---
title: IRenderTexture
second_title: Справочник API Aspose.3D для Java
description: Интерфейс рендер‑текстуры
type: docs
weight: 250
url: /ru/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

Интерфейс рендер‑текстуры
## Методы

| Метод | Описание |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | Текстура буфера глубины. |
| [getTargets()](#getTargets--) | Целевые объекты вывода цвета. |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


Текстура буфера глубины.

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


Целевые объекты вывода цвета.

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> — целевые объекты вывода цвета.
