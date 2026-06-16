---
title: "IRenderTexture"
second_title: "Aspose.3D for Java API Referansı"
description: "Render dokusunun arayüzü"
type: docs
weight: 250
url: /tr/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

Render dokusunun arayüzü
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | Derinlik tamponu dokusu |
| [getTargets()](#getTargets--) | Renk çıkış hedefleri. |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


Derinlik tamponu dokusu

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


Renk çıkış hedefleri.

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> - Renk çıkış hedefleri.
