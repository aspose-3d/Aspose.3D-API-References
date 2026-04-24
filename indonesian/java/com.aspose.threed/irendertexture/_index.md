---
title: IRenderTexture
second_title: Referensi API Aspose.3D untuk Java
description: Antarmuka tekstur render.
type: docs
weight: 250
url: /id/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

Antarmuka tekstur render.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | Tekstur buffer kedalaman |
| [getTargets()](#getTargets--) | Target output warna. |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


Tekstur buffer kedalaman

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


Target output warna.

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> - Target output warna.
