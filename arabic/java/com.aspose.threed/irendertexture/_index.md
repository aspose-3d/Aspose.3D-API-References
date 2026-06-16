---
title: "IRenderTexture"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "واجهة الملمس المصور"
type: docs
weight: 250
url: /ar/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

واجهة الملمس المصور
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | قوام مخزن العمق |
| [getTargets()](#getTargets--) | أهداف إخراج اللون. |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


قوام مخزن العمق

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


أهداف إخراج اللون.

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> - أهداف إخراج اللون.
