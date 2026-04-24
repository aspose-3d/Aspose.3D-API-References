---
title: IRenderTexture
second_title: Aspose.3D for Java API-referens
description: Gränssnittet för renderingstextur
type: docs
weight: 250
url: /sv/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

Gränssnittet för renderingstextur
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | Djupbufferttextur |
| [getTargets()](#getTargets--) | Färgutgångsmål. |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


Djupbufferttextur

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


Färgutgångsmål.

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> - Färgutgångsmål.
