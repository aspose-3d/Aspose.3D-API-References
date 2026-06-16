---
title: "IRenderTexture"
second_title: "Aspose.3D for Java API 参考"
description: "渲染纹理的接口"
type: docs
weight: 250
url: /zh/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

渲染纹理的接口
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | 深度缓冲纹理 |
| [getTargets()](#getTargets--) | 颜色输出目标。 |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


深度缓冲纹理

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


颜色输出目标。

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> - 颜色输出目标。
