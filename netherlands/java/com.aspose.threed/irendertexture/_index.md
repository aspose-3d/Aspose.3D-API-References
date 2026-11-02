---
title: "IRenderTexture"
second_title: "Aspose.3D voor Java API-referentie"
description: "De interface van rendertexture"
type: docs
weight: 250
url: /nl/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

De interface van rendertexture
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | Depth-buffertextuur |
| [getTargets()](#getTargets--) | Kleuruitvoertargets. |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


Depth-buffertextuur

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


Kleuruitvoertargets.

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> - Kleuruitvoertargets.
