---
title: IRenderTexture
second_title: Referencia de API de Aspose.3D para Java
description: La interfaz de la textura de renderizado
type: docs
weight: 250
url: /es/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

La interfaz de la textura de renderizado
## Métodos

| Método | Descripción |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | Textura del búfer de profundidad |
| [getTargets()](#getTargets--) | Objetivos de salida de color. |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


Textura del búfer de profundidad

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


Objetivos de salida de color.

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> - Objetivos de salida de color.
