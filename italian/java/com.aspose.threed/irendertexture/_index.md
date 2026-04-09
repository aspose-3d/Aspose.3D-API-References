---
title: IRenderTexture
second_title: Aspose.3D for Java API Reference
description: L'interfaccia della texture di rendering
type: docs
weight: 250
url: /it/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

L'interfaccia della texture di rendering
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | Texture del buffer di profondità |
| [getTargets()](#getTargets--) | Obiettivi di output colore. |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


Texture del buffer di profondità

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


Obiettivi di output colore.

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> - Obiettivi di output colore.
