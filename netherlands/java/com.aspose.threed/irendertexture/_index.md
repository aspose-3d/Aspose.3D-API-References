---
title: IRenderTexture
second_title: Aspose.3D for Java API-referentie
description: De interface van render texture
type: docs
weight: 250
url: /nl/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

De interface van render texture
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | Depth-buffertekstuur |
| [getTargets()](#getTargets--) | Kleuruitvoertargets. |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


Depth-buffertekstuur

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


Kleuruitvoertargets.

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> - Kleuruitvoertargets.
