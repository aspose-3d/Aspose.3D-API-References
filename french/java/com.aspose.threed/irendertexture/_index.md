---
title: "IRenderTexture"
second_title: "Référence d'API Aspose.3D pour Java"
description: "L'interface de la texture de rendu"
type: docs
weight: 250
url: /fr/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

L'interface de la texture de rendu
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | Texture du tampon de profondeur |
| [getTargets()](#getTargets--) | Cibles de sortie couleur. |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


Texture du tampon de profondeur

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


Cibles de sortie couleur.

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> - Cibles de sortie couleur.
